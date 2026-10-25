### Kalala Gaël Kapia

MTech student in Information Technology at the Cape Peninsula University of Technology (CPUT), Cape Town, South Africa, with a background in cloud and network engineering (AWS, Azure).

#### Research

Intrusion detection models learn from labelled network traffic, and that is exactly the data organisations are least willing to share. Anonymised traces are not a safe answer, because they can often be re-identified.

My MTech study looks at synthetic traffic with a formal differential privacy guarantee. A network simulator, NS-3, is steered by private traffic through Private Evolution (the Sim-PE approach, using Microsoft's DPSDA library), so every synthetic flow comes from simulated protocol exchanges. The question is at which privacy budgets the resulting flows are still useful for training classifiers, judged on the CIC-DDoS2019 dataset. The study continues in 2027.

#### Selected work

- Kapia, K.G., Kabaso, B. & Hendricks, W. 2026. A systematic review of privacy-preserving synthetic network traffic generation for machine learning-based intrusion detection systems. In *Recent Advances in Information Systems (ICRAIS 2025)*, Progress in IS. Springer, 755–767. [doi:10.1007/978-3-032-14099-9_50](https://doi.org/10.1007/978-3-032-14099-9_50)
- [SIM_PE_NS-3](https://github.com/Gael-Majestic/SIM_PE_NS-3): code, experiment plans and design notes for the study. The link works from the day the repository is made public. The code was developed with AI assistance (Claude Code); the repository's `AI_USE.md` sets out what the assistant did, what I did, and how the output was checked.

#### Projects

- [network_asset_management](https://github.com/Gael-Majestic/network_asset_management): a REST API for tracking network assets and incidents. FastAPI, async SQLAlchemy and PostgreSQL, Alembic migrations, JWT authentication with roles, Docker Compose, and Terraform for an AWS development VM. CI checks the migrations against a real PostgreSQL and smoke-tests the running stack.
- [Business_Intelligence_Mini_Project](https://github.com/Gael-Majestic/Business_Intelligence_Mini_Project): an ETL pipeline from MySQL and MongoDB into a PostgreSQL star schema, with Metabase on top. CI runs the whole pipeline on Docker Compose and checks every warehouse table.

#### Interests

- Differential privacy and synthetic data
- Network security and intrusion detection
- Network simulation with NS-3
- Evaluating machine-learning models trained on synthetic data

#### Contact

ORCID: [https://orcid.org/0009-0001-3410-6319](https://orcid.org/0009-0001-3410-6319). Questions about the research code are welcome as issues in SIM_PE_NS-3.
