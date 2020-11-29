# SYNCYDINK IS NO LONGER MAINTAINED

This repo has been archived and neither it or the app will be updated anymore. If you would like to fork and create your own version, feel free. There's more info in [this github issue.](https://github.com/metafetish/syncydink/issues/85)

# SyncyDink

[![npm](https://img.shields.io/npm/v/syncydink.svg)](https://npmjs.com/package/syncydink) [![Patreon donate button](https://img.shields.io/badge/patreon-donate-yellow.svg)](https://www.patreon.com/qdot)

SyncyDink is (going to be) a web based video player and encoder (once we're done with it), using:

- [vue.js](http://vuejs.org) for frontend
- [video.js](http://videojs.com) for 2D movies
- [aframe](http://aframe.io) for 180SBS/360 Spherical movies

On top of these systems, Syncydink provides a way for users to load
haptics files to synchronize with movies. Supported haptics hardware
includes:

- [Fleshlight Launch](http://fleshlight.com/launch)
- [Lovense Toys](http://www.lovense.com)
- [Vorze A10 Cyclone](http://www.vorzeinteractive.com)
- XInput Gamepads
- Anything else [the Buttplug library](https://buttplug.io) for your platform might support

This hardware can be accessed via:

- WebBluetooth in Chrome on Linux, macOS, ChromeOS, and Android 6 or higher (All except gamepads)
- [buttplug-csharp](http://github.com/metafetish/buttplug-csharp) on Windows

Supported Haptic File Formats:

- [Funscript Format](https://godoc.org/github.com/funjack/launchcontrol/protocol/funscript) (json format)
- [Feelme Format](http://feelme.com) (json format)
- [VirtualRealPlayer Format](http://virtualrealporn.com) (ini format)
- [RealTouchScripter Format](http://realtouchscripts.com) (RealTouch format)

## Support The Project

If you find this project helpful, you can [support our projects via
Patreon](http://patreon.com/qdot)! Every donation helps us afford more
hardware to reverse, document, and write code for!

## License

Syncydink is BSD licensed.

    Copyright (c) 2017-2018, Nonpolynomial Labs LLC
    All rights reserved.
    
    Redistribution and use in source and binary forms, with or without
    modification, are permitted provided that the following conditions are met:
    
    * Redistributions of source code must retain the above copyright notice, this
      list of conditions and the following disclaimer.
    
    * Redistributions in binary form must reproduce the above copyright notice,
      this list of conditions and the following disclaimer in the documentation
      and/or other materials provided with the distribution.
    
    * Neither the name of the project nor the names of its
      contributors may be used to endorse or promote products derived
      from this software without specific prior written permission.
    
    THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
    AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
    IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
    DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
    FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
    DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
    SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
    CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
    OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
    OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
