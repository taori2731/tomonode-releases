# Third-party notices

TomoNode's proprietary license does not change the licenses or source-access
rights of the third-party components listed here. Previously Apache-licensed
TomoNode material retains its prior permissions; the original license text is
preserved in `licenses/Apache-2.0.txt`.

## SteamCMD and Palworld Dedicated Server

SteamCMD and Palworld Dedicated Server are not bundled with TomoNode. When the user explicitly creates a Palworld server, the app downloads SteamCMD from Valve's fixed official HTTPS distribution URL and uses anonymous Steam App `2394010` installation. The downloaded software remains subject to its publishers' terms and licenses.

Steam and SteamCMD are trademarks or registered trademarks of Valve Corporation. Palworld is a trademark of Pocketpair, Inc. TomoNode is an independent project and is not an official product of, endorsed by, sponsored by, or affiliated with Minecraft, Mojang Studios, Microsoft, Palworld, Pocketpair, or Valve.

## MPL-2.0 dependencies

The Windows x64 application and Developer Tools use dependencies that declare the Mozilla Public License 2.0, including `selectors`, `cssparser`, `cssparser-macros`, `dtoa-short`, `attohttpc`, `option-ext`, and the Windows-compatible `lightningcss` packages. The exact applicable package list is generated from the current lockfiles by Developer Tools.

The complete canonical MPL-2.0 text is bundled as `licenses/MPL-2.0.txt`. Official source: https://www.mozilla.org/MPL/2.0/

Recipients can obtain the unmodified MPL-covered source for the current Windows
lockfiles at the following public locations. These components remain available
under MPL-2.0, not TomoNode's proprietary license. On crates.io, use Download to
obtain the corresponding source archive.

| Component | Version | Source |
| --- | --- | --- |
| attohttpc (main app) | 0.30.1 | https://crates.io/crates/attohttpc/0.30.1 |
| cssparser | 0.36.0 | https://crates.io/crates/cssparser/0.36.0 |
| cssparser-macros | 0.6.1 | https://crates.io/crates/cssparser-macros/0.6.1 |
| dtoa-short | 0.3.5 | https://crates.io/crates/dtoa-short/0.3.5 |
| option-ext | 0.2.0 | https://crates.io/crates/option-ext/0.2.0 |
| selectors | 0.36.1 | https://crates.io/crates/selectors/0.36.1 |
| lightningcss / lightningcss-win32-x64-msvc | 1.33.0 | https://github.com/parcel-bundler/lightningcss/tree/v1.33.0 |

Update this table when the applicable locked versions change. If a covered file
is modified, its corresponding modified source must also be made available
under MPL before distributing that build.

The `selectors 0.36.1` crate archive declares `MPL-2.0` and contains the standard MPL 2.0 source header, but its published crate archive does not contain a standalone license file. Developer Tools records the verified source header and pairs it with the bundled canonical text instead of silently treating the missing file as complete.

## playit.gg agent / playit-ipc 1.0.10

Source: https://github.com/playit-cloud/playit-agent/tree/v1.0.10

The signed Windows agent is not bundled with TomoNode. After explicit confirmation, it can be downloaded from the official v1.0.10 GitHub Release and installed under its own license and service configuration.

Copyright 2022 Developed Methods LLC

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
