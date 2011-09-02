**Update**: You shouldn't need this patched version if you're running Xcode 4.1 or above. See [this post](http://twobitlabs.com/2011/09/symbolicating-fixed-in-xcode-4-1/) for more information on troubleshooting Xcode 4.1.

iOS crash report symbolication is broken in Xcode 4.0 with archived builds. Read more at [http://twobitlabs.com/blog/2011/04/cant-symbolicate-xcode4-archive-builds/](http://twobitlabs.com/blog/2011/04/cant-symbolicate-xcode4-archive-builds/)

To fix your iOS crash report symbolication, move /usr/local/bin/symbolicatecrash aside and copy in the version in this repo.

Filed as rdar://problem/9241304
