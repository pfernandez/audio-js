# Audio JS

Provides simplified recording, playback, and download functionality through the JavaScript Web Audio API. As of this writing, it is tested to work in the latest versions of Chromium and FireFox on Ubuntu Linux.Should also work in regular Chrome, Opera, and the mobile versions of each.

Loosely based on a demo at [http://webaudiodemos.appspot.com/AudioRecorder/index.html](http://webaudiodemos.appspot.com/AudioRecorder/index.html), and taking advantage of Matt Diamond's [Recorderjs](https://github.com/mattdiamond/Recorderjs) library.

Provides four functions:

    audio.record();
    audio.stop();
    audio.play();
    audio.download();

See `index.html` for simple usage.

This project is licensed under the terms of the MIT license.
