#AstroJournal
###Astronomy Journal for Wordpress

A plugin for keeping an astronomical observation journal.

####**Features**
AstroJournal will keep track of 
- Equipment
- Locations
- Observation date / time
- Observing conditions logging
- Object types
- Constellations

####**Installation**
1. Download, unzip, add _astrojournal_ folder to Wordpress _plugins_ folder
2. Activate under *Plugins*
3. At the top of astrojournal.php is the settings:
-- $show_astrojournal_on_frontpage = true

AstroJournal should automagically refresh the permalinks, but if you get a 404 message when trying to display your AstroJournal posts you can refresh them manually by going to *Settings->Permalinks* and just clicking _save_. If that doesn't work please [post an issue](https://github.com/plaidmelon/AstroJournal/issues) on GitHub.

####**Environment**
Tested on:
- Wordpress 4.7.2
- PHP 5.4
- MySQL 5.5

####**Utilizes**
[jQuery](https://jquery.com) and [jQueryUI](https://jqueryui.com)

[jQuery-Timepicker-Addon](https://github.com/trentrichardson/jQuery-Timepicker-Addon)

Required files are already included, links are here for reference.

####**History**
2/24/17 - First release 0.9
- Basic funtionality

3/04/17 - Release 1.0
- OOP design
- Metadata improvements
- added jQuery picker