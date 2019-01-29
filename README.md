# This Is Fine Plugin for Jenkins - RGY version

This plugin replaces all build status indicators with dogs and fires
inspired by the [This Is Fine meme](https://knowyourmeme.com/memes/this-is-fine).

This plugin was forked from the This Is Fine Plugin.

## Installing

1. Download the latest packaged plugin.
2. Install by going to `Jenkins->Manage Jenkins->Manage Plugins->Advanced`. Upload
the `.hpi` file under "Upload Plugin". Make sure to restart Jenkins for changes
to take effect.

## Building

To build the plugin from source: `mvn package`. On success the `.hpi` will be
output to `target/thisisfin.hpi`.

## Preview

This is what your Jenkins will look like with the plugin:

![screenshot](https://raw.githubusercontent.com/llbit/thisisfine-plugin/master/thisisfine.png)

* Happy dog = success.
* Dog with fire in the background = test failures.
* Only fire = build failed.
* Gray dog = not built.
