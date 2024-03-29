# esp32Blink
Simple 'out of tree' project to blink an LED on the ESP32 C3 using the Zephyr RTOS

### Building and Running

This application can be built and executed on QEMU as follows:

#### Init:
```
    source ../zephyrproject/.venv/bin/activate
    source ../zephyrproject/zephyr/zephyr-env.sh
```

#### Build:
```
    west build -p always -b qemu_x86
```

To build for another board, change "qemu_x86" above to that board's name.

### Sample Output

```
    Hello World! x86
```

Exit QEMU by pressing `CTRL+A`
