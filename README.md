OpenNote [![Build Status](https://travis-ci.org/FoxUSA/OpenNote.png?branch=master)](https://travis-ci.org/FoxUSA/OpenNote)
=============
![][responsive]
In a post 9/11 world of mass digital survailence, there is only one way to keep your digital information safe.
In the United States, you do not have have 5th amendment rights if you entrust you information to a third party.

The fix is to take personal responsibility and host applications yourself.

OpenNote was built to be a open source(MIT License), web based note taking software.
It is designed to be self hosted and gives you ownership of your data.

Please support this project by:
- [Using GitTip][GitTip], 
- [donating bitcoins][Bitcoins], 
- and/or like on [Alternative To][Alternative].

Thank you!

[Download using Docker][Docker]

[or download manually from here.][Download]


Demo
-------
http://stardrive.us/OpenNote/


![][topLevel]
Features
--------
- Full WYSIWYG editor
- Touch friendly and mouse friendly ui
- Upload manager (not enabled in demo :) )
- Light weight
- Multi user support
- Note History ***(Revisions are currently being stored. However, there is not a view to see the revision tree)
- Search
- PDO Connector/(MySql and SQLite Database Support)
- Move Folders(Drag into another folder in the list view.)
- Rename/Delete Folders(Click on folder title to get menu.)
- Responsive

Upcoming Features
-----------------
- Tags (You win)
- Email to note
- Implement history viewer
- Install script
- Move Notes (Feature lost when migrating to Angular based list)
- Mobile App

User Wish List
--------------
List of things users are wishing for that have not made it into the pipeline.
Please do not re-submit issues for these features. Instead, how about a donation with the feature in the comment?

- Out of box PostgreSQL support. PDO connector support PostgreSQL.

Documentation
-----------------
[How to install][Install]

[How to upgrade][Upgrade]

[How to build][Build]

[Themes][Themes]

[PHP backend][php]


![][dark]
License
-------
	JQuery - Distributed under the MIT License
	Angular - Distributed under the MIT License
	Bootstrap - Distributed under the MIT License
	CKEditor - Distributed under the MPL License
	Angular UI Tree - Distributed under the MIT License
	Alertify.js - Distributed under the MIT License

	OpenNote Code - Distributed under the MIT License
	
	© Jacob Liscom 2014
	
Credits
-------
	J. Liscom - Supreme Programmer

	Kam Bnkamalesh - His TODO project heavily influenced my UI design

[topLevel]: https://raw.github.com/FoxUSA/OpenNote/master/Doc/screenShots/topLevel.png
[dark]: https://raw.github.com/FoxUSA/OpenNote/master/Doc/screenShots/dark1.png 
[responsive]: https://raw.githubusercontent.com/FoxUSA/OpenNote/master/Doc/screenShots/OpenNote.png

[Install]: https://github.com/FoxUSA/OpenNote/blob/master/Doc/Install.md
[Upgrade]: https://github.com/FoxUSA/OpenNote/blob/master/Doc/Upgrade.md
[Build]: https://github.com/FoxUSA/OpenNote/blob/master/Doc/Build.md
[PHP]: https://github.com/FoxUSA/OpenNoteService-PHP
[Dependencies]: https://github.com/FoxUSA/OpenNote/blob/master/Doc/Dependencies.md
[Themes]: https://github.com/FoxUSA/OpenNote/blob/master/Doc/Themes.md
[GitTip]: https://www.gittip.com/FoxUSA/
[Bitcoins]: http://blockchain.info/address/15Q2jhnTvxDQm4LvTku68vTzU8j8dcLnLB
[Alternative]: http://alternativeto.net/software/opennote/
[Download]: https://github.com/FoxUSA/OpenNote/releases
[Docker]: https://registry.hub.docker.com/u/foxusa/opennote/
