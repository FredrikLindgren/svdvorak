# Svdvorak with an X leaning

Svdvorak is a Dvorak keyboard layout adapted for the Swedish alphabet, originally by Gunnar Parment. Microsoft Windows lacks anything but the original Dvorak layout. This particular implementation is for Windows and embellishes the layout with some commonly used symbols (parentheses etc.) under the left hand in combination with AltGr, as found in the Svdvorak layout available through the X Window System (at least, I think it's through X). Note that this implementation does not strive to emulate the X layout.

This Svdvorak layout is available either with or without remapped virtual keys (VK). The difference is that with remapped virtual keys, Ctrl-C, for instance, uses the Svdovak position for C, while the implementation without remapped virtual keys uses the QWERTY position for C.

Visual descriptions of the layout are available in the images folder. Note that you cannot see the virtual keys.

Installers are available under Releases. They have been tested with Windows 7 and Windows 10.

## Compatibility

Games appear to have no problems with the layout.

Anti-virus heuristics may raise a false positive over the installer. When it has happened to me, building the installer on the same system seemed to mollify the anti-virus (at least until the very same file was moved off-system and then back).

## Building the layout

The layout is built with the [Microsoft Keyboard Layout Creator](https://msdn.microsoft.com/en-us/globalization/keyboardlayouts.aspx).

## Licence

Copyright (C) 2016 Fredrik Lindgren

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice, this
  list of conditions and the following disclaimer.

* Redistributions in binary form must reproduce the above copyright notice,
  this list of conditions and the following disclaimer in the documentation
  and/or other materials provided with the distribution.

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
