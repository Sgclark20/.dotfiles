.gitignore: This file tells Git to ignore certain files or directories

Vimrc: this file allows you to change the "settings" of the code you are writting, for example color, ruler.

bashrc_custom: with the given info in this file it is creating different aliases

Linux.sh: this file is in charge of doing a number of things. the first being that it is redirections any output from echo and putting it into a file called linuxsetup.log. The second thing is it is creating a directory called .Trash in the Home Directory. The last two things its doing is overwritting the contents of the vimrc file and putting them into .vimrc file, and finally it is adding the statement ‘source ∼/.dotfiles/etc/bashrc custom’ to the end of the .bashrc

Cleanup.sh: the main job of this script is to reverse anything that was done in the ‘linux.sh’ script
