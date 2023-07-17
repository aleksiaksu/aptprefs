Preference block lists for the Apt package manager, for Debian 11 or newer.

If you use block-browsers.pref, it helps if you want to install a newer version of your favorite browser from Flathub or something similar. 

However `block-thunar.pref` and `block-xfce4.pref` may cause issues.

To install this project, use:
```
git clone https://github.com/aleksiaksu/aptprefs.git ~/aptprefs
cd ~/aptprefs/debian
sudo cp *.pref /etc/apt/preferences.d
```
