# jtag2axi

JTAG to AXI4-Lite Master bridge IP core based on the BSCANE2 primitive.

Allows read/write AXI4-Lite transactions initiated from a JTAG connection, without dependency on Xilinx debug IPs.

## Repository structure

```
jtag2axi/
├── docs/        → documentation and protocol specification
├── rtl/
│   └── hdl/     → VHDL source files
├── iprepo/      → Vivado IP metadata (component.xml, xgui/)
└── sw/          → host software
```

## Status

Work in progress.
