Curseforge hook push with tag
```sh
VERSION="v1.0.0"

ga . && gc $VERSION && git tag -a $VERSION -m $VERSION && git push origin --tags

git tag -a $VERSION -m $VERSION
# or
git tag $VERSION

git push origin --tags
# or
git push origin $VERSION
```
