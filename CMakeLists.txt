CMAKE_MINIMUM_REQUIRED (VERSION 3.14)
PROJECT (mxmlstat C)

INCLUDE_DIRECTORIES(
    ./
    ./vcnet
)

SET ( SRC_LIST_mxml
    mxml-attr.c
    mxml-entity.c
    mxml-file.c
    mxml-get.c
    mxml-index.c
    mxml-node.c
    mxml-private.c
    mxml-search.c
    mxml-string.c
)

ADD_LIBRARY( mxmlstat ${SRC_LIST_mxml} )
