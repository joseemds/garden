## Recipes
### Get sha256 of  a tarball from github 
`curl -Ls https://github.com/repo/owner/archive/ref.tar.gz | sha256sum`

### Apply a patch directily from github
`curl -Ls https://github.com/repo/owner/commit/ref.patch | git apply`

###