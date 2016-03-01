##Clay OS##
This file is for the developers.

Clay setup will be hosted at the repo.
Version is major.middle.minor-build. Major will be only changed on stage changes (Alpha -> Beta -> Release).
Middle will be changed when we add a bunch of features
Minor will be changed when we add a feature or a couple.
Build will be the same from start, and will not be reset to 0 at anytime.
A new build is made when you complete all the changes.

###Filesystem###
This OS will have a new fs API.
/foo/bar is absolute
foo/bar is relative
!/foo/bar means that ! is equal to the user's data folder
?top/foo/bar means the disk on the top of the computer.

###Structure###

* Root
  * Users
    * Default
    * (user name here)
      * Programs
      * Documents
      * Images
      * Config
      * Downloads
      * Desktop
  * Clay
    * lua
    * config
    * debug (crash dumps)
