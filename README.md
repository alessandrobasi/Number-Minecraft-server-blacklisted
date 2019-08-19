# Number-Minecraft-server-blacklisted
Dynamic image for counting the number of Minecraft server blacklisted by Mojang

# Installation
Put the font (Arial) and the php file (index.php) in a folder of web server and go to the file index.php

# Database structure
| Name  | Type |
| ------------- | ------------- |
| id  | int auto increment  |
| date  | text 255  |
| number  | int  |

```
CREATE TABLE IF NOT EXISTS `minecraft_blacklist` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `date` text NOT NULL,
  `number` int(11) NOT NULL,
  PRIMARY KEY (`id`)
) ENGINE=MyISAM  DEFAULT CHARSET=latin1 AUTO_INCREMENT=1 ;
```
