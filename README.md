# Prometheus Dynamics

**Prometheus makes a quantum chemistry and algorithm budget go further - reducing billed quantum hardware resources per confirmed molecular-energy result by 52% to 60% on IBM and IQM, leading a 7-family IQM compiler sweep, and validating multi-window execution on Amazon Braket.**

- **Evaluate Prometheus on your workloads (pharma, chemicals, materials & enterprise quantum teams):** [prometheusdynamics.ca/connect](https://prometheusdynamics.ca/connect/) · [william@prometheusdynamics.ca](mailto:william@prometheusdynamics.ca?subject=Joint%20Quantum%20Chemistry%20Pilot)
- **Focused buyer & partner path:** [Chemistry & Quantum OS Overview](https://prometheusdynamics.ca/quantum/) -> [Search All 17 Study Repositories](https://prometheusdynamics.ca/evidence/) -> [Evaluate Your Workload](https://prometheusdynamics.ca/connect/)
- **Why it matters across pharma, chemicals, materials & cloud platforms:** Drug-discovery conformer studies, catalysis, and battery-materials R&D require evaluating entire series of molecular geometries and optimization steps. Cutting billed QPU spend by 52% to 60% per confirmed energy result (paired with 33.8% to 36.9% lower correlated 8Q H4 error) lets R&D teams explore roughly twice as many structures per budget while giving enterprise teams and cloud platforms across IBM, IQM, and Amazon Braket auditable, reproducible outcomes.

---

## Start Here: Featured Quantum Repositories (15 Quantum / 17 Study Repositories Overall)

*Extent & longitudinal hardware depth (`June - November 2026`, `40` execution dates):* Tested across **7 physical QPUs from 4 vendors - IBM (`ibm_fez`, `ibm_kingston`, `ibm_marrakesh`), IQM (`IQM Emerald`, `IQM Garnet`), Rigetti (`Rigetti Cepheus-1-108Q`), and QuEra (`QuEra Aquila`)** - spanning **1,069 completed benchmark jobs and tasks** (**1,081 unique cloud provider records**, **15,912 circuits and schedules**, **24.64 million measurement shots**, and **0 duplicate IDs** across 15 public quantum repositories, replicated over separated calibration windows and pre-committed SHA-256 locks). Supported pilot evaluations and live Pilot Console demonstrations are available today; partner funding builds the self-installable Python SDK, 24/7 queue failover, and always-on hosted web access.

| Priority | Repository | Plain-English Result & Comparator | Offline Verifier |
| :---: | :--- | :--- | :--- |
| **1** | **[prometheus-quantum-chemistry](https://github.com/PrometheusDynamicsCanada/prometheus-quantum-chemistry)** | **Chemistry Budget Efficiency (Lead Commercial Result):** 52% to 60% fewer billed IBM seconds and IQM credits vs. the strongest SABRE or TKET baseline per dual-run confirmed <= 25.0 mHa molecular energy across unseen molecules and live SPSA optimization (172 jobs, 3.76M shots; 49/49 early stops confirmed). | `numpy, scipy` |
| **2** | **[prometheus-iqm-validation-campaign](https://github.com/PrometheusDynamicsCanada/prometheus-iqm-validation-campaign)** | **IQM Compiler Sweep (6Q-11Q) & Equal Packing:** #1 overall output agreement (0.7609 vs. 0.7546 IQM-supported Qiskit and 0.7267 VF2/SABRE) and 5 of 7 family leads across 84 Garnet jobs, plus #1 6-qubit packed agreement (0.8863, 8/8 passes) at tied-lowest 3.00 credits (-75% vs. separate execution) and H2/LiH chemistry (212 completed jobs). | `numpy` |
| **3** | **[prometheus-braket-validation](https://github.com/PrometheusDynamicsCanada/prometheus-braket-validation)** | **Amazon Braket Multi-Window Validation:** +6.61% post-recalibration output agreement on 108-qubit Rigetti Cepheus-1 (16/18 wins vs. SABRE O3) and +18.1% 12-atom optimal yield (-15.4% cost/optimum) on 256-atom QuEra Aquila (22 tasks). | `numpy, scipy` |
| **4** | **[prometheus-circuit-complexity-atlas](https://github.com/PrometheusDynamicsCanada/prometheus-circuit-complexity-atlas)** | **Correlated H4 Accuracy & Multi-Cloud Scaling (3Q-23Q):** 33.8% to 36.9% lower 8-qubit Linear H4 active-space energy error on IQM Emerald, 4/4 verified 10Q matchgate passes on IBM Kingston, and #1 in 30/36 completed 3-compiler groups across 6 QPUs (224 completed jobs). | `numpy, qiskit` |
| **5** | **[prometheus-quantum-overview](https://github.com/PrometheusDynamicsCanada/prometheus-quantum-overview)** | **Portfolio Hub:** Reconciles all 15 quantum repositories (1,069 completed benchmark jobs/tasks, 1,081 total cloud records, 24.64M shots) with plain-English definitions and zero duplicate IDs. | Python stdlib |
| **6** | **[prometheus-practical-execution-limits](https://github.com/PrometheusDynamicsCanada/prometheus-practical-execution-limits)** | **Demanding QFT Circuits:** Passed all 10 fresh and all 5 repeated (+32h) 15-qubit dense QFT tests on IBM Marrakesh (and 5/5 at 12Q on IQM Emerald), while tested baselines passed none (24 jobs). | `numpy` |
| **7** | **[prometheus-quantum-execution](https://github.com/PrometheusDynamicsCanada/prometheus-quantum-execution)** | **Automated Queue & Shot Stopping:** 30/36 vs. 27/36 requests accepted at equal 18.0 s on IBM Kingston, 22/36 vs. 12/36 on IQM Emerald, and 0/31 false early stops (149 benchmark jobs). | `numpy, scipy` |

---

## Separate Non-Quantum Research Archives

- **[argus-server-protection](https://github.com/PrometheusDynamicsCanada/argus-server-protection):** Linux connection-flood protection keeping 90.8% to 97.5% of visitor HTTPS requests under 500 ms on a 4 USD/mo VM across 71 external trials.
- **[Hyperion-fusion-telemetry](https://github.com/PrometheusDynamicsCanada/Hyperion-fusion-telemetry):** Retrospective plasma disruption warning evaluation across 4,114 unique held-out discharges on EAST, DIII-D, and Alcator C-Mod plus a 12,693-discharge UKAEA MAST scan.
