<!-- # AIC Documentation

This folder contains the core documentation for Adaptive Intelligence Circle (AIC).

## Reading Order
1. PRINCIPLES.md
2. Architecture.md
3. PHASES.md
4. LOGGING_CONTRACT.md
5. SECURITY.md
6. GLOSSARY.md

## Change Control
- All changes must be proposed via Pull Request.
- Each document has a version header.
- Major changes require consensus aligned with P1–P6 principles. -->

# AIC-TestNet Documentation

**Project:** Adaptive Intelligence Circle – Test Network  
**Phase:** 0 (Local / Controlled)  
**Principles:** Ethical-from-Kernel · Third Path Absolute · Zero Donation (2 layers) · Human Meaning Preservation  

---

## 1. Document map

| File | Audience | Content |
|------|----------|---------|
| [Architecture.md](./Architecture.md) | Engineers, architects | Topology 5+1, service map, control flows, phases |
| [PRINCIPLES.md](./PRINCIPLES.md) | All contributors | Six immutable principles + enforcement rules |
| [LOGGING_CONTRACT.md](./LOGGING_CONTRACT.md) | Kernel / monitoring | Audit log format, hash chain, change policy |
| [PHASES.md](./PHASES.md) | Leads, governance | Phase 0 → MainNet criteria and checklists |
| [SECURITY.md](./SECURITY.md) | Security / governance | Trust boundaries, threats, fail-closed rules |
| [GLOSSARY.md](./GLOSSARY.md) | Everyone | Shared vocabulary |

---

## 2. Recommended reading order (Phase 0)

1. **Architecture.md** §1–§4 — purpose, topology, Kernel internals  
2. **PRINCIPLES.md** — what must never change at runtime  
3. **LOGGING_CONTRACT.md** — before editing `services/ethical-kernel/logs/`  
4. **PHASES.md** — what “done” means for Phase 0  
5. **SECURITY.md** — fail-closed expectations  
6. **GLOSSARY.md** — when a term is ambiguous  

---

## 3. Source layout (reference)

```
AIC-TestNet/
├── docs/                            ← you are here
├── services/
│   └── ethical-kernel/
│       ├── core/                    # principles, engine, verifier
│       ├── logs/                    # audit subsystem (see LOGGING_CONTRACT)
│       ├── adapters/
│       ├── config/
│       ├── simulation/
│       └── tests/
├── monitoring/                      # metrics, alerts (Phase 0 optional)
├── logs/                            # aggregated TestNet-level logs
├── docker-compose.yml
└── README.md
```

---

## 4. Change control

| Change type | Required updates |
|-------------|------------------|
| Principle definition | PRINCIPLES.md + Architecture.md + governance note |
| Decision semantics | Architecture.md + LOGGING_CONTRACT.md |
| Log field names / hash payload | LOGGING_CONTRACT.md + `logs/log_format.h` |
| Phase promotion | PHASES.md checklist completed |

Documentation is part of the protocol surface. Keep it consistent with code.

---

## 5. Status

| Item | State |
|------|--------|
| Phase | 0 – Local / Controlled |
| Kernel | Required functional |
| Other services | May be stubs |
| MainNet | Not claimed |

