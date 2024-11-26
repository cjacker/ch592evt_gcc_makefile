# ch59x riscv ble evt with gcc and makefile support

This is pre-converted ch59x riscv ble evt firmware library with gcc and makefile support from WCH official CH592EVT.ZIP.

It is converted by [ch5xx_riscv_ble_evt_makefile_gcc_project_template](https://github.com/cjacker/ch5xx_riscv_ble_evt_makefile_gcc_project_template)

This firmware library support below parts from WCH:

- ch592
- ch591

The default part is set to 'ch591', you can change it with `./setpart.sh <part>`. the corresponding 'Link.ld' will update automatically from the template.

The default 'User' codes is not BLE related, just blink a LED. all evt examples shipped in original EVT package provided in 'Examples' dir.

To build the project, type `make`.

