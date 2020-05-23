# woff2otf

This is a small utility to convert WOFF files to the OTF font format. It uses Python 3, so you need to have it installed in order to run it.

## Usage
To run the script, simply invoke it from the command line:
```
./woff2otf.py font.woff font.otf
```

The first parameter is the source file (the WOFF) font, and the second parameter is the output file (in OTF format).

To convert all files in a directory, renaming them accordingly:

```bash
for i in *.woff; do ./woff2otf.py $i ${i%.woff}.otf; done
```
