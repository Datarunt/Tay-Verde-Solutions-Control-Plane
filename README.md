## Control Plane: System context

This repository is part of a larger **reliability-first industrial IoT system**.
The system is intentionally split into four focused, frozen repositories.

**Explore the full system:**
1. [Edge-reliability](https://github.com/Datarunt/Tay-Verde-Solutions-Edge-Reliability)
2. [Data-ingestion](https://github.com/Datarunt/Tay-Verde-Solutions-Data-Ingestion)
3. [Control-plane](https://github.com/yourusername/risk-control-plane-airflow)
4. [ML-system](https://github.com/Datarunt/Tay-Verde-Solutions-ML-System)

Purpose: prove scheduling/orchestration, replayability, and operational ownership.

- docker compose up quickstart
- Where to set env vars
- How to trigger a run
- How to clear/replay
- How you prevent duplicates

Deliverables

- Airflow via Docker working
- Postgres connection configured
- Smoke test DAG
- Real DAG weekly schedule
- NOAA/USDA/incidents branches
- Idempotent rebuild behavior
- Replay historical weeks proof


---

**Previous:** See how data is ingested and validated → [Data-ingestion](https://github.com/Datarunt/Tay-Verde-Solutions-Data-Ingestion)

**Next:** See how ML is applied safely with abstention and fallback → [ML-system](https://github.com/Datarunt/Tay-Verde-Solutions-ML-System)
