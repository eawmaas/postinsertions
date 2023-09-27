## Intro
-This package contains one module (postupdated) which is used by the feathers. The feathers check for existence and activation of the module (postupdated) and if it's activated it displays a post-updated date.
-This package also contains all feathers in the topaz-theme rewritten to function with this package. 4 items are added to each feather, 1 to include a file on top of the post (above the title), 1 to include a file below the title, 1 to include a file above the post-body and one to include a file below the post-body.
-The files to include are html-files but they can contain text, html and twig (other extensions are not tested). If you do not want anything in a certain spot, then just leave that file empty.
-The files to include are present in themes/topaz/feathers/inserts/

## Attention
-if you include something, then it will be included in every post!
-this clean version has one pre-installed insert: post-updated in postheaderbottomtext.html, the file can be flushed ofcourse (not deleted). It appears below the title. If you want it on another spot, just the move the contents to the file that represents the spot where you want it to appear in your blogpost.
-every feather in themes/topaz has the features now, some validation-improvements have also been made but there are more that need ton be done
-it is possible to add more than one item to a spot in the post
-all other themes must have these feathers too (when tested properly and full valid HTML), easy copy-paste job

## Future
-Needs heavy tweaking, I want to build it to a level where you can switch insertions on and off on a post per post basis. This needs to be done in admin/manage/posts

## Documentation

The Chyrp Lite [wiki](https://chyrplite.net/wiki/) has comprehensive documentation
for users and developers.

## Authors

Chyrp Lite was created by the following people:

* Lite Developer: Daniel Pimley
* Chyrp Developer: Arian Xhezairi
* Project Founder: Alex Suraci
* Module authors and other contributors.

## Licenses

Chyrp Lite is Copyright 2008-2023 Alex Suraci, Arian Xhezairi, Daniel Pimley, and other contributors,
distributed under the [BSD license](https://raw.githubusercontent.com/xenocrat/chyrp-lite/master/LICENSE.md).
Please see the [licenses](licenses) directory for the full license text of all software packages distributed with Chyrp Lite.
