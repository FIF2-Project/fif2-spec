# FIF2 format

**The specification of the FIF2 fractal image format, with C header files for its structures.**

[**The FIF2 format — fif2.org**](https://fif2.org) ·
[**What is fractal image compression? — fractalimagecompression.com**](https://www.fractalimagecompression.com) ·
[Reference implementation — libfif](https://github.com/FIF2-Project/libfif)

---

FIF2 is an open file format for fractal images: a free reboot of the Fractal
Image Format of the 1990s. This repository is the normative home of the format.
An implementation in any language can be written from it alone.

| Folder | Contents |
| --- | --- |
| [`spec/`](spec/) | the format specification |
| [`include/`](include/) | C header files with the on-disk structures and constants |

| | Version |
| --- | --- |
| FIF2 format | 3.3 |

## Implementations

- [**libfif**](https://github.com/FIF2-Project/libfif): the reference encoder
  and decoder (C library) and the `fif` command-line tool.

## Questions and proposals

Questions about the format and proposals for changes are welcome as issues in
this repository. Bugs in the encoder, decoder or tool belong to
[libfif](https://github.com/FIF2-Project/libfif/issues).

## License

To be announced. The format itself is free for everyone to use, commercially
or non-commercially, with no license fees.

## Credits

- **FIF2 format**: Rezar Behzad
- **libfif and fif**: Oskar Behzadpour
