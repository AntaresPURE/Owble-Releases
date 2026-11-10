# Third-party notices

Owble is proprietary software (see `LICENSE`). It includes the following third-party
components, which are distributed under their own licenses. The license texts are
reproduced below or, where they are long, as files in the folder `licenses` next to this
file. Nothing in the license of Owble restricts the rights that these licenses give you
for the components themselves.

| Component | Used for | License |
|---|---|---|
| .NET runtime (included in the self-contained build) | application platform | MIT |
| [CommunityToolkit.Mvvm](https://github.com/CommunityToolkit/dotnet) | MVVM infrastructure | MIT |
| Microsoft.Extensions.DependencyInjection.Abstractions, Microsoft.Extensions.Logging.Abstractions, [Microsoft.IO.RecyclableMemoryStream](https://github.com/microsoft/Microsoft.IO.RecyclableMemoryStream), System.Security.Cryptography.ProtectedData (dependencies of Avalonia and the app) | infrastructure, protecting saved secrets on Windows | MIT |
| [NAudio](https://github.com/naudio/NAudio) (NAudio.Core, NAudio.Wasapi) | mixing; audio input and output on Windows (WASAPI) | MIT |
| [System.Numerics.Tensors](https://github.com/dotnet/runtime) | dependency of NAudio | MIT |
| [Concentus](https://github.com/lostromb/concentus) (including the Opus reference library) | Opus voice codec | BSD-style (Opus license) |
| [Google.Protobuf](https://github.com/protocolbuffers/protobuf) | protocol serialization | BSD-3-Clause |
| [RNNoise](https://gitlab.xiph.org/xiph/rnnoise) | noise suppression (macOS: built from the release 0.2 when packaging, `librnnoise.dylib`) | BSD-3-Clause |
| [RNNoise.NET](https://github.com/Yellow-Dog-Man/RNNoise.Net) (YellowDogMan.RRNoise.NET) | packaging of RNNoise | MIT |
| [Mumble](https://github.com/mumble-voip/mumble) protocol definitions (`Mumble.proto`, `MumbleUDP.proto`, excerpts) | Mumble protocol | BSD-3-Clause |
| [Avalonia](https://github.com/AvaloniaUI/Avalonia) (Avalonia, Avalonia.Desktop, Themes.Fluent, Fonts.Inter, Avalonia.Skia and the platform packages), MicroCom.Runtime, Tmds.DBus.Protocol | cross-platform user interface | MIT |
| [ANGLE](https://github.com/google/angle) (`av_libglesv2.dll` from Avalonia.Angle.Windows.Natives) | graphics on Windows | BSD-3-Clause (`licenses/ANGLE-Avalonia-LICENSE.txt`) |
| [Inter](https://github.com/rsms/inter) font (Avalonia.Fonts.Inter) | user interface font | SIL Open Font License 1.1 (`licenses/Inter-OFL-1.1.txt`) |
| [SkiaSharp](https://github.com/mono/SkiaSharp) and [HarfBuzzSharp](https://github.com/mono/SkiaSharp) with their native libraries (they contain Skia, HarfBuzz, FreeType, libpng, zlib and others) | drawing, text, image decoding, scaling and encoding | MIT; the native parts under the licenses in `licenses/SkiaSharp-HarfBuzzSharp-THIRD-PARTY-NOTICES.txt` |
| [PortAudio](https://github.com/PortAudio/portaudio) | audio input and output on macOS and Linux | MIT |
| [PortAudioSharp2](https://github.com/csukuangfj/PortAudioSharp2) and the packages org.k2fsa.portaudio.runtime.* | .NET binding and builds of PortAudio | Apache License 2.0 (`licenses/Apache-2.0.txt`) |
| [SharpHook](https://github.com/TolikPylypchuk/SharpHook) | .NET binding for the system-wide push-to-talk key | MIT |
| [libuiohook](https://github.com/TolikPylypchuk/libuiohook) (fork used by SharpHook) | system-wide keyboard and mouse hook | **LGPL-3.0** (`licenses/LGPL-3.0.txt`, `licenses/GPL-3.0.txt`), see the section on libuiohook below |
| [Material Icons](https://github.com/google/material-design-icons) font | icons (`Owble/Assets/Fonts/MaterialIcons-Regular.ttf`) | Apache License 2.0 (`licenses/Apache-2.0.txt`) |

Build tools that do not become part of the program (Grpc.Tools, Microsoft.CodeAnalysis.ResxSourceGenerator,
test frameworks, the Avalonia developer tools of debug builds) are used under their own licenses and are not redistributed.

---

## MIT License

Applies to the components marked "MIT" above, with these copyright notices:

- .NET runtime, WPF, Windows Forms, System.Numerics.Tensors: Copyright (c) .NET Foundation and Contributors
- CommunityToolkit.Mvvm: Copyright (c) .NET Foundation and Contributors
- Avalonia: Copyright (c) AvaloniaUI OÜ and contributors
- SkiaSharp: Copyright (c) 2015-2016 Xamarin, Inc.; (c) 2017-2018 Microsoft Corporation
- PortAudio: Copyright (c) 1999-2011 Ross Bencina and Phil Burk
- SharpHook: Copyright (c) Tolik Pylypchuk
- NAudio: Copyright (c) Mark Heath
- RNNoise.NET: Copyright (c) 2023 Yellow Dog Man Studios s.r.o.
- HarfBuzzSharp: Copyright (c) 2015-2016 Xamarin, Inc.; (c) 2017-2018 Microsoft Corporation
- Microsoft.Extensions.*, Microsoft.IO.RecyclableMemoryStream, System.Security.Cryptography.ProtectedData: Copyright (c) Microsoft Corporation and the .NET Foundation
- MicroCom.Runtime: Copyright (c) AvaloniaUI OÃœ and contributors
- Tmds.DBus.Protocol: Copyright (c) Tom Deseyn and contributors

The .NET runtime additionally contains components listed in its own third-party notices:
https://github.com/dotnet/runtime/blob/main/THIRD-PARTY-NOTICES.TXT

```
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## BSD-3-Clause License

Applies to the components marked "BSD-3-Clause" above, with these copyright notices:

- Google.Protobuf: Copyright 2008 Google Inc. All rights reserved.
- RNNoise: Copyright (c) 2017, Mozilla; Copyright (c) 2007-2017, Jean-Marc Valin;
  Copyright (c) 2005-2017, Xiph.Org Foundation; Copyright (c) 2003-2004, Mark Borgerding
- Mumble protocol definitions: Copyright (C) The Mumble Developers

```
Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this
   list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice,
   this list of conditions and the following disclaimer in the documentation
   and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its
   contributors may be used to endorse or promote products derived from
   this software without specific prior written permission.

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
```

---

## Concentus and Opus

Concentus contains a C# port of the Opus codec and independently compiled versions of the
Opus reference library (https://gitlab.xiph.org/xiph/opus), distributed under these terms:

```
Copyright (c) by various holding parties, including (but not limited to):
Skype Limited, Xiph.Org Foundation, CSIRO, Microsoft Corporation,
Jean-Marc Valin, Gregory Maxwell, Mark Borgerding, Timothy B. Terriberry,
Logan Stromberg. All rights are reserved by their respective holders.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice, this
  list of conditions and the following disclaimer.

* Redistributions in binary form must reproduce the above copyright notice,
  this list of conditions and the following disclaimer in the documentation
  and/or other materials provided with the distribution.

* Neither the name of Internet Society, IETF or IETF Trust, nor the
   names of specific contributors, may be used to endorse or promote
   products derived from this software without specific prior written
   permission.

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
```

---

## Apache License 2.0

Applies to the components marked "Apache License 2.0" above. The full text is in `licenses/Apache-2.0.txt`.

- Material Icons: Copyright Google LLC
- PortAudioSharp2 and org.k2fsa.portaudio.runtime.*: Copyright the PortAudioSharp2 authors (csukuangfj, k2-fsa), https://github.com/csukuangfj/PortAudioSharp2

---

## SIL Open Font License 1.1 (Inter)

The user interface font Inter is licensed under the SIL Open Font License, Version 1.1. The font is
used unchanged and is not sold on its own. The full text with the copyright notice is in
`licenses/Inter-OFL-1.1.txt`.

Copyright (c) 2016 The Inter Project Authors (https://github.com/rsms/inter)

---

## Native libraries of SkiaSharp and HarfBuzzSharp, ANGLE

The native libraries `libSkiaSharp` and `libHarfBuzzSharp` contain third-party code (Skia, HarfBuzz,
FreeType, libpng, zlib, ANGLE and others) under the licenses reproduced in
`licenses/SkiaSharp-HarfBuzzSharp-THIRD-PARTY-NOTICES.txt` (copied unchanged from the NuGet packages).
`av_libglesv2.dll` (ANGLE, Windows) comes from the package Avalonia.Angle.Windows.Natives; its license is
in `licenses/ANGLE-Avalonia-LICENSE.txt`.

---

## libuiohook (LGPL-3.0)

Owble uses the library libuiohook, through the .NET binding SharpHook (MIT), to recognise the push-to-talk
key and mouse button while Owble is in the background.

libuiohook: Copyright (C) 2006-2023 Alexander Barker and contributors. It is free software under the
GNU Lesser General Public License, version 3 (`licenses/LGPL-3.0.txt`), which refers to the GNU General
Public License, version 3 (`licenses/GPL-3.0.txt`). Owble comes with no warranty from the authors of libuiohook.

- **Used version:** the fork https://github.com/TolikPylypchuk/libuiohook at commit
  `3890543a1aa09f20966b1784650487093daad97e` (the version SharpHook 8.0.1 is built with). Its source code
  is available there: https://github.com/TolikPylypchuk/libuiohook/tree/3890543a1aa09f20966b1784650487093daad97e
- **Not linked statically:** libuiohook is a separate dynamic library next to the program
  (`uiohook.dll` on Windows, `libuiohook.dylib` on macOS, `libuiohook*.so` on Linux). Owble loads it at
  runtime and contains no code of it.
- **Replacing it:** you may replace this library with your own modified build of the same interface
  (stop Owble, replace the file in the program folder, start Owble). Nothing in the license of Owble
  prohibits this, nor reverse engineering for debugging such modifications.
