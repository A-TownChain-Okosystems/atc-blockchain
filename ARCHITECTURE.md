# 🌳 Architektur — atc-blockchain

> **Stand:** 2026-08-06 | **Commit:** eaa10e4
> **Teil von:** [A-TownChain Ökosystem](https://github.com/A-TownChain-Okosystems)

## Statistik

| Metrik | Wert |
|--------|------|
| Dateien | 72 |
| Zeilen | 6,781 |
| .atc | 37 |
| .py | 21 |
| .rs | 1 |
| .ts/.tsx | 4 |
| .md | 6 |

## Verzeichnisstruktur

```
├── alerts/ (1 files, 34 lines)
│   └── blockchain_alerts.yml (34 lines)
├── atcoin/ (1 files, 2 lines)
│   └── __init__.py (2 lines)
├── consensus/ (19 files, 1,519 lines)
│   ├── MIGRATION_INDEX.md (13 lines)
│   ├── __init__.py (2 lines)
│   ├── consensus.atc (144 lines)
│   ├── fork_atc85.atc (74 lines)
│   ├── fork_resolution.atc (7 lines)
│   ├── gas_fee.atc (7 lines)
│   ├── gas_fee_atc86.atc (71 lines)
│   ├── hybrid_atc84.atc (98 lines)
│   ├── hybrid_consensus.atc (7 lines)
│   ├── poh.atc (7 lines)
│   ├── poh.py (67 lines)
│   ├── poh_atc83.atc (79 lines)
│   ├── poh_integration.atc (78 lines)
│   ├── poh_integration.py (29 lines)
│   ├── pos.atc (7 lines)
│   ├── pos_atc82.atc (92 lines)
│   ├── pow.atc (7 lines)
│   ├── pow_atc81.atc (89 lines)
│   └── shiva_consensus.py (641 lines)
├── contracts/ (7 files, 16 lines)
│   ├── atc001/ (1 files, 0 lines)
│   │   └── __init__.py
│   ├── atc8300/ (1 files, 2 lines)
│   │   └── __init__.py (2 lines)
│   ├── base/ (1 files, 0 lines)
│   │   └── __init__.py
│   ├── governance/ (1 files, 6 lines)
│   │   └── governance_contract.atc (6 lines)
│   ├── shivamon/ (1 files, 2 lines)
│   │   └── __init__.py (2 lines)
│   ├── __init__.py
│   └── contract_engine_atc14.atc (6 lines)
├── dex/ (2 files, 279 lines)
│   ├── __init__.py (2 lines)
│   └── amm.atc (277 lines)
├── governance/ (7 files, 1,039 lines)
│   ├── __init__.py (2 lines)
│   ├── dao.atc (168 lines)
│   ├── dao_live.atc (235 lines)
│   ├── governance.atc (113 lines)
│   ├── snapshot.atc (151 lines)
│   ├── timelock.atc (150 lines)
│   └── treasury.atc (220 lines)
├── kernel/ (1 files, 57 lines)
│   └── src/ (1 files, 57 lines)
│       └── blockchain.rs (57 lines)
├── mainnet/ (3 files, 258 lines)
│   ├── __init__.py (2 lines)
│   ├── launch_manager.atc (105 lines)
│   └── mainnet_config.atc (151 lines)
├── network/ (2 files, 193 lines)
│   ├── atc-04_dag_consensus_propagation.atc (58 lines)
│   └── latency_opt_atc06.atc (135 lines)
├── nodes/ (8 files, 1,425 lines)
│   ├── __init__.py (2 lines)
│   ├── block_propagation.atc (87 lines)
│   ├── bootstrap.atc (234 lines)
│   ├── bootstrap.py (257 lines)
│   ├── discovery.py (314 lines)
│   ├── initial_sync.atc (207 lines)
│   ├── node.atc (192 lines)
│   └── testnet_launcher.atc (132 lines)
├── propagation/ (1 files, 98 lines)
│   └── block_gossip.atc (98 lines)
├── src/ (3 files, 600 lines)
│   ├── backend/ (1 files, 129 lines)
│   │   └── blockchain/ (1 files, 129 lines)
│   │       └── engine.ts (129 lines)
│   └── components/ (2 files, 471 lines)
│       ├── BlockchainEcosystemView.tsx (224 lines)
│       └── BlockchainLedgerView.tsx (247 lines)
├── wallet/ (6 files, 685 lines)
│   ├── __init__.py (2 lines)
│   ├── did.atc (122 lines)
│   ├── did.py (74 lines)
│   ├── multisig.atc (268 lines)
│   ├── multisig.py (107 lines)
│   └── wordlist.atc (112 lines)
├── workspace/ (1 files, 167 lines)
│   └── src/ (1 files, 167 lines)
│       └── backend/ (1 files, 167 lines)
│           └── blockchain/ (1 files, 167 lines)
│               └── engine.ts (167 lines)
├── zkp/ (2 files, 93 lines)
│   ├── __init__.py (4 lines)
│   └── groth16.atc (89 lines)
├── .gitignore
├── CHANGELOG.md (21 lines)
├── FILE_REGISTER.md (109 lines)
├── LICENSE
├── README.md (146 lines)
├── ROADMAP.md (21 lines)
├── STATUS.md (19 lines)
└── __init__.py
```

---
*Auto-generiert 2026-08-06 · Aurora (MasterBrain · Base44)*
