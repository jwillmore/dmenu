# dmenu
My build of Suckless' dmenu

Current patches:
  - **line-height:** Allows to specify the height of the menu.
  - **numbers:** Adds text which displays the number of matched and total items in the top right corner of dmenu.
  - **case insensitive:** This patch changes case-insensitive item matching to default behaviour.
  - **password:** Adds a password mode for dmenu, that hides the user inpur.

Installation
--------------
In order to build dmenu you need the Xlib header files and the base-devel packages.
``` 
git clone https://github.com/jwillmore/dmenu.git
cd dmenu
sudo make clean install
```
