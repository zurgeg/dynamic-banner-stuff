# CHANS opcodes
## 1-byte
### Other
- `0x00`: END
- `0x01`: RACC

### Stacc
- `0x04`: PACC

### Arthmetics
- `0x06`: ADD POP, ACC
- `0x07`: SUB POP, ACC
- `0x08`: MUL POP, ACC
- `0x09`: DIV POP, ACC
- `0x0A`: MOD POP, ACC

### Logic
- `0x0B`: AND POP, ACC
- `0x0C`: OR POP, ACC
- `0x0D`: XOR POP, ACC
- `0x0E`: SHL POP, ACC
- `0x0F`: SHR POP, ACC

### Comparison
- `0x10`: EQU POP, ACC
- `0x11`: NEQ POP, ACC
- `0x12`: LT POP, ACC
- `0x13`: GT POP, ACC
- `0x14`: LTE POP, ACC
- `0x15`: GTE POP, ACC
- `0x17`: NACC

