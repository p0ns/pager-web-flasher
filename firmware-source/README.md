# Pager Custom Firmware Source

The firmware files on this site are built from Meshtastic firmware commit
`c800fc8fa2c779903f15aae063cc3f7dd77bc9a1` on the `event/defcon34`
branch, with the changes in `defcon-custom.patch` applied.

To reproduce the firmware:

```bash
git clone https://github.com/meshtastic/firmware.git
cd firmware
git checkout c800fc8fa2c779903f15aae063cc3f7dd77bc9a1
git am /path/to/defcon-custom.patch
pio run -e tlora-pager
```

The resulting application version is `2.8.0.0748c44`.
