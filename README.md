# How to use command-line instructions for new web developers, or "what does 'composer update' mean?"

**TL;DR:** Write it in the command line at the desired folder.

When I was just starting to learn web development, I stumbled upon many instructions on installing things through the command line, mostly related to package managers like NPM and Composer. However, no one ever bothered to explain what exactly was the context I had to write these commands in, they just left me with a line of code I had to write... somewhere. Worse, I'm a Windows user, so even if there was some shell reference, it was always Unix. These inconveniences for some time had me long for a world where package managers didn't exist and everything could be done by copying files instead of installing them through the CLI.

Turns out that, every time somebody asks you to `composer update` or `npm install` or `yarn add` on a project, they're actually expecting you to *write that command inside your project folder root*. 

For Windows users, there's the `cd path/to/directory`, but if you hold shift and right-click on a folder on Windows Explorer, there should be an option for opening a command window inside that folder, ready to accept these commands. I can't speak for Mac or Linux users, but there should be a simple way to set a folder up for these as well.

I hope that helps someone, somewhere. I sure wish somebody told me that sooner when I was struggling.

For you, library documentation writers: knowing what I described above is an assumption larger than it seems.
