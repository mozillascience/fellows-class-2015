## README.md for Richard!

This is a stub file, delete/redo as you wish.

### basics

This is your personal directory in the fellows repo. You can add all of your deliverables of all formats, data, and any notes/files that you'd like to share as part of your [roadmap](https://github.com/mozillascience/fellows-class-2015/blob/master/roadmap.md) progression through the fellowship. 

Please add them to your folder on a branch with your name (instructions on this below).

### instructions

You've been added to the repository as a collaborator so you should have read/write access. We [discussed on our 12/03 fellows call](https://public.etherpad-mozilla.org/p/2015-science-fellows-dec03) (see line 39) that giving everyone a directory, and allowing them to create branches might be the best way to coordinate resource sharing. Follow the guide below

Currently, the structure is like this:

```
fellows-class-2015/
	_christie/
		README.md
	_jason/
		README.md
	_joey/
		README.md
	_richard/
		README.md
	explore/
		1-challenge_exercise.md
		...
	reference/
		contacts.md
```

You'll not that you each have a repository with a readme, this is where you can add files and submit deliverables. The `_` before your names is just to keep the repo tidy and the fellows at the top...whoot.

If you know how to make a branch and work collaboratively in git, you can skip the rest, but I included some workflow details just in case. You probably all know this because you are smarties! Don't mind me I just like typing.

We will use Joey as an example, thanks Joey for being voluntold.

To add files so:

**on the CL**

* open Terminal
* clone the repo | `git clone git@github.com:mozillascience/fellows-class-2015.git`
* if you've already cloned it, make sure to `git pull` to collect all recent changes by other users and avoid merge conflicts later
* navigate to your fellows-class-2015 repository 
* create a new branch for your name | `git branch joey`
* move into the branch to make changes | `git checkout joey`
	* now (on joey's branch), Joey can create | `cd` into your directory, for example `cd fellows-class-2015/joey`
	* add files to the folder or make changes to the existing README.md
	* when done, add them on the CL | `git add .`
	* commit them | `git commit -m "some message here"`
	* push them up to the public repo | `git push origin joey`


**in the browser**

* you can also create branches by selecting the dropdown in the github interface, and creating a new branch
![](http://imgur.com/D2xV7G6.jpg)
![](http://imgur.com/v84VWvc.jpg)

* you can add files in markdown with the "new file" button in that same area of the interface, and save to commit them
![](http://i.imgur.com/EcjFdUD.jpg)

Rinse repeat for future additions, you might also want to update from master occasionally as we move through project phases, so you can `fetch` changes and `rebase` from master, but no pressure right now, we can always cherry pick your folders in the future for a master merge.

Thanks for reading!