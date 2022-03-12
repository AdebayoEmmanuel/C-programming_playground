/**# C-programming_playground
*This repository contains all my personal C practice codes and 
*mini projects including head_first C practices
*I shall be adopting the Betty coding style 
*and to ensure this, betty linter is installed and used on every code.
*to install betty linter: clone the betty repo ==>> https://github.com/holbertonschool/Betty to your local machine, cd into the Betty dir and 
*Install the linter with `sudo ./install.sh`
*emacs or vi a new file called betty, and copy the script below:
`#!/bin/bash
# Simply a wrapper script to keep you from having to use betty-style
# and betty-doc separately on every item.
# Originally by Tim Britton (@wintermanc3r), multiargument added by
# Larry Madeo (@hillmonkey)

BIN_PATH="/usr/local/bin"
BETTY_STYLE="betty-style"
BETTY_DOC="betty-doc"

if [ "$#" = "0" ]; then
    echo "No arguments passed."
    exit 1
fi

for argument in "$@" ; do
    echo -e "\n========== $argument =========="
    ${BIN_PATH}/${BETTY_STYLE} "$argument"
    ${BIN_PATH}/${BETTY_DOC} "$argument"
done`
*Once saved, exit file and change permissions to apply to all users with chmod a+x betty
*Move the betty file into /bin/ directory or somewhere else in your $PATH with sudo mv betty /bin/
*You can now type betty <filename> to run the Betty linter!
*visit the betty wiki ==>> https://github.com/holbertonschool/Betty/wiki to learn about the betty coding style.
*/
