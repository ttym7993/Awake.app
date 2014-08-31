Awake.app
=========

![screenshot](https://raw.github.com/xiaozi/Awake.app/master/screenshot.png)

An app for mac osx to prevent sleeping; inspired by Caffine.

1. left click to toggle "should sleep status"
2. right click for menu

"run at login" will not take effect unless you put this app in the `/Applications` directory.

### apple script supported

```applescript
tell application "Awake"
	turn on for 1
	-- turn off
end tell
```