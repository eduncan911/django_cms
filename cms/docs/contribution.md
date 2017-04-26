Contribution Guide
==================

For contributing to django-cms follow these steps:

You need either [git](http://git-scm.com/) or [Mercurial](http://www.selenic.com/mercurial/)
with the [hg-git](http://hg-git.github.com/) extension installed.

You need an account on [github](http://www.github.com/).

On github you can see all the [open tickets](http://github.com/digi604/django-cms-2.0/issues).
Please be sure to check there first before you open a new one.

Go to the [project-page](http://github.com/digi604/django-cms-2.0/) and click on the fork button.
This creates your own repository of django-cms2 and enables you to push updates to this repository.

On your fork you should see "Your Clone URL:". Copy the URL and clone it with git or hg-git.

	$ git clone YOURURL
	
or 
	
	$ hg gclone YOURURL

Make your changes and commit.

	$ git commit
	
or 
	
	$ hg commit
	
After you are finished you can push to github. 

	$ git push origin
	
or 
	
	$ hg gpush origin

After you have done the push, your changes should show up in the
[project network](http://github.com/digi604/django-cms-2.0/network).

You can now press on "pull request" to send the project leaders a message of what
your changes contain and inform them that there are new changes ready to be
incorporated into the master tree.

After some time you local and github repository will probably become
out-of-date.  To get the newest changesets add a new remote:

	$ git remote add upstream git://github.com/digi604/django-cms-2.0.git
	
or 
	
	$ hg gremote add upstream git://github.com/digi604/django-cms-2.0.git
	
After this you can do a fetch from upstream:

	$ git fetch upstream 	# only download
	$ git pull upstream 	# download and merge
	
or 
	
	$ hg gfetch upstream 	# download
	$ hg update 		# merge

Now your repository is up-to-date again.

If you have questions you may wish to read some tutorials about git or Mercurial
or ask on IRC or the mailing list.
