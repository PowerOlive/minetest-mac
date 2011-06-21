# Xcode project to build minetest

This Xcode project can be used to build [minetest-c55](https://bitbucket.org/celeron55/minetest).

## Requirements

This was tested on OS X 10.6 with Xcode 3. It includes all needed 3rd party libraries.
It builds a 32bit 10.5 compatible application bundle.

## How to build minetest

### Getting the code

	$ mkdir ~/code && cd ~/code
	$ hg clone ssh://hg@bitbucket.org/celeron55/minetest
	$ cd minetest
	$ git clone https://github.com/toabi/minetest-mac.git
	$ cd minetest-mac

There are now two easy ways to get your app. The final product always ends up in ./build/(Release|Debug)/.

### Commandline

* Run `xcodebuild` in the minetest-mac folder

### Xcode GUI

* Doubleclick the .xcodeproj
* Hit "Build & Run"
* If everything is OK, the application should launch.

## Credits

I'm distributing the binary Irrlicht framework release from this [thread](http://irrlicht.sourceforge.net/phpBB2/viewtopic.php?t=42601).
