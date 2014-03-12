Arduino Data Logging Abstraction Project
========================================

The goal of this project is to have a robust Arduino system with different, abstracted plugin sensors (such as a Temperature sensor, Geiger counter, etc.) that can easily be switched out and logged onto an SD card.  We will be using an Arduino with a built-in GPS sensor and an SD card reader/writer (for exact schematics see <a href="http://www.adafruit.com/products/98">this store page</a>).

We are using <a href="inotool.org">ino</a> to compile.  Use the following command to compile the project (assuming you are currently located at the root git folder):

```
cd ino-project
ino build
```
