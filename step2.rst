.. include:: cyverse_rst_defined_substitutions.txt

|CyVerse logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_


Cloning, Branching, & Versioning
-------------

**Description:**

In this step, you will learn more advanced skills including cloning a repo, the difference between branching and forking, and how to submit and accept pull requests.
----

Clone a repo
~~~~~~~~~~~~~~~~~~~

1. Click the down arrow "Clone or download"
2. Click "Open in Desktop"
3. Select where to save it
	- Create a folder for GitHub repos on your computer locally

.. code-block:: console
	git clone https://github.com/path/to/repo
	#can get path to repo under "Clone or download" arrow

-------

Commit
~~~~~~~~~~~~~~~~~~~
1. Create a file and put it in your *local* GitHub repo
2. Open Desktop
3. Fetch origin
4. Write a commit message & hit commit
5. Push to origin
6. See changes on the repo online

----

Create a branch
~~~~~~~~~~~~~~~~~~~
1. Select the down arrow on the repository page that says "Branch:master"
2. Create a new branch name

.. code-block:: console
	git checkout -b <new branch name>
	git branch -d <branch name>
	git push origin master
	git push --delete origin <branch name>

----

Make a pull request
~~~~~~~~~~~~~~~~~~~
1. From your branch, create a new file
2. Commit file to your branch
3. Hit "Compare & pull request"
4. Go to pull requests
5. "Merge pull request"
6. Delete branch
7. See it on the master branch

**Note** that you can always revert back to a previous version

.. code-block:: console
	git pull upstream master
	git commit
	#add in message
	git push origin <master branch name>

**Exercise:** Why would pull requests be important?

----

Etc.
~~~~

- Versioning
	1. Go to "Releases"
	2. Click "Create a new release"
	3. Tag version: Version #
	4. Release title: I usually put the date of the release, but any system can work

- Reactions:
	1. Create a new pull request
	2. Looking at the messages, click the smiley face to give a reaction

- Badges
	1. Go find a `badge <https://naereen.github.io/badges/>`_!
	2. Copy badge code into README:

.. code-block:: 
	[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

- Notifications:
	- get notified when there is an issue or pull request created
	- can also "watch" a repository and get updates

----

**Fix or improve this documentation**

Search for an answer:
|CyVerse Learning Center| or
|CyVerse Wiki|

----

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_

.. Comment: Place Images Below This Line
   use :width: to give a desired width for your image
   use :height: to give a desired height for your image
   replace the image name/location and URL if hyperlinked


 .. |Clickable hyperlinked image| image:: ./img/IMAGENAME.png
    :width: 500
    :height: 100
 .. _CyVerse logo: http://learning.cyverse.org/

 .. |Static image| image:: ./img/IMAGENAME.png
    :width: 25
    :height: 25



.. Comment: Place URLS Below This Line

   # Use this example to ensure that links open in new tabs, avoiding
   # forcing users to leave the document, and making it easy to update links
   # In a single place in this document

   .. |Substitution| raw:: html # Place this anywhere in the text you want a hyperlink

      <a href="REPLACE_THIS_WITH_URL" target="blank">Replace_with_text</a>


.. |Github Repo Link|  raw:: html

   <a href="https://github.com/CyVerse-learning-materials/git-for-mere-mortals" target="blank">Github Repo Link</a>
