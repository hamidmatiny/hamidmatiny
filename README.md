<div align="center">

# Mohammadreza Matiny

### AI Infrastructure & MLOps Engineer · LLM Serving · GPU Orchestration · Observability

[![Profile Views](https://komarev.com/ghpvc/?username=hamidmatiny&color=0e7490&style=flat-square)](https://github.com/hamidmatiny)
[![GitHub followers](https://img.shields.io/github/followers/hamidmatiny?style=flat-square&logo=github&color=0e7490)](https://github.com/hamidmatiny?tab=followers)

</div>

---

## About Me

### Hi, I'm Hamid 👋

ML/MLOps engineer focused on production-grade systems at the intersection of **LLM security & agentic infrastructure**, **computer vision**, and **geospatial ML** — with ~6 years building deep learning systems, scalable data pipelines, and cloud infrastructure (GCP/AWS). Currently at Torc Robotics on the Data Quality Assurance ML Pipeline.

**I build the full stack an organization needs to run AI systems in production.** Data foundations, LLM serving and GPU orchestration, and observability with incident response — end to end. I specialize in production-shaped platforms: unified serving contracts across heterogeneous backends, cost-safe GPU scheduling, contract-validated data pipelines, and evidence-grounded operational tooling. Success is measured by serving reliability, GPU cost-safety, and observability that closes the loop — not notebook demos.

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

#### Data Foundations & Systems

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Kafka%20%2F%20Redpanda-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Iceberg](https://img.shields.io/badge/Apache_Iceberg-1B4E6B?style=for-the-badge)
![PyArrow](https://img.shields.io/badge/PyArrow-FF6F00?style=for-the-badge)
![Parquet](https://img.shields.io/badge/Parquet-50C878?style=for-the-badge&logo=apache&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=for-the-badge&logo=opentelemetry&logoColor=white)

---

## Featured Architectural Builds

### Flagship · Sibling Platforms

### [Vulcan](https://github.com/hamidmatiny/vulcan) · v1.0.0

Production-shaped multi-backend LLM serving and GPU-orchestration platform. One unified serving contract across **vLLM**, **Triton Inference Server**, **Ray Serve**, **KServe**, and **BentoML** — with real GPU infra patterns (**MIG** partitioning, **Kueue** multi-tenant scheduling, **Karpenter** autoscaling) validated in CI and applied out-of-band so no GPUs are burned in the pipeline. Includes **SageMaker** / **Bedrock** integration, LoRA/PEFT fine-tuning, DVC data versioning, pluggable MLflow/W&B tracking, TensorRT-LLM templates, GPTQ/AWQ/FP8 quantization, a benchmark-driven routing gateway, and a **LangGraph** advisor agent that is tool-grounded and non-fabricating — CI asserts every number it states is backed by Prometheus/benchmark evidence from that run.

`LLM Serving` · `GPU Orchestration` · `Kueue` · `Karpenter` · `KServe` · `vLLM` · `Triton` · `Ray Serve` · `Quantization` · `MLOps`

---

### [Argus](https://github.com/hamidmatiny/argus) · Architecture & Foundation Phase

Vulcan's sibling platform: a unified fleet telemetry, data-quality, MLOps, and observability system currently in active architecture and early-build. Devices stream into a **Kafka/Redpanda** bus; **Ray** and **Flink** harden the data path; **Iceberg** + **Dagster** form the lakehouse and orchestration spine; drift-monitor, incident-engine, and **OpenTelemetry** close the operational loop — with an AI copilot for natural-language query/explain over platform data. Polyglot monorepo (**Go** for incident-engine / API gateway / CLI, **Python** for ingestion / drift / copilot, **TypeScript** for the dashboard, Terraform / Helm / ArgoCD for infra). Ambitious, well-designed scope — not yet feature-complete.

`Fleet Telemetry` · `Iceberg` · `Dagster` · `Kafka` · `Ray` · `Flink` · `OpenTelemetry` · `MLOps` · `Observability`

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
- See also **[hydra-data-factory](https://github.com/hamidmatiny/hydra-data-factory)** above — the AV telemetry lakehouse foundation behind Argus.

#### ⚙️ MLOps & Infrastructure

- **[task-master](https://github.com/hamidmatiny/task-master)** — Production FastAPI + PostgreSQL REST API with Docker and CI/CD.
- **[bert-inference](https://github.com/hamidmatiny/bert-inference)** — Containerized DistilBERT sentiment-analysis inference service.

---

## Engineering Philosophy

> Production-quality platforms are resource-efficient and evidence-grounded by design — not bolted on after the model works. I treat serving contracts, GPU cost-safety, and observability as first-class systems problems: unify backends, schedule capacity without burning money in CI, validate data at the gate, and close the loop with metrics that survive contact with production. Success is measured by **deployment metrics** — serving reliability, GPU utilization under multi-tenant constraints, pipeline acceptance rates, and operational signal fidelity — not theoretical benchmarks that never leave the lab.

---

📍 Fredericton, NB, Canada · 🌐 [hamidmatiny.github.io](https://hamidmatiny.github.io)
