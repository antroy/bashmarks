Bashmarks
=========

This is a bookmarking tool for bash. It provides the following commands with tab completion:

`mark <alias>` - Bookmark the current directory with the given alias.
`go <alias>` - Go to the directory with the provided alias. Autocompletes on tab. Implemented using pushd to facilitate easy back functionality.
`marks` - Display all bookmarks.
`delmark <alias>` - Delete alias. Autocompletes.
`po` - alias for popd
`pd` - alias for pushd

Installation
------------

Save somewhere like you home directory. Source in your .bashrc:

    source bashmarks
