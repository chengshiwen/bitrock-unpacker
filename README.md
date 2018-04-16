# BitRock Unpacker

A tcl script for unpacking bitrock packed archives.

## Requirements

- [tclkit](https://code.google.com/archive/p/tclkit/downloads)

```
gzip -d tclkit-*.gz
mv tclkit-* tclkit
chmod +x tclkit
sudo mv tclkit /usr/bin
```

- [sdx.kit](https://code.google.com/archive/p/tclkit/downloads)

```
mv sdx-*.kit sdx.kit
sudo mv sdx.kit /usr/bin
```

## Usage

```
./bitrock-unpacker.tcl installerFile outputDirectory
```
