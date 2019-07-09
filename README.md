# deZoom

This is a Mac app and shell script for removing the Zoom video conferencing app from your Mac and disabling the vulnerabilities it leaves behind, [as detailed in this blog post](https://medium.com/@jonathan.leitschuh/zoom-zero-day-4-million-webcams-maybe-an-rce-just-get-them-to-visit-your-website-ac75c83f4ef5). The Mac app is just the shell script bundled into an app using [Platypus](https://sveinbjorn.org/platypus) for ease of use.

[Click here to download the deZoom App](https://github.com/ryanfb/deZoom/releases/download/v1.0/deZoom.zip)

If this project helped you, feel free to [donate here](https://ryanfb.github.io/etc/tip-jar).

## Usage

You can either run the app (in order to bypass Mac app signing, you may need to right/two-finger click the app, hold command, then select "Open" and confirm that you want to run the app), or clone this repository and run `./dezoom.sh` if you're comfortable with the command line.

![A screenshot of the deZoom app running](screenshot.png?raw=true "A screenshot of the deZoom app running")

**WARNING:** This will disable Zoom video conferencing by default, delete the Zoom app, kill all Zoom processes, remove Zoom directories, and prevent their recreation. This is the course of action recommended in the vulnerability disclosure. I am not responsible for any data loss or problems that may occur (see below).

## LICENSE

Copyright 2019 Ryan Baumann

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
