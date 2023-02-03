# clownmd5

This is an MD5 hasher. Two versions are provided: one written in ANSI
C, and another written in Lua. The C version is implemented as a
single-header library. Both versions are licensed under the 0BSD
licence.

I initially wrote the C version back when I was in university. I was
meant to write it in C#, but I prefer C so I wrote the prototype in
that instead and converted it to C# afterwards. The C# version is
pretty redundant since the standard library already has an MD5
hasher, so I haven't included it in this repository. Way later, I
stumbled across a copy of the C prototype and refactored it into a
single-header library. I also overhauled the interface to be a lot
more low-level, to eliminate overhead.

The Lua version was something that I created much more recently, just
because a Lua script of mine needed a file hasher and none of the
libraries that I could find were very fast. It's a straight port of
the C version.
