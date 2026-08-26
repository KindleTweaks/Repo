Hello contributor! A few simple rules should be followed when opening pull requests to this repository.

1. If updating a malformed package, always clone the repository and extract (`tar -xzvf`) the package, then update the source building on top of the latest contents. E.g.;
    - `mkdir src`
    - `cp packages/larkplayer/artifacts/larkplayer_2.9.0_kindlepw2-kindlehf.kpkg larkplayer_2.9.0_kindlepw2-kindlehf.tar.gz`
    - `cd src && tar -xzvf ../larkplayer_2.9.0_kindlepw2-kindlehf.tar.gz`
    - Edits...
    - `python kpm-helper.py package pack src Repo/`
    - `python kpm-helper.py repo add ./Repo larkplayer_2.9.0_kindlepw2-kindlehf.kpkg`

Adjust paths accordingly.

2. Always ensure the `manifest` version is constant and inline with what is in `manifest.json`, in packages and within the file itself.

3. Always abide by the licensing terms outlined in the `README`, having a `README.md` and `LICENSE` file in every package as well as having the required information outlined in this repository's main `README` file.

4. It's best practice to create separate `.kpkg` files for separate ABIs, but this is not a strict necessity.

5. Understand packages must be maintained or will be withdrawn from the repository.