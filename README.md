Gerrit webhooks
===============

Overview
--------
Set of gerrit hooks that will fire webhooks to your URLs. Inspired by jerrit.

More info on hooks at:
http://gerrit.googlecode.com/svn/documentation/2.1.6/config-hooks.html

Requirements
------------
 - `requests` library

Installation Steps
-------------------
 - Install `requests`
 - Drop hook files into `$site_path/hooks`
 - Setup config file in the home folder for the user that runs gerrit: ~/.gerrit-webhook

Config file
------------
This plugin looks for a config file at ~/.gerrit-webhook
See `gerrit-webhook.example`
