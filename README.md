# Hi, I'm Martin 👋

I'm an operations research scientist. I'm a Senior Software Engineer, Operations Research at [Optym](https://www.optym.com/), contracted to Amazon Global Realty, where I've spent nearly 3 years building large-scale mixed-integer optimization systems (Benders decomposition, column generation, FICO Xpress). Before that I spent 1.5 years in backend and platform engineering at Mailmodo and Gojek. I studied Mechanical Engineering at IIT (BHU) Varanasi.

> may the code you write bring you happiness

## Experience

### Optym, contracted to Amazon Global Realty
**Senior Software Engineer, Operations Research** · Feb 2024 - Present · Bangalore

- Built the input, engine and output layers of **REOS**, Amazon's mixed-integer real-estate optimization model for the US network (Python, FICO Xpress, AWS). Validated outputs secured the contract and underpin **$5 billion in projected savings over 10 years**.
- Cut the **Benders decomposition** model runtime by **50%** and the **column generation** model runtime by **90%** by parallelizing subproblem and pricing solves.
- Reduced the column-generation model's **memory footprint by 85%**, making a single run over the **entire US market** feasible on one instance.
- Led the **Decomposition Lab** initiative as project manager, driving development of the **Graph Master** algorithm and its integration with partner business units.
- Built and deployed an **LLM layer**, now in production, that explains REOS solutions (binding constraints and trade-offs) to business stakeholders.
- Named **Best Performer, Q2 2026**, for the Optym Labs business unit.

### Mailmodo
**Platform Engineer, Platform and Services team** · Jan 2023 - Feb 2024 · Bangalore

- Built the **Send-Time Optimization** feature, which schedules emails for the recipient's highest-engagement window and **lifted open, click and submission rates by 15%**.
- Scaled the custom-events, opens and clicks trackers to **3x throughput** with asynchronous processing and horizontal scaling (TypeScript, Node.js, Kubernetes, Azure Durable Functions).

### Gojek
**Backend Engineer, GoFood Consumer Discovery** · Jul 2022 - Nov 2022 · Gurugram

- **Tripled throughput** of the merchant-profile service by adding in-memory caching (Go, BigQuery, GCP).

## Research and publications

### Strengthening Compact Vehicle Routing Formulations through Arc-Flow Aggregation and Refinement (2026)
[arXiv:2611.20310](https://arxiv.org/abs/2611.20310) · submitted to *Transportation Science*

With J. Yarkony, W.-J. van Hoeve (Carnegie Mellon), A. Karahalios, S. Khalilpourazari, L.-M. Rousseau (Polytechnique Montréal), and X. Zhu. I implemented the method and ran the computational studies on the 168 Solomon VRPTW instances.

### Facility location with decision-dependent scenario probabilities (2026)
[Optimization Online](https://optimization-online.org/?p=37860) · submitted to *INFORMS Journal on Computing* · independent research

- **Linked lifted cuts** for the bilinear objective that cut the McCormick root gap from **6-10% to 0.07-0.43%**.
- A **scenario-decomposed branch-and-cut** that solves all 25 test instances to optimality.

### Online bin packing (2026)
[arXiv:2610.32367](https://arxiv.org/abs/2610.32367) · submitted to *Algorithmica* · independent research · [code and certificates](https://github.com/ksnmartin/online-bin-packing-bounds)

- Improved the best known upper bound on the asymptotic competitive ratio from **1.5782896 to 1.5782147**, the first improvement since 2018.
- Every claimed bound ships with a machine-checkable certificate that an independent checker re-verifies.

## Toolbox

| | |
| --- | --- |
| **Optimization** | Mixed-integer programming, Benders decomposition, column generation, LP/MIP modeling, heuristics; FICO Xpress, Gurobi, CPLEX |
| **Languages** | Python (NumPy, pandas), C++, Go, TypeScript, SQL |
| **Platform** | AWS (CDK, S3, Batch), Azure, Docker, Kubernetes, FastAPI, Git |

## Education

**Indian Institute of Technology (BHU), Varanasi** · BTech, Mechanical Engineering · 2018 - 2022

## Let's connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ksnmartin)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:karyamsettymartin@gmail.com)
[![Instagram](https://img.shields.io/badge/Instagram-E1306C?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/ksnmartin)
