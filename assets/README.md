# AIC Whitepaper

**Adaptive Intelligence Circle (AIC) & World Meaning Infrastructure (WMI)**  
Canonical *human-readable* specification of intent, architecture, and boundaries.

| Item | Value |
|------|--------|
| Status | Advanced draft (pre-Covenant) |
| Primary text | [Whitepaper.md](./Whitepaper.md) (assembled) / [chapters/](./chapters/) |
| License (this docs repo) | See [LICENSE](./LICENSE) |
| Protocol code | Other repos under [AdaptiveIntelligenceCircle](https://github.com/AdaptiveIntelligenceCircle) — often GPL-3.0 |

## How to read

1. Start: [chapters/01-introduction.md](./chapters/01-introduction.md)  
2. Boundaries: [chapters/03-third-path.md](./chapters/03-third-path.md), [legal/](./legal/)  
3. System: [chapters/04-ethical-kernel.md](./chapters/04-ethical-kernel.md) → [05-architecture.md](./chapters/05-architecture.md) → [06-governance.md](./chapters/06-governance.md)  
4. Status: [chapters/07-testnet.md](./chapters/07-testnet.md), [08-future.md](./chapters/08-future.md)

**This whitepaper is not a securities offering, not a token prospectus, and not a claim of UN or state endorsement.**

## Repository layout

```text
AIC-Whitepaper/
├── README.md
├── LICENSE
├── Whitepaper.md          # Assembled view
├── chapters/              # Source of truth by section
├── assets/
├── legal/
├── governance/
├── versions/
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
└── SECURITY.md
```

## Version

See [versions/changelog.md](./versions/changelog.md).
EOF

cat > "$BASE/LICENSE" << 'EOF'
# License — AIC Whitepaper (documentation)

Unless otherwise noted, text in this repository is dual-marked for clarity:

1. **Documentation / whitepaper prose:** Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)
   https://creativecommons.org/licenses/by-nc-nd/4.0/

2. **Normative protocol implementations** referenced by this paper live in other AdaptiveIntelligenceCircle repositories and are typically licensed under **GNU GPL v3.0** (and any stated supplements such as OpenMDW where applicable). This documentation license does **not** re-license those codebases.

You may share the whitepaper with attribution for non-commercial purposes; do not create derivative *versions of the paper* under CC BY-NC-ND without permission. Forking *protocol code* follows each code repo’s LICENSE.

Trademark and project names remain with their holders. Partnership mentions do not transfer ownership of the protocol.