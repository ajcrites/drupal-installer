# Drupal Installer

This is a simple shell command that will:
* install Drupal to the provided document root
 * defaults to the current directory
* create a functional server entry to run the site either as
 * subdomain
 * port
* document root
* ensure that the necessary services are running; install
 if needed/possible
* ensure that all required PHP modules are installed/enabled

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
