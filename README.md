![Symbol Instance Locator](https://raw.githubusercontent.com/sonburn/symbol-instance-locator/master/images/logo.png)

Locate all instances of a selected symbol or instance. Select an instance in the list of results to jump to it's location.

![Symbol Instance Locator](https://raw.githubusercontent.com/sonburn/symbol-instance-locator/master/images/screenshot.png)

<a href="http://bit.ly/SketchRunnerWebsite">
	<img width="160" height="41" src="http://bit.ly/RunnerBadgeBlue" alt="runner-badge-blue">
</a>

<a href="https://www.paypal.me/sonburn">
	<img width="160" height="41" src="https://raw.githubusercontent.com/sonburn/symbol-organizer/master/images/donate.png">
</a>

# Usage

* cmd option shift l - Locate all instances of the selected symbol or instance

# Installation

## Automatic
Search for Symbol Instance Locator in [Sketchrunner](http://sketchrunner.com/) or [Sketch Toolbox](http://sketchtoolbox.com/) if you have one of those installed.

Once installed, Sketch will automatically notify you when an update is available (version 0.2 and later).

## Manual

1. Download and open symbol-instance-locator-master.zip
2. Navigate to Symbol Instance Locator.sketchplugin and copy/move to your plugins directory

To find your plugins directory...

1. In the Sketch menu, navigate to Plugins > Manage Plugins...
2. Click the cog in the lower left of the plugins window, and click Reveal Plugins Folder

# Changelog

* **1.16** - Fix for non-modified overrides appearing as overrides for instance.
* **1.15** - Improvements to responsiveness, result accuracy, and better darkmode support. Fix for Sketch 72.
* **1.14** - If instance master is in library, 'Go to Master' will now open the library. Override instances now show each instance and overridden layer name.
* **1.13** - Fix for Sketch 53.
* **1.12** - Fix for "null is not an object (evaluating 'overrides.forEach')" issue.
* **1.11** - Updated method used to locate symbols used as overrides.
* **1.10** - General optimizations.
* **1.9** - Added plugin icon to manifest for Sketch 50.
* **1.8** - Fix for plugin not working in El Capitan and updated years.
* **1.7** - Fix for Sketch 48 change of currentView to contentDrawView.
* **1.6** - Improved handling when selection has overrides but no instances.
* **1.5** - Added support for overrides.
* **1.4** - Improved handling for long symbol master names, added button to select master (if it resides in current document).
* **1.3** - Added button to select all matches on current page, updated plugin screenshot.
* **1.2** - Update to make the result window a floating panel, highlight for current selection, and artboard name.
* **1.1** - Code optimizations and dialog frame will now be smaller if a small set of results are returned.
* **1.0** - Found instances now display image of the instance, page where the instance reside, and instance name.
* **0.3** - Converted list of instances to NSButtons, which when selected, will now navigate user to location of instance.
* **0.2** - Added appcast plugin support for Sketch 45 and later. Significantly improved processing time, and presentation of results.
* **0.1** - Initial commit. Functional, but rudimentary and will be improved upon.

# Contact

Find me on Twitter <a class="twitter-follow-button" href="https://twitter.com/sonburn">@sonburn</a>

# Support

If you find this plugin helpful, or would like to support my plugins in general, buy me ☕️ via <a href="https://www.paypal.me/sonburn">PayPal</a>.

# License

Copyright (c) 2021 Jason Burns (Sonburn). See LICENSE.md for further details.
