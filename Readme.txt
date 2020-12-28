FirefoxCSS+ is based on h4wwk3ye release (https://github.com/h4wwk3ye/firefoxCSS), MaterialFox (https://github.com/muckSponge/MaterialFox) 
and FlyingFox (https://github.com/akshat46/FlyingFox).

INSTALLATION:
- install "TreeStyleTab" addon;
- go to the addon's preferences and scroll until you find "Advanced settings", then import the .json file.
- do the same for a css section. Load the css file outside chrome;
- go to "about:profiles"
- open the root directory folder of your desidered profile (either the one you use or one you want to make);
- unzip the chrome folder in it;
- go to "about:config" into your urlbar and search for:
 	> "toolkit.legacyUserProfileCustomizations.stylesheets", then set its value to true;
	> "svg.context-properties.content.enabled", then set its value to true;
	> "layout.css.backdrop-filter.enabled", then set its value to true;
	