Venpad
------

### Why

RSS is broken, the web is dead, and blogging is broken. How do we distributed content in 2013? Why not use Git, because then I can type

	$ git pull origin master

to get new content. I get to see social cues, such as when something was updated, what changed since I last wrote, I can see diffs, I can see when writing goes away. Perhaps Git is the answer to the question Craig Mod posed a few years ago in [Post-Artifact Books and Publishingt](http://craigmod.com/journal/post_artifact/).

Or maybe people won't have the technical abilities to clone down a repo. But then again, do I want people reading my work who can't clone a repo? Probably not. Git has become the fundamental skill you need to know to be involved in technology. As Gwen Bell wrote in Git Commit, 'if you don't know Git, you don't know shit.' I have to agree, but I'm biased.

### What

I write into markdown files, you read them on your computer. If you'd like to render them, go right ahead. Or just read in your terminal.

### How

I write into this git repository. To read what I've written, clone the repository. You'll need to install [Git](http://git-scm.org) for this to work. 

	git clone git@github.com:venportman/venpad.git

To get new updates, navigate to the directory and type

	git pull origin master

This will bring my latest writing to your computer.
