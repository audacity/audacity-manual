This git repo contains the manual for Audacity


## Flow of Content

* We write the Audacity Manual at https://alphamanual.audacityteam.org
* We wget it and mangle it a little using our script, https://github.com/audacity/audacity/blob/master/scripts/mw2html_audacity/mw2html.py
* That content is then pushed as a commit to the GitHub repo.
* A script on our server detects the change at GitHub and pulls the changes to serve them.

## Wiki Tricks

There is a lot of content in our manual which would be prohibitively time consuming to produce without automated tools to help us.  This is particularly so of the many image maps in the manual.

* Most of our tricks are documented at https://wiki.audacityteam.org/wiki/Magicke_Spells
* The heavy lifting is done by our 'What Is That' page https://wiki.audacityteam.org/wiki/Using_WIT