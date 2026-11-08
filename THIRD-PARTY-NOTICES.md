# Third-party notices

Owble is proprietary software (see `LICENSE`). It includes the following third-party
components, which are distributed under their own licenses. The license texts are
reproduced below as their terms require.

| Component | Used for | License |
|---|---|---|
| .NET runtime, WPF, Windows Forms (included in the self-contained build) | application platform | MIT |
| [CommunityToolkit.Mvvm](https://github.com/CommunityToolkit/dotnet) | MVVM infrastructure | MIT |
| [NAudio](https://github.com/naudio/NAudio) (NAudio, NAudio.Core, NAudio.Wasapi, NAudio.WinMM, NAudio.Midi) | audio input and output | MIT |
| [System.Numerics.Tensors](https://github.com/dotnet/runtime) | dependency of NAudio | MIT |
| [Concentus](https://github.com/lostromb/concentus) (including the Opus reference library) | Opus voice codec | BSD-style (Opus license) |
| [Google.Protobuf](https://github.com/protocolbuffers/protobuf) | protocol serialization | BSD-3-Clause |
| [RNNoise](https://gitlab.xiph.org/xiph/rnnoise) | noise suppression | BSD-3-Clause |
| [RNNoise.NET](https://github.com/Yellow-Dog-Man/RNNoise.Net) (YellowDogMan.RRNoise.NET) | packaging of RNNoise | MIT |
| [Mumble](https://github.com/mumble-voip/mumble) protocol definitions (`Mumble.proto`, `MumbleUDP.proto`, excerpts) | Mumble protocol | BSD-3-Clause |

Build tools that do not become part of the program (Grpc.Tools, Microsoft.CodeAnalysis.ResxSourceGenerator,
test frameworks) are used under their own licenses and are not redistributed.

---

## MIT License

Applies to the components marked "MIT" above, with these copyright notices:

- .NET runtime, WPF, Windows Forms, System.Numerics.Tensors: Copyright (c) .NET Foundation and Contributors
- CommunityToolkit.Mvvm: Copyright (c) .NET Foundation and Contributors
- NAudio: Copyright (c) Mark Heath
- RNNoise.NET: Copyright (c) 2023 Yellow Dog Man Studios s.r.o.

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
