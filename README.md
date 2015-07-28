# atlas-publish

Publishes vagrant boxes to Atlas with curl

    vagrant package
    git submodule add https://github.com/matti/atlas-publish
    git submodule update --init

    atlas-publish/publish.sh ATLAS_TOKEN ATLAS_USER ATLAS_BOX ATLAS_VERSION
