Bashmarks
=========

This is a bookmarking tool for bash built on the pushd/popd commands. It provides the following commands with tab completion:

- `mark <alias>` - Bookmark the current directory with the given alias.
- `mark` - Bookmark the current directory with alias equal to the directory name.
- `go <alias>` - Go to the directory with the provided alias. Autocompletes on tab. Implemented using pushd to facilitate easy back functionality.
- `marks` - Display all bookmarks.
- `delmark <alias>` - Delete alias. Autocompletes.
- `delmark` - Delete alias for this directory.
- `po` - alias for popd
- `pd` - alias for pushd

Note - the bookmarks are stored in a simple text file ~/.bookmarks and can be edited if desired.

Installation
------------

Save the bashmarks.sh script somewhere on your path, and source in your .bashrc:

    source bashmarks
