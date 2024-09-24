<p align="center">
<img src="https://repository-images.githubusercontent.com/3925242/a4566200-912a-11ea-984f-c387546a3126">
</p>

[bgfx](https://github.com/bkaradzic/bgfx) - Cross-platform rendering library
============================================================================

Please note: This is NOT the official version of bgfx. Like most things on my Github, this version is made purely for educational and testing purposes. - Astukari

NOTE TO SELF: Build is in a different folder, bgfx-test. Here's the instructions I followed to get it to work:

1. 
git clone https://github.com/bkaradzic/bx.git
git clone https://github.com/bkaradzic/bimg.git
git clone https://github.com/bkaradzic/bgfx.git

2. 
cd bgfx

3. 
..\bx\tools\bin\windows\genie --with-examples vs2019

4. 
start .build\projects\vs2019\bgfx.sln

5. 
Run any example using the Local Windows Debugger up top.


[What is it?](https://bkaradzic.github.io/bgfx/overview.html)
-------------------------------------------------------------

Cross-platform, graphics API agnostic, "Bring Your Own Engine/Framework" style
rendering library.

Supported rendering backends:

 * Direct3D 11
 * Direct3D 12
 * GNM (only for licensed PS4 developers, search DevNet forums for source)
 * Metal
 * OpenGL 2.1
 * OpenGL 3.1+
 * OpenGL ES 2
 * OpenGL ES 3.1
 * Vulkan
 * WebGL 1.0
 * WebGL 2.0

Supported platforms:

 * Android (14+)
 * iOS/iPadOS/tvOS (16.0+)
 * Linux
 * macOS (13.0+)
 * PlayStation 4
 * RaspberryPi
 * UWP (Universal Windows, Xbox One)
 * Wasm/Emscripten
 * Windows (7+)

Supported compilers:

 * Clang 11 and above
 * GCC 8 and above
 * VS2019 and above
 * Apple clang 12 and above

Languages:

 * C/C++
 * Beef
 * C#
 * D
 * Go
 * Haskell
 * Java
 * Lua
 * Nim
 * Pascal
 * Python
 * Rust
 * Swift
 * Zig

Who is using it? [#madewithbgfx](https://twitter.com/search?q=%23madewithbgfx&src=typed_query&f=live)
-----------------------------------------------------------------------------------------------------

[License (BSD 2-clause)](https://bkaradzic.github.io/bgfx/license.html)
-----------------------------------------------------------------------

<a href="http://opensource.org/licenses/BSD-2-Clause" target="_blank">
<img align="right" src="https://opensource.org/wp-content/uploads/2022/10/osi-badge-dark.svg" width="100" height="137">
</a>

	Copyright 2010-2024 Branimir Karadzic
	
	Redistribution and use in source and binary forms, with or without modification,
	are permitted provided that the following conditions are met:
	
	   1. Redistributions of source code must retain the above copyright notice, this
	      list of conditions and the following disclaimer.
	
	   2. Redistributions in binary form must reproduce the above copyright notice,
	      this list of conditions and the following disclaimer in the documentation
	      and/or other materials provided with the distribution.
	
	THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
	ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
	WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED.
	IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT,
	INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING,
	BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE,
	DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY
	OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE
	OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED
	OF THE POSSIBILITY OF SUCH DAMAGE.
