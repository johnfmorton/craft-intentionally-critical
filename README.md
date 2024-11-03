# Intentionally Critical

A plugin with an intentionally critical update for testing purposes. 

## Usage

This plugin does nothing except allow you to test scenarios that involve having a plugin that requires a critical update. It is intended to be installed at version 5.0.0 in a Craft project to trigger the critical update warning in the Craft Control Panel updates section. 

Installing version 5.0.1 of this plugin will resolve the critical update warning.

## Requirements

This plugin requires Craft CMS 5.4.0 or later, and PHP 8.2 or later.

## Installation

You can install this plugin from the Plugin Store or with Composer.

#### From the Plugin Store

Go to the Plugin Store in your project’s Control Panel and search for “Intentionally Critical”. Then press “Install”.

#### With Composer

Open your terminal and run the following commands:

```bash
# go to the project directory
cd /path/to/my-project.test

# tell Composer to load the plugin at verion 1.0.0, the version that will trigger the critical warning
composer require johnfmorton/craft-intentionally-critical:5.0.0

If you install the plugin without specifying a version, Composer will install the latest version of the plugin, which will not trigger the critical warning, which is the point of this plugin.

# tell Craft to install the plugin
./craft plugin/install intentionally-critical
```
