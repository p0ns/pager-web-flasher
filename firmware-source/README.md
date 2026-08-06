# Pager Custom Firmware Source

The firmware files on this site use Meshtastic firmware commit
`c800fc8fa2c779903f15aae063cc3f7dd77bc9a1` from the `event/defcon34`
branch as their base.

The selected safe rollback release uses only commit `ac7a71e64`. To reproduce
version `2.8.0.ac7a71e`:

```bash
git clone https://github.com/meshtastic/firmware.git
cd firmware
git checkout c800fc8fa2c779903f15aae063cc3f7dd77bc9a1
git am /path/to/defcon-custom-ac7a71e.patch
pio run -e tlora-pager
```

`defcon-custom.patch` also contains commit `0748c4466`, which added persistent
display brightness control. Version `2.8.0.0748c44` is no longer selected by
the flasher because a Pager boot loop was reported after that update. Its files
remain available for diagnosis.
