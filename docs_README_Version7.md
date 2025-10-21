# Diagrams

- `lw_datapath_annotated.mmd` — Mermaid source for the annotated single-cycle MIPS datapath of `lw $t1, 32($t2)`.

A GitHub Actions workflow renders `.mmd` files in this folder into `.png` on push.

## Local render (optional)
```bash
npx -y @mermaid-js/mermaid-cli -i docs/lw_datapath_annotated.mmd -o docs/lw_datapath_annotated.png
```