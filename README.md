# Examples of map add-ins

This project contains a few simple examples of add-ins that can be opened in right panel on the map or trips history page. Each of these add-ins shows how geotab services are work.

1) **events** - shows how to subscribe to different events from map `services.events`;
2) **tooltip** - shows to show additional information in map tooltips or show your own tooltip `services.tooltip`;
3) **action** - shows how to add a custom button in different map action list `services.actionList`;
4) **localStorage** - shows how to set/get/remove items from local storage `services.localStorage`;
5) **request** - shows how to request Geotab data from server `services.api`;
6) **page** - shows how to change page state and handle state changes that happens on the page `services.page`;
7) **mapElements** - shows how to draw different elements on the map and catch events from them `services.canvas`;
8) **map** - shows how to control map view and catch events from it `services.map`.

To try it you show:

1) Create `.zip` archive from a folder (for Mac and Linux users it can be done with one command: `zip -r addin.zip {{addinFolder}}`)
2) Add it as usual add-in on the system settings page*.
> It works only in FB/295585 branch or in master if it's merged.

If you want to try it on tripsHistory page just change a page name in `configuration.json` file: from `"page": "map"` to `"page": "tripsHistory"`.

If you want to build all add-ins to test them, just run `./build.sh` command and get any `zip` file from `./dist` folder.# mapElements
