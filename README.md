NVorbis
-------

NVorbis is a .Net library for decoding Xiph.org Vorbis files. It is designed to run in partial trust environments and does not require P/Invoke or unsafe code.

This implementation is based on the Vorbis specification found on xiph.org. The MDCT and Huffman codeword generator were borrowed from public domain implementations in https://github.com/nothings/stb/blob/master/stb_vorbis.c.

Currently the only container supported is Xiph.org Ogg.  Ogg Skeleton and Matroska / WebM are planned (no ETA, though).  RTP support is possible, but not planned.

This version of NVorbis compiled under .NET Framework 2.0 to ensure maximum compatibility against old hardware while doesn't have any performance effect to new hardware.

Although the repository is forked and modified directly from the original one, this project isn't intended to use directly. 

The API itself is used as dependency of [Cgen.Audio](http://github.com/SirusDoma/Cgen.Audio) Project.