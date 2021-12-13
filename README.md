<p align="center">
  <img width="300" height="75" src="Resources/logo.png">
</p>

# QuickMoodle

The goal of this project is to create a quick shortcut for macOS, to open and connect to a Moodle website in a single click, using *AppleScript*. In this code, I will use the [Moodle portal of ETH Zürich](https://moodle-app2.let.ethz.ch/auth/shibboleth/login.php). This shortcut may seem unnecessary, but logging into Moodle can take up to 9 clicks — even with credentials autofilling!

## Configuration
* Modify the `moodle_c.txt` file inside this `QuickMoodle` folder: write your username on the first line and your password on the second line. **Disclaimer: it is a bad security practice to write your password in plain text — do so at your own risk.**
* If you are using this script for another portal than ETH Zürich, you will have to change various parts of the `moodle.scpt` script.
* Move the folder `QuickMoodle` where you want to, for example `/Users/YOUR_USERNAME/Public/Drop Box`.
* Add the shortcut [by clicking this link](https://www.icloud.com/shortcuts/9e5f30ae080a486684eda357c70531b3) on your Mac. When prompted, provide the previously set path to the `QuickMoodle` folder.

You are now ready to go! To use this program, you can launch it from the Shortcuts icon in your Mac's menu bar, or you can define a keyboard shortcut in the Shortcuts application if you prefer.