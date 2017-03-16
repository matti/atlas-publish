# atlas-publish

Publishes vagrant boxes to Atlas with curl

```
vagrant package

brew install jq
git submodule add https://github.com/matti/atlas-publish
git submodule update --init

atlas-publish/publish.sh ATLAS_TOKEN ATLAS_USER ATLAS_BOX ATLAS_VERSION

# for example:
#   atlas-publish/publish.sh tokenabbacdabbacd matti better-bento-ubuntu-16.04 0.0.1
```
