# AutoComment
I can't be the only one that forgets to put header comments with my name, date and project in them.

This is a bash script you can run that checks for files that do not have a comment in the first line.

I made it a project because I had a bunch of files to add header comments to that I forgot about.
As of now, it only works on python files, but I hope to have to expand this to comment other file types as well.

Let's see where this can go!

# Instructions
Place the auto_comment.sh in the root of your project you'd like to comment
Run it and follow the instructions
Enjoy!

# Additional Required Mac Instructions
1. Make sure you have homebrew installed
2. in terminal, enter: brew install gnu-sed --with-default-names
3. then enter: PATH="/usr/local/opt/gnu-sed/libexec/gnubin:$PATH"
  This installs gnu-sed and prioritizes it over mac sed in your PATH
