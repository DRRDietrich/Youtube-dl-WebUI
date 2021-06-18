# Youtube-dl WebUI

![Main](https://raw.githubusercontent.com/DRRDietrich/Youtube-dl-WebUI/master/img/de/main.png)
![List](https://raw.githubusercontent.com/DRRDietrich/Youtube-dl-WebUI/master/img/de/list.png)

## Description
Youtube-dl WebUI is a small web interface for youtube-dl. It allows you to host your own video downloader. After the download you can stream your videos from your web browser or save it on your computer directly from the list page.

## Requirements
- A web server (Apache or nginx)
- PHP latest version should be fine.
- [Youtube-dl](https://github.com/rg3/youtube-dl)

## How to install ?
1. Clone this repo in your web folder (ex: /var/www).
2. Edit config.php as you want it to work.
3. Create the video folder. 
4. Check permissions.
5. Access to your page (ex: index.php) to check that everything works.

## Set a password
1. Open config.php
2. Set security to 1
3. Find a password and hash it with md5 (you can do this with the md5.php page)

## CSS Theme
[Flatly](http://bootswatch.com/flatly/)

## License
GPL v2 see LICENSE.md
