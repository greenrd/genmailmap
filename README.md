A script to try to generate `.mailmap` files for git.

Sample usage:

    $ genmailmap.sh
	$ git commit -m 'Added .mailmap'
	
By default, generated entries are _appended_ to any existing `.mailmap` file.
To make it instead _overwrite_ the file, run it like this:

    $ genmailmap.sh --
