# Prometheus Dynamics

**Software to compile, co-schedule, and verify gate-based quantum workloads across IBM Quantum, IQM Resonance, and Rigetti on Amazon Braket** *(alongside neutral-atom analog optimization studied on 256-atom QuEra Aquila)*.

- **See the product & 60s walkthrough:** [prometheusdynamics.ca](https://prometheusdynamics.ca/#product-walkthrough)
- **Filter all 16 studies by research question:** [prometheusdynamics.ca/evidence](https://prometheusdynamics.ca/evidence/)
- **Scope a supported pilot (`5-50` OpenQASM circuits) or investor briefing:** [william@prometheusdynamics.ca](mailto:william@prometheusdynamics.ca)

---

## Start Here: Featured Repositories

| Priority | Repository | Question Answered & Principal Hardware Result | Offline Check (`0` Credentials) |
| :---: | :--- | :--- | :--- |
| **1** | **[`prometheus-quantum-overview`](https://github.com/PrometheusDynamicsCanada/prometheus-quantum-overview)** | **Portfolio Hub:** How do all `14` quantum archives (`829` unique cloud records, `14,676` PUBs/schedules, `22.40M` shots) fit together with `0` duplicate IDs? | `stdlib` · **`0.06 s`** |
| **2** | **[`prometheus-quantum-chemistry`](https://github.com/PrometheusDynamicsCanada/prometheus-quantum-chemistry)** | **Chemistry Cost:** `52%-60%` fewer billed IBM seconds and IQM credits vs. the best baseline per confirmed `<= 25.0 mHa` molecular energy (`172` jobs, `49/49` early stops confirmed). | `numpy, scipy` · **`0.80 s`** |
| **3** | **[`prometheus-circuit-complexity-atlas`](https://github.com/PrometheusDynamicsCanada/prometheus-circuit-complexity-atlas)** | **Width & Connectivity (`3Q-23Q`):** `25/30` (`83.3%`) completed 3-way wins (`27/32` incl. `2` halts); `+9.04%` (`-20.0%` cr) on `13Q` Emerald & `+85.7%` on `7Q` Cepheus-1 vs. best base TKET (`+155.8%` vs. SABRE at `13Q`). | `numpy, qiskit` · **`1.19 s`** |
| **4** | **[`prometheus-practical-execution-limits`](https://github.com/PrometheusDynamicsCanada/prometheus-practical-execution-limits)** | **Demanding Circuits:** `10/10` fresh + `5/5` (`+32h`) confirmed passes on `15Q` IBM Marrakesh dense QFT (`5/5` at `12Q` IQM Emerald); baselines passed `0`. | `numpy` · **`80.6 s`** |
| **5** | **[`prometheus-quantum-execution`](https://github.com/PrometheusDynamicsCanada/prometheus-quantum-execution)** | **Queue & Stopping:** `30/36` vs. `27/36` accepted at `18.0 s` on IBM, `+83.3%` yield on IQM, and `0/31` false early stops (`157` records). | `numpy, scipy` · **`0.75 s`** |
| **6** | **[`prometheus-quality-gated-packing`](https://github.com/PrometheusDynamicsCanada/prometheus-quality-gated-packing)** | **Parallel Billing:** `-54.55%` billed IBM seconds/accepted across `4` circuit families & counterbalanced `ABCCBA` `4-way` vs. `8-way` quality gating (`29` records). | `numpy` · **`0.15 s`** |

---

## What Changed (`v2026.11.23` - `2026-11-23`)

- **Added [`prometheus-circuit-complexity-atlas`](https://github.com/PrometheusDynamicsCanada/prometheus-circuit-complexity-atlas):** `187` new cloud QPU records (`32` three-compiler groups, `464` PUBs, `1.41M` shots across `6` superconducting QPUs, including two simultaneous `5`-QPU cross-cloud dispatches and `4Q H2` / `6Q LiH` chemistry runs).
- **Reconciled portfolio hub ([`prometheus-quantum-overview`](https://github.com/PrometheusDynamicsCanada/prometheus-quantum-overview)):** Expanded verified unique provider records from `642 -> 829` (`819` benchmark + `10` auxiliary) and physical shots from `20.99M -> 22.40M` across `14` quantum repositories (`16` total repositories including [`argus-server-protection`](https://github.com/PrometheusDynamicsCanada/argus-server-protection) and [`Hyperion-fusion-telemetry`](https://github.com/PrometheusDynamicsCanada/Hyperion-fusion-telemetry)).
- **Standardized plain-English introductions & simplified opening charts** across all `16` repositories (`The question -> The test -> The finding -> The significance -> The boundary -> The evidence`), with measured offline verification runtimes and searchable filters at [prometheusdynamics.ca/evidence](https://prometheusdynamics.ca/evidence/).
