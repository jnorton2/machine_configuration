# Mac Setup
This is the configuration of programs and settings I use on a Mac machine for work and productivity. 

## Productivity
| **Program**                                             | **Description**               | **Download Link**                                              | **Paid/Free** |
| ------------------------------------------------------- | ----------------------------- | -------------------------------------------------------------- | ------------- |
| FlyCut                                                  | Clipboard manager             | https://github.com/TermiT/Flycut                               | Free          |
| Spectacle                                               | Windowing management          | https://www.spectacleapp.com/                                  | Free          |
| Alfred                                                  | Spotlight Replacement         | https://www.alfredapp.com/                                     | Free          |
| Homebrew                                                | Package installer             | https://brew.sh/                                               | Free          |
| Steel Series Exact Mouse | Mouse Acceleration Killer | https://downloads.steelseriescdn.com/drivers/tools/steelseries-exactmouse-tool.dmg | Free |

## Essentials
| **Program**                                             | **Description**               | **Download Link**                                              | **Paid/Free** |
| ------------------------------------------------------- | ----------------------------- | -------------------------------------------------------------- | ------------- |
| Chrome                                                  | Web Browser                   | https://www.google.com/chrome/                                 | Free          |
| Dropbox                                                 | Cloud File storage            | https://www.dropbox.com/install                                | Paid          |
| Spotify                                                 | Music Stream                  | https://www.spotify.com/us/download                            | Paid          |


## Development
| **Program**                                             | **Description**               | **Download Link**                                              | **Paid/Free** |
| ------------------------------------------------------- | ----------------------------- | -------------------------------------------------------------- | ------------- |
| Jetbrains Suite <br><br>PyCharm<br>IntelliJ<br>Webstorm | IDEs                          | https://www.jetbrains.com/toolbox-app/                         | Paid          |
| Illuminated Cloud IntelliJ Plugin                       | Salesforce Development Plugin | http://www.illuminatedcloud.com/                               | Paid          |
| Source Tree                                             | Git GUI                       | https://www.sourcetreeapp.com/                                 | Free          |
| Sequel Pro                                              | Database GUI                  | https://www.sequelpro.com/                                     | Free          |
| MYSQL Workbench                                         | Database GUI                   | https://www.mysql.com/products/workbench                      | Free          |
| Sublime Text                                            | Text Editor                   | https://www.sublimetext.com/3                                  | Free          |

## Communication
| **Program**                                             | **Description**               | **Download Link**                                              | **Paid/Free** |
| ------------------------------------------------------- | ----------------------------- | -------------------------------------------------------------- | ------------- |
| Slack                                                   | Messaging                     | https://slack.com/downloads                                    | Paid          |
| Teams                                                   | Thermofisher Messaging        | https://products.office.com/en-us/microsoft-teams/download-app | Free          |

## Network
| **Program**                                             | **Description**               | **Download Link**                                              | **Paid/Free** |
| ------------------------------------------------------- | ----------------------------- | -------------------------------------------------------------- | ------------- |
| Pulse Secure                                            | VPN                           | https://www.pulsesecure.net/                                   | Paid          |


## Scripts

**CPU throttle for Controlling Dropbox**  

Use with `cputhrottle {pid} {percentage_to_throttle} &`  

https://www.dropbox.com/s/llusdnyp23q2dhq/cputhrottle?dl=0  

   pid: process ID. Alternatively you could use `$(pgrep -f ProgramYouWishToGrepFor)` to find the process ID dynamically.  

   percentage_to_throttle: An integer to state what percentatge to throttle by.  

   Example:  

   Throttle Process 2010 to 20% `cputhrottle 2010 20 &`  

   Throttle Dropbox to 70%: `cputhrottle $(pgrep -f Dropbox) 70 &`  



## OSX Setting Changes

1. Reverse the Scroll settings for the trackpad

   Preferences -> Trackpad -> Uncheck Scroll direction: Natural
2. Show the percentage in the battery bar

   Click the battery icon -> Show Percentage
3. Change the touchbar to include Lockscreen, Brightness and Sound

   Perferences -> Keyboard -> Customize Control Bar
   
   
## Other Settings   

Remove Hardware Media Key handling from Chrome: chrome://flags/#hardware-media-key-handling
