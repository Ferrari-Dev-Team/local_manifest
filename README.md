Ferrari Development Team
===========

Submitting Patches
------------------
Patches are always welcome!  

    Fork the project you wanted to submit a patch on, upload your patch, and make a pull request on the base project.

Make your changes and commit with a detailed message, starting with what you are working with (i.e. vision: Update Kernel)
Commit your patches in a single commit. Squash multiple commit using this command: git rebase -i HEAD~<# of commits>


Getting Started
---------------

To get started on building a rom for the Xiaomi Mi4i (ferrari), you'll need to get
familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository using the CyanogenMod trees, use a command like this:
(For other roms, please follow their own trees)

    repo init -u git://github.com/CyanogenMod/android.git -b cm-13.0

Then to to get the local manifests

    Download the local_manifest.xml file and move it to *YOUR ROM DIRECTORY*/.repo/local_manifest

Please see the [CyanogenMod Wiki](http://wiki.cyanogenmod.org/) for building instructions.
