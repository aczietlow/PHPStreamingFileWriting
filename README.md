# Streamys

This is a sandbox for smoke testing streaming csv and zip files to an end user without saving the file on the server.

## Docksal

Docksal configuration is included in the .docksal directory.

### Requirements

------------
* [docksal](http://docksal.readthedocs.io/en/master/getting-started/env-setup/) >= 1.6
* (OSX & Windows)[virtualBox](https://www.virtualbox.org/wiki/Downloads) >= 5.1.x

## Getting Started

------------------

1. From inside the project root, run `fin init`
2. Enter your password when prompted
3. Visit `http://streamys.docksal/` in your browser of choice.

## How do I work on this?

------------------

1. Navigate to http://streamys.docksal/
2. From inside the project root `fin` to see a list of available commands
   - `fin drush`
3. fin acts as a wrapper to pass commands to the various running servers,
so there's no need to log into the VM

### Code Structure
The web root lives within the /web directory.  It contains a full Drupal
installation that gets deployed to various hosting platforms to power dev,
test, staging, live, and multidev websites.

### Module Layout
* modules/contrib -- Contrib modules from d.o
* modules/custom -- Custom modules developed for the project
