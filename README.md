# tiny stack VM

Interpreter for make.fun's tiny stack ISA v1 (`node main.ts`, Node 22, stdlib only).
Reads `MAKEFUN_INPUT_DIR` (default `/input`), writes `<id>/stdout.bin` +
`<id>/exit.txt` under `MAKEFUN_OUTPUT_DIR` (default `/output`).

Verify locally: `MAKEFUN_INPUT_DIR=<kit>/practice/input MAKEFUN_OUTPUT_DIR=/tmp/tinyvm-out node main.ts`
