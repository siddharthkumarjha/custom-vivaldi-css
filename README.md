# custom-vivaldi-css

👋 Hello everyone, I’m [@siddharthkumarjha](https://github.com/siddharthkumarjha)
A while back I created and uploaded a [Vivaldi theme](https://themes.vivaldi.net/themes/Qbnlj4pmJ2m) called Hogwarts!! 🏰
However, the regular updates keep messing with the perfect theme that I have and we can't have that now can we!!
So, I decided to create a custom CSS file that keeps combating ⚔️ with the constant updates and the breaking theme.

## How to use this custom CSS?

For those who don't know how to use custom CSS in vivaldi:

1. Download the ```main.css``` file from repo :octocat:
2. Create an empty folder and store the ```.css``` file there.
2. open vivaldi and type ```vivaldi://experiments/``` in the address field.
3. make sure the checkbox next to the option ```Allow using CSS modification``` is ticked, i.e., :ballot_box_with_check:.
4. next open vivaldi settings or if you can't find the settings icon type ```vivaldi://settings/``` in the URL bar.
5. once there go to ```Appearance``` &rarr; ```custom UI modifications``` and click ```select folder``` and select the folder :open_file_folder: where the css file is kept.
6. click OK and you are done you might need to reload ${\color{red}↻}$ the browser :globe_with_meridians: for the custom css to work.

## Suggestions for better user experience

I would recommend turning on device's dark mode and using the extensions like [```Dark Reader```](https://chrome.google.com/webstore/detail/dark-reader/eimadpbcbfnmbkopoojfekhnkhdbieeh) or turning on ```auto dark mode for webcontents``` in ```vivaldi://flags``` this will force all the webpages you view to be in dark mode.

### For arch users 

if want to force vivaldi to use dark mode go to ```~/.config``` and create a file called ```vivaldi-stable.conf``` and enter these lines:

~~~
--force-dark-mode 
--enable-features=WebUIDarkMode
~~~

and save.
