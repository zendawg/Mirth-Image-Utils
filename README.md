Mirth-Image-Utils
=================

Support for image processing (such as scaling and sub-images), used by the service bus.

It is expected that Mirth has already been installed prior to installing these utilities.

The image utilities are created as part of the Mirth ESB installation process; this can be done separately, by installing Java, Maven, and then compiling the sources and copying them to the Mirth library directory.

Once the `OpenEyes-Install-Scripts` have been obtained, Java can be installed by calling

	sh esb/mirth/mirth-install.sh -j

Next, Apache Maven can be installed:

	sh esb/mirth/mirth-install.sh -m

Finally, both image and encode utilities can be installed by calling

	sh esb/mirth/mirth-install.sh -s

This can be combined in one command by calling

	sh esb/mirth/mirth-install.sh -j -m -s
