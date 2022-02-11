# docker-firebird-2.5-ss-tbudf-enabled
Files for building a Docker image with Firebird 2.5 ss with tbudf library installed.

# Notes
The tbudf.so was intended to be a symlink to tbudf_x64_no-debug.so, but firebird does not allow symlinks.
So, to be totally clear: The file tbudf.so is just a copy of tbudf_x64_no-debug.so.
The other *.so files are provided just because they are hard to find on internet and I decided to share.
I had to compile tbudf from source using Pascal/Lazarus for Linux.

tbudf library sources (with some compiled binaries) can be found at https://tecnobyte.com.br/1233/Downloads
