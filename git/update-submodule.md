**Update submodules**

As a note for future travelers. If you set your depth too shallow, the git server may be configured not to advertise each individual commit, IIUC. We weren't seeing this issue in travis ci since it clones with depth 50, but local checkouts were broken.

`git submodule update --depth 50`