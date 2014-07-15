# node-decaptcher

Package that comes with node.js class and command line utility.

## What it does
Wraps a deCAPTCHA library (currently only `deathbycaptcha`) and exposes a simple interface of:
 1. `solve()` - solves CAPTCHA
 1. `report()` - reports wrong CAPTCHA

The command line utility (`run.js`) is an app that accepts an CAPTCHA image as a stream and returns the text on the image.