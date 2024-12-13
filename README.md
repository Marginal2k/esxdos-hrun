# Run CODE Hobetas from esxDOS

## Usage

### Usage in "pure" esxDOS

Copy `hrun` file to  `/BIN/` directory.
Type in commandline:

```
.hrun filename.$c
```
### Usage in esxDOS with LFN browser

Copy `hrun` file to  `/BIN/` directory, copy `$C` file to `/BIN/BPLUGINS` directory.
Select in LFN browser hobeta (`____.$C`) file and press Enter.

### Usage in NextZXOS on ZX Spectrum Next

Copy `hrun` file to  `/dot/` directory.
Add next line to your `browser.cfg` in `/nextzxos/` directory:

```
$C:cls: .hrun |
```
Select in NextZXOS browser hobeta (`____.$C`) file and press Enter.

## Development

Use [sjasmplus](https://github.com/z00m128/sjasmplus)

## License

This project licensed with `HOT POTATO LICENSE`.
