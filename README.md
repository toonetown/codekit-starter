# codekit-starter
Some templates for kickstarting a [CodeKit](http://incident57.com/codekit/) project

## To run:
The installer is hosted in a separate branch, and can be launched by running:

    bash <(curl -fsSL https://raw.githubusercontent.com/toonetown/codekit-starter/project-base/install) [dirname]

Where `[dirname]` is the output directory to check out into.

This will do the following:

 - Check out the stub branch, and prompt you to set the project name
 - Set up that stub project as *your* "initial commit" (your own local master branch)
 - Set up a remote pointing to this project
 - Check out the latest code from this project into a branch called `codekit-starter`
 - Merge `codekit-starter` into your master, trying its hardest to merge correctly
 - Commits the merge
     - From this point on, you should be able to just pull changes from `codekit-starter` if you want
 - Opens your new project in CodeKit

