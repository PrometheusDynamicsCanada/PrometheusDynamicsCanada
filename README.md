# Prometheus Dynamics

**Software to compile, co-schedule, and verify gate-based quantum workloads across IBM Quantum, IQM Resonance, and Rigetti on Amazon Braket** *(alongside neutral-atom analog optimization studied on 256-atom QuEra Aquila)*.

- **Launch QuantumCompiler (`10` Free Full-Capability Jobs):** [prometheusdynamics.ca/quantumcompiler](https://prometheusdynamics.ca/quantumcompiler)
- **See the 60s product walkthrough & filter all 17 studies:** [prometheusdynamics.ca/quantum](https://prometheusdynamics.ca/quantum/) · [prometheusdynamics.ca/evidence](https://prometheusdynamics.ca/evidence/)
- **Scope an enterprise pilot (`5-50` OpenQASM circuits) or investor briefing:** [william@prometheusdynamics.ca](mailto:william@prometheusdynamics.ca)

---

## Start Here: Featured Repositories

| Priority | Repository | Question Answered & Principal Hardware Result | Offline Check (`0` Credentials) |
| :---: | :--- | :--- | :--- |
| **1** | **[`prometheus-quantum-overview`](https://github.com/PrometheusDynamicsCanada/prometheus-quantum-overview)** | **Portfolio Hub:** How do all `15` quantum archives (`1,081` unique cloud records, `15,912` PUBs/schedules, `24.64M` shots) fit together with `0` duplicate IDs? | `stdlib` · **`0.06 s`** |
| **2** | **[`prometheus-iqm-validation-campaign`](https://github.com/PrometheusDynamicsCanada/prometheus-iqm-validation-campaign)** | **Broad `6Q-11Q` IQM Sweep & Equal Packing:** `#1` overall agreement (`0.7609` vs. `0.7546` IQM Qiskit & `0.7267` VF2/SABRE), `23/42` observed cell rankings, `5/7` family leads, & `#1` QAOA `<C>` across `6Q-11Q` (`84` Garnet jobs), plus `#1` `6Q` equal `4-Way` packed quality (`0.8863`) at tied-lowest `3.00 cr` (`-75.0%` vs. unpacked) & `H2/LiH` chemistry (`214` records, `1.87M` shots). | `numpy` · **`0.68 s`** |
| **3** | **[`prometheus-quantum-chemistry`](https://github.com/PrometheusDynamicsCanada/prometheus-quantum-chemistry)** | **Chemistry Cost:** `52%-60%` fewer billed IBM seconds and IQM credits vs. the best baseline per confirmed `<= 25.0 mHa` molecular energy (`172` jobs, `49/49` early stops confirmed). | `numpy, scipy` · **`0.80 s`** |
| **4** | **[`prometheus-circuit-complexity-atlas`](https://github.com/PrometheusDynamicsCanada/prometheus-circuit-complexity-atlas)** | **Multi-Cloud Width, `H4` & `10Q` Matchgates (`3Q-23Q`):** `30/36` (`83.3%`) completed 3-way wins (`32/38` incl. `2` halts); `-33.8%` to `-36.9%` `8Q H4` error (`8.25 cr` `-21.4%` `3w` packed), `+9.76%` `4/4 PASS` `10Q` Matchgate (`ibm_kingston`), & `+85.7%` `7Q` Cepheus-1 (`225` records). | `numpy, qiskit` · **`1.29 s`** |
| **5** | **[`prometheus-practical-execution-limits`](https://github.com/PrometheusDynamicsCanada/prometheus-practical-execution-limits)** | **Demanding Circuits:** `10/10` fresh + `5/5` (`+32h`) confirmed passes on `15Q` IBM Marrakesh dense QFT (`5/5` at `12Q` IQM Emerald); baselines passed `0`. | `numpy` · **`80.6 s`** |
| **6** | **[`prometheus-quantum-execution`](https://github.com/PrometheusDynamicsCanada/prometheus-quantum-execution)** | **Queue & Stopping:** `30/36` vs. `27/36` accepted at `18.0 s` on IBM, `+83.3%` yield on IQM, and `0/31` false early stops (`157` records). | `numpy, scipy` · **`0.75 s`** |
| **7** | **[`prometheus-quality-gated-packing`](https://github.com/PrometheusDynamicsCanada/prometheus-quality-gated-packing)** | **Parallel Billing:** `-54.55%` billed IBM seconds/accepted across `4` circuit families & counterbalanced `ABCCBA` `4-way` vs. `8-way` quality gating (`29` records). | `numpy` · **`0.15 s`** |

---

## What Changed (`v2026.11.26` - `2026-11-26`)

- **Published Repository `#15` ([`prometheus-iqm-validation-campaign`](https://github.com/PrometheusDynamicsCanada/prometheus-iqm-validation-campaign)) (`214` IQM Resonance records = `212` completed QPU jobs + `2` unbilled attempts, `992` PUBs, `1,865,728` physical shots, `605.00` credits, `0.0000` discrepancy):**
  - **Preregistered `84`-job `6Q-11Q` Seven-Family Sweep on `IQM Garnet` (`336` executions, `688,128` shots):** Prometheus led aggregate agreement (`0.7609` vs. `0.7546` `IQM-Supported Qiskit` [`+0.83%`] and `0.7267` `Qiskit VF2 O3`/`SABRE O3` [`+4.71%`]), ranked first in `23/42` `(family, width)` cells (observed rankings), led `5/7` circuit families (`+17.0%` Forward QFT spectral peak mass; `#1` QAOA MaxCut `<C>` across every tested width `6Q-11Q`), and used `-5.23%` to `-8.99%` fewer `CZ` gates (`~4.87 s` classical compile time vs. `17-34 ms` baselines; `IQM Qiskit` led Inverse QFT and `VF2 O3` led `0`-SWAP `1D` spin chains).
  - **Six-stage `v4.2` IQM Crystal validation (`128` completed jobs, `1,177,600` shots):** Replicated `#1` `6Q` equal-opportunity `4-Way` spatial-packing agreement (`0.8863`, `-8.99%` `TVD`, `8/8` passes) at tied-lowest `3.00 cr` (`-75.0%` vs. `12.00 cr` unpacked), achieved the only `2/2` dual-wave symmetry-filtered Emerald `H2` pass (`4.016 mHa` at `3.00 cr`) and `#1` raw `6Q LiH` error (`88.996 mHa`, `-27.4%`), and raised Garnet `12Q` QAOA `<C>` by `+3.26%`.
- **Reconciled portfolio hub ([`prometheus-quantum-overview`](https://github.com/PrometheusDynamicsCanada/prometheus-quantum-overview)):** Expanded verified unique provider records from `867 -> 1,081` (`1,069` benchmark + `12` auxiliary across `481` IBM Quantum, `552` IQM Resonance, and `48` AWS Braket tasks), `14,920 -> 15,912` PUBs/schedules, and `22.77M -> 24.64M` (`24,639,160`) physical shots across `15` quantum repositories (`17` public repositories total) with `0` cross-repository duplicates.
