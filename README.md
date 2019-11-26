# What is this?

ChromeFox is a collection of Firefox customizations to emulate Google Chrome's UI.

# What does it do?

These configuration files will provide the following Chrome-like appearance and functionality changes: rounded tabs, bigger bookmark bar item padding, bookmark bar shown only on new tab, overlay scrollbars and other small fixes and tweaks.

![](https://raw.githubusercontent.com/ipproductions/ChromeFox/master/Screenshots/Captura%20de%20tela%20de%202019-03-16%2016-38-26.png)

# How do I install it?

Go to your Firefox profile folder (Help > Troubleshooting Info > Profile Directory) and place them inside your "chrome" folder (create a folder with that name if it's not already there).

For Firefox 70 and higher, please change the value : ```toolkit.legacyUserProfileCustomizations.stylesheets``` to true.

~~~
1. Load about:config in the Firefox address bar.
2. Confirm that you will be careful.
3. Search for toolkit.legacyUserProfileCustomizations.stylesheets using the search at the top.
4. Toggle the preference. True means Firefox supports the CSS files, False that it ignores them.
~~~
