# Prometheus Dynamics

**Software to compile, co-schedule, and verify gate-based quantum workloads across IBM Quantum, IQM Resonance, and Rigetti on Amazon Braket** *(alongside neutral-atom analog optimization studied on 256-atom QuEra Aquila)*.

- **Launch QuantumCompiler (`10` Free Full-Capability Jobs):** [prometheusdynamics.ca/quantumcompiler](https://prometheusdynamics.ca/quantumcompiler)
- **See the 60s product walkthrough & filter all 16 studies:** [prometheusdynamics.ca/quantum](https://prometheusdynamics.ca/quantum/) · [prometheusdynamics.ca/evidence](https://prometheusdynamics.ca/evidence/)
- **Scope an enterprise pilot (`5-50` OpenQASM circuits) or investor briefing:** [william@prometheusdynamics.ca](mailto:william@prometheusdynamics.ca)

---

## Start Here: Featured Repositories

| Priority | Repository | Question Answered & Principal Hardware Result | Offline Check (`0` Credentials) |
| :---: | :--- | :--- | :--- |
| **1** | **[`prometheus-quantum-overview`](https://github.com/PrometheusDynamicsCanada/prometheus-quantum-overview)** | **Portfolio Hub:** How do all `14` quantum archives (`867` unique cloud records, `14,920` PUBs/schedules, `22.77M` shots) fit together with `0` duplicate IDs? | `stdlib` · **`0.06 s`** |
| **2** | **[`prometheus-quantum-chemistry`](https://github.com/PrometheusDynamicsCanada/prometheus-quantum-chemistry)** | **Chemistry Cost:** `52%-60%` fewer billed IBM seconds and IQM credits vs. the best baseline per confirmed `<= 25.0 mHa` molecular energy (`172` jobs, `49/49` early stops confirmed). | `numpy, scipy` · **`0.80 s`** |
| **3** | **[`prometheus-circuit-complexity-atlas`](https://github.com/PrometheusDynamicsCanada/prometheus-circuit-complexity-atlas)** | **Width, `H4` Chemistry & `10Q` Matchgates (`3Q-23Q`):** `30/36` (`83.3%`) completed 3-way wins (`32/38` incl. `2` halts); `-33.8%` to `-36.9%` `8Q H4` error (`8.25 cr` `-21.4%` `3w` packed), `+9.76%` `4/4 PASS` `10Q` Matchgate (`ibm_kingston`), & `+85.7%` `7Q` Cepheus-1 vs. best baseline (`225` records). | `numpy, qiskit` · **`1.29 s`** |
| **4** | **[`prometheus-practical-execution-limits`](https://github.com/PrometheusDynamicsCanada/prometheus-practical-execution-limits)** | **Demanding Circuits:** `10/10` fresh + `5/5` (`+32h`) confirmed passes on `15Q` IBM Marrakesh dense QFT (`5/5` at `12Q` IQM Emerald); baselines passed `0`. | `numpy` · **`80.6 s`** |
| **5** | **[`prometheus-quantum-execution`](https://github.com/PrometheusDynamicsCanada/prometheus-quantum-execution)** | **Queue & Stopping:** `30/36` vs. `27/36` accepted at `18.0 s` on IBM, `+83.3%` yield on IQM, and `0/31` false early stops (`157` records). | `numpy, scipy` · **`0.75 s`** |
| **6** | **[`prometheus-quality-gated-packing`](https://github.com/PrometheusDynamicsCanada/prometheus-quality-gated-packing)** | **Parallel Billing:** `-54.55%` billed IBM seconds/accepted across `4` circuit families & counterbalanced `ABCCBA` `4-way` vs. `8-way` quality gating (`29` records). | `numpy` · **`0.15 s`** |

---

## What Changed (`v2026.11.24` - `2026-11-24`)

- **Expanded [`prometheus-circuit-complexity-atlas`](https://github.com/PrometheusDynamicsCanada/prometheus-circuit-complexity-atlas) (`187 -> 225` cloud records, `32 -> 38` groups, `1.41M -> 1.78M` shots):** Added `3` correlated `8Q Linear H4 STO-3G CAS(4e,4o)` cohorts on `IQM Emerald` (`58.17 +/- 9.20 mHa` dual-wave confirmed `H4 1.00 A` in `1-way`, `-33.8%` to `-36.9%` error vs. best baseline TKET; back-to-back `3-way` spatial packing at **`8.25 cr` [`-21.43%` vs. SABRE, `-26.67%` vs. TKET; `2.25 cr` Wave 1 in `2.521 s`]** while ranking `#1` on $F_B = 0.8976$ and `#1` on chemistry) plus `3` `10Q QC-AFQMC Matchgate Shadow Quartet` cohorts isolating processor $T_1$ selection (`4/4 PASS`, `F_B = 0.8052` on auto-selected `ibm_kingston` vs. `0/4` on `2.5h`-queued `IQM Emerald`).
- **Reconciled portfolio hub ([`prometheus-quantum-overview`](https://github.com/PrometheusDynamicsCanada/prometheus-quantum-overview)):** Expanded verified unique provider records from `829 -> 867` (`857` benchmark + `10` auxiliary across `481` IBM Quantum, `338` IQM Resonance, and `48` AWS Braket tasks), `14,676 -> 14,920` PUBs/schedules, and `22.40M -> 22.77M` (`22,773,432`) physical shots with `0` cross-repository duplicates.
- **Launched commercial self-serve service ([`prometheusdynamics.ca/quantumcompiler`](https://prometheusdynamics.ca/quantumcompiler)):** Workspace onboarding with `10` free full-capability demonstration jobs (Digital Twin or customer BYOC keys across IBM, IQM, and AWS Braket) and value-scoped fixed licensing.
