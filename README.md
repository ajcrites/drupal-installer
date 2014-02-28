# Drupal Installer

This is a simple shell command that will:
* install Drupal to the provided document root
* create a functional server entry to run the site either
 as subdomain
* ensure that the necessary services are running; install
 if needed/possible

The installer takes three arguments, but if some are
not provided you will be prompted for them:

1. Name of the subdomain to run on locally
2. Version of Drupal to install
3. Document root: where the drupal code should live

After completing the installation, The installer will
open your brand new awesome Drupal installation in Chrome.

## Requirements
In order to make everything to smoothly, you should already
have PHP, MySQL, and Apache installed and running.

## TODO
Need to develop for OS X as well, which has very different
mechanisms for starting/stopping services

Also need to allow for more options:
* Subdomain name
 * Port alternative
* Document root path
* Drupal version (with default)
 * Need to find a way to get *latest*, if possible

Compatibility with MAMP?
