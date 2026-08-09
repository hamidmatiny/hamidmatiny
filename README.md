<div align="center">

# Mohammadreza Matiny

### AI Infrastructure & MLOps Engineer · LLM Serving · GPU Orchestration · Computer Vision · Observability

[![Profile Views](https://komarev.com/ghpvc/?username=hamidmatiny&color=0e7490&style=flat-square)](https://github.com/hamidmatiny)
[![GitHub followers](https://img.shields.io/github/followers/hamidmatiny?style=flat-square&logo=github&color=0e7490)](https://github.com/hamidmatiny?tab=followers)

</div>

---

## About Me

### Hi, I'm Hamid 👋

ML/MLOps engineer focused on production-grade systems at the intersection of **LLM security & agentic infrastructure**, **computer vision**, and **geospatial ML** — with 12 years building deep learning systems, scalable data pipelines, software backend systems, and cloud infrastructure (GCP/AWS). That work spans **30 public repositories**, including **5 production-shaped platforms** with real CI/CD, Terraform-provisioned infrastructure, and tagged releases rather than perpetual drafts.

**I build the full stack an organization needs to run AI systems in production.** Data foundations, LLM serving and GPU orchestration, computer-vision pipelines, and observability with incident response — end to end. Where it matters, the numbers are measured, not estimated: one lakehouse pipeline processed **42,972 records at a 91.8% acceptance rate with zero post-gate rejections**; another platform runs **45 Docker Compose services** behind **41 automated test files** and **6 active CI workflows**; a third ships **17 services** behind a single multi-warehouse activation contract. Success is serving reliability, GPU cost-safety, and pipeline acceptance rates — not notebook demos.

---

## Core Expertise

#### LLM Serving & Inference

![vLLM](https://img.shields.io/badge/vLLM-000000?style=for-the-badge)
![Triton](https://img.shields.io/badge/Triton_Inference_Server-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Ray Serve](https://img.shields.io/badge/Ray_Serve-028CF0?style=for-the-badge)
![KServe](https://img.shields.io/badge/KServe-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![BentoML](https://img.shields.io/badge/BentoML-000000?style=for-the-badge)
![TensorRT-LLM](https://img.shields.io/badge/TensorRT--LLM-76B900?style=for-the-badge&logo=nvidia&logoColor=white)

#### GPU Orchestration & Cloud

![Kueue](https://img.shields.io/badge/Kueue-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Karpenter](https://img.shields.io/badge/Karpenter-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![MIG](https://img.shields.io/badge/MIG_Partitioning-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![SageMaker](https://img.shields.io/badge/SageMaker-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Bedrock](https://img.shields.io/badge/Bedrock-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)

#### MLOps & Experiment Tracking

![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![DVC](https://img.shields.io/badge/DVC-13ADC7?style=for-the-badge)
![Weights & Biases](https://img.shields.io/badge/Weights_%26_Biases-FFBE00?style=for-the-badge&logo=weightsandbiases&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/CI%2FCD-GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)

#### Computer Vision & Perception

![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX_Runtime-005CED?style=for-the-badge&logo=onnx&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-111F68?style=for-the-badge)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![PyTorch Lightning](https://img.shields.io/badge/PyTorch_Lightning-792EE5?style=for-the-badge&logo=pytorchlightning&logoColor=white)

#### Data Foundations & Systems

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Kafka%20%2F%20Redpanda-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Iceberg](https://img.shields.io/badge/Apache_Iceberg-1B4E6B?style=for-the-badge)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![PyArrow](https://img.shields.io/badge/PyArrow-FF6F00?style=for-the-badge)
![Parquet](https://img.shields.io/badge/Parquet-50C878?style=for-the-badge&logo=apache&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=for-the-badge&logo=opentelemetry&logoColor=white)

---

## Featured Architectural Builds

### Flagship Platforms

### [Vulcan](https://github.com/hamidmatiny/Vulcan) · v1.2.0

Production-shaped multi-backend LLM serving and GPU-orchestration platform. One unified serving contract across **vLLM**, **Triton Inference Server**, **Ray Serve**, **KServe**, and **BentoML** — with real GPU infra patterns (**MIG** partitioning, **Kueue** multi-tenant scheduling, **Karpenter** autoscaling) validated in CI so no GPUs are burned in the pipeline. Tagged v1.2.0 across 22 phases: **SageMaker**/**Bedrock** integration, LoRA/PEFT fine-tuning, DVC data versioning, pluggable MLflow/W&B tracking, TensorRT-LLM templates, GPTQ/AWQ/FP8 quantization, cost-per-token tracking, and a **LangGraph** advisor agent that is tool-grounded and non-fabricating — CI asserts every number it states is backed by Prometheus/benchmark evidence from that run.

`LLM Serving` · `GPU Orchestration` · `Kueue` · `Karpenter` · `KServe` · `vLLM` · `Triton` · `Ray Serve` · `Quantization` · `MLOps`

---

### [Argus](https://github.com/hamidmatiny/Argus) · v1.0.0

Vulcan's sibling platform: a production-shaped fleet telemetry, data-quality, MLOps, and observability system. Tagged v1.0.0, with its own CHANGELOG calling it the "first production-shaped release" across Phases 0–15 — a **45-service** Docker Compose stack, **41 test files** (including Kafka integration tests), and **6 active CI workflows**. Devices stream into a **Kafka/Redpanda** bus; **Ray** and **Flink** harden the data path; **Iceberg** + **Trino** form the lakehouse; **Dagster**/MLflow orchestrate; drift-monitor, an **OPA**-backed incident-engine, and **OpenTelemetry** close the operational loop; a read-only, Qdrant-RAG AI copilot ships with its own eval harness. Polyglot monorepo (**Go** for incident-engine / API gateway / CLI, **Python** for ingestion / drift / copilot, **Next.js** dashboard, Terraform / Helm / ArgoCD for infra).

`Fleet Telemetry` · `Iceberg` · `Trino` · `Dagster` · `Kafka` · `Ray` · `Flink` · `OPA` · `OpenTelemetry`

---

### [PRISM](https://github.com/hamidmatiny/PRISM) · v1.2.0

Multi-warehouse fleet-intelligence platform. Tagged v1.2.0, with all **20 phases (0–19) complete** — including a golden-path chaos end-to-end test run against the live Compose stack. Camera/sensor ingest splits into a **PySpark** medallion lakehouse (bronze → silver → gold, **dbt**-modeled) and an **OpenCV**/**ONNX** YOLO-family CV service that routes low-confidence findings to a **Django** control-plane review queue. Gold data fans out through one activation contract to **Redshift** and **Snowflake**, mirrors to **Databricks**/Azure ADLS for disaster recovery, and feeds a **Vue 3 + Three.js** digital-twin cockpit; a per-asset circuit-breaker incident-engine runs OPA/Rego trip policies; a tool-grounded AI copilot answers only from evidence it can cite. **17-service** Docker Compose stack, **19 test files**, 2 CI workflows.

`PySpark` · `Databricks` · `dbt` · `OpenCV` · `ONNX` · `Django` · `Vue` · `Snowflake` · `Redshift`

---

### [FORGE](https://github.com/hamidmatiny/FORGE) · v0.2.0

Offline AV perception & auto-labeling platform. Tagged v0.2.0, with all **11 phases complete**. An 8-stage `forge` CLI pipeline runs end to end locally: ingest (nuScenes → Parquet lake) → detect2d (Faster R-CNN) and detect3d (PointNet-style) → track (SORT: Kalman + Hungarian IoU) → fuse (calibrated sensor fusion) → label (active learning / pseudo-labeling) → evaluate (BEV distance, mAP against held-out ground truth) → curate (LanceDB dedup) → visualize (rerun.io / Foxglove MCAP). A parallel cloud path (S3 → Lambda → SQS → DynamoDB → EventBridge → Step Functions → ECS Fargate → Glue → Athena, 11 tables) is Terraform-defined and CI-verified — deliberately never applied against live AWS, the same cost-safety policy as Vulcan, PRISM, and hydra-data-factory. Detection heads are documented honestly as randomly-initialized research baselines, not tuned models.

`Computer Vision` · `PyTorch Lightning` · `Sensor Fusion` · `Ray` · `LanceDB` · `Terraform`

---

### Foundation

### [hydra-data-factory](https://github.com/hamidmatiny/hydra-data-factory)

Production-validated AV telemetry lakehouse — the data/lakehouse foundation Argus grew out of. Mock fleet telemetry simulator, two-layer **Pydantic + Pandera** contract validation with dead-letter-queue isolation, **Terraform**-provisioned S3 + Glue + IAM, and **PyArrow/Parquet** columnar storage with Hive partitioning, deployed via Docker Compose. Verified production-run metrics: **42,972** records ingested, **91.8%** acceptance rate, **0%** post-gate contract rejections.

`Data Contracts` · `Pandera` · `PyArrow` · `Parquet` · `Terraform` · `S3` · `Glue` · `Docker Compose`

---

## Also Building

#### 🛡️ LLM Security & Agentic Systems

- **[aegis](https://github.com/hamidmatiny/aegis)** — Defense-in-depth security gateway for LLM apps and agents: input/output threat detection, policy-as-code (CEL), tool/MCP permission gating with taint tracking, continuous red-teaming, Ed25519-signed tamper-evident audit trail, and drop-in SDKs.
- **[AegisFlow](https://github.com/hamidmatiny/AegisFlow)** — Autonomous multi-agent incident response engine (Temporal, PydanticAI, OpenTelemetry) that triages observability alerts and plans mitigations.
- **[smart-assistant](https://github.com/hamidmatiny/smart-assistant)** — Personal knowledge assistant and workflow agent.
- **[edgevision](https://github.com/hamidmatiny/edgevision)** — Edge CV security/anomaly detection with YOLO + ByteTrack.

#### 🌲 Geospatial ML

- **[terra-OBIA](https://github.com/hamidmatiny/terra-OBIA)** — Object-Based Image Analysis platform for forestry stand delineation, wetland classification, and land cover mapping at province scale.
- **[terra-obia-etl](https://github.com/hamidmatiny/terra-obia-etl)** — ETL pipeline harmonizing GeoNB/GNB Open Data into labeled training polygons.

#### 🚗 Computer Vision & Autonomous Systems

- **[NEXUS-CV](https://github.com/hamidmatiny/NEXUS-CV)** — Real-time multi-modal computer vision platform with live observability and full MLOps lifecycle.
- **[multi-modal-od](https://github.com/hamidmatiny/multi-modal-od)** — Sensor-fusion object detection (radar, LiDAR, camera) for autonomous driving.
- **[sentinel-ray](https://github.com/hamidmatiny/sentinel-ray)** — Distributed camera telemetry ingestion with Ray, statistical drift detection, and automated incident orchestration.
- **[vanguard-telemetry-monitor](https://github.com/hamidmatiny/vanguard-telemetry-monitor)** — Fleet telemetry simulation and observability platform with production-like anomaly injection.
- **[vit-fastapi-cloud-deploy](https://github.com/hamidmatiny/vit-fastapi-cloud-deploy)** — FastAPI image classification service, evolved into a cloud-deployed Vision Transformer pipeline.
- **[cuda-optimization](https://github.com/hamidmatiny/cuda-optimization)** — Deep learning optimization guide adapted for Apple Metal Performance Shaders.

#### ⚙️ MLOps & Infrastructure

- **[task-master](https://github.com/hamidmatiny/task-master)** — Production FastAPI + PostgreSQL REST API with Docker and CI/CD.
- **[bert-inference](https://github.com/hamidmatiny/bert-inference)** — Containerized DistilBERT sentiment-analysis inference service.

---

## Engineering Philosophy

> Production-quality platforms are resource-efficient and evidence-grounded by design — not bolted on after the model works. I treat serving contracts, GPU cost-safety, and observability as first-class systems problems: unify backends, schedule capacity without burning money in CI, validate data at the gate, and close the loop with metrics that survive contact with production. Success is measured by **deployment metrics** — serving reliability, GPU utilization under multi-tenant constraints, pipeline acceptance rates, and operational signal fidelity — not theoretical benchmarks that never leave the lab.

---

📍 Fredericton, NB, Canada · 🌐 [hamidmatiny.github.io](https://hamidmatiny.github.io)
