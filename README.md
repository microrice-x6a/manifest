# manifest

[mainfest format](https://gerrit.googlesource.com/git-repo/+/HEAD/docs/manifest-format.md)

repo init manifest

```
mkdir -p ~/lineageos-build/x6a
cd ~/lineageos-build/x6a
repo init -u https://github.com/microrice-x6a/manifest.git -b main
repo sync -c --force-sync --no-clone-bundle --no-tags -j$(nproc --all)
```
