# Flutter 3.13.0 icon font codepoint crash

A sample project to reproduce a crash when building an app using a custom font package.

* Use Flutter 3.13.0
* Run `flutter build web --release --web-renderer canvaskit`

The build will fail with an error:

```
Codepoint 32 not found in font, aborting.

Target web_release_bundle failed: IconTreeShakerException: Font subsetting failed with exit code 255.

```
