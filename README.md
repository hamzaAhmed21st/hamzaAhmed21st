# Hamza Ahmed

Computer Science student at the University of Minnesota Twin Cities, graduating May 2027. Based in Minneapolis and looking for new-grad software engineering opportunities.

My projects focus on Python backends, data processing, and the applications built around them.

## [HoopsLab — NBA shot-quality analytics](https://github.com/hamzaAhmed21st/hoopslab)

Explore a player's shots on an interactive court and compare actual shooting with model-estimated make probabilities.

- Imports six NBA seasons with source validation, transactional writes, and repeat-import detection.
- Separates model training, calibration, selection, and held-out evaluation by game and time.
- The published evaluation reports **0.6371 log loss versus 0.6428 for the logistic comparator**, across **218,701 held-out shots**.

Python · scikit-learn · FastAPI · PostgreSQL · React · TypeScript

[Dashboard](https://github.com/hamzaAhmed21st/hoopslab#dashboard-preview) · [Original results and provenance](https://github.com/hamzaAhmed21st/hoopslab/blob/main/docs/EVIDENCE.md#model-results-and-reproducibility) · [Code and tests](https://github.com/hamzaAhmed21st/hoopslab/blob/main/docs/EVIDENCE.md)

## [EventStream — asynchronous metrics pipeline](https://github.com/hamzaAhmed21st/eventstream)

Submit service metrics over HTTP, process them through Redis Streams, and view PostgreSQL-backed summaries in a dashboard.

- Uses stable event IDs, database uniqueness, and transactions to keep exact replays from creating duplicate rows.
- Distinguishes conflicting payloads from valid replays and acknowledges deliveries after checking the database outcome.
- Tests the pipeline with real Redis/PostgreSQL and a containerized ingestion-to-query smoke test.

Python · FastAPI · Redis Streams · PostgreSQL · React · Docker Compose

[Dashboard and local demo](https://github.com/hamzaAhmed21st/eventstream#dashboard) · [Implementation and tests](https://github.com/hamzaAhmed21st/eventstream/blob/main/docs/EVIDENCE.md)
