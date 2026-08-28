# flipslidersand — Forward Deployed Engineer / Applied AI Engineer

**花島 祐輝 | Yuki Hanajima**

> 業務課題の発見から設計・実装・本番運用まで一気通貫で担当するエンジニア。  
> I turn ambiguous operational problems into production systems — from requirements through deployment and operations.

---

## Production Work / 現職プロジェクト

### Internal Business Platform — グーネットエクスチェンジ (2026–Present)

中古車輸出業向け業務管理システムの内製化。業務観察・要件定義から本番稼働まで単独で担当。  
Built and shipped an internal business management system from scratch as a sole engineer.

- **Stack**: Go · React · TypeScript · PostgreSQL · GCP (Cloud Run / Cloud SQL / Vertex AI / Pub/Sub) · Kubernetes · Argo CD · OpenTelemetry · Grafana
- **Velocity**: 75 working days · 153 PRs · production cutover in ~4 months
- **Impact**: ¥8–15M cost avoidance vs. external development estimate · 2-day MVP during a data-leak incident

---

## Open Source & R&D

| Project | Description | Stack |
|---------|-------------|-------|
| [marketplace-lakehouse-reference](https://github.com/flipslidersand/marketplace-lakehouse-reference) | Medallion Architecture data pipeline (Bronze→Silver→Gold) · 31 tests | PySpark · Delta Lake · Streamlit |
| [context-smith](https://github.com/flipslidersand/context-smith) | AI context compiler CLI — extracts task-relevant code for LLMs · v0.1.0 | Rust · BM25 · Tree-sitter |
| [fluxion](https://github.com/flipslidersand/fluxion) | Distributed WebAssembly job scheduler with DAG execution | Rust · WebAssembly · MCP |
| [dataguard-rail](https://github.com/flipslidersand/dataguard-rail) | Data quality & lineage platform · 6 phases complete | Rust · Go · OpenTelemetry |
| [stream-rail](https://github.com/flipslidersand/stream-rail) | Stream processing engine with tumbling windows & watermarks | Go · BadgerDB · NATS |
| [wasm-runtime](https://github.com/flipslidersand/wasm-runtime) | WebAssembly binary parser · 136 tests · all sections (0–12) | Rust |
| [reasoning-mesh](https://github.com/flipslidersand-labs/reasoning-mesh) | RAG-LLM orchestration — router + knowledge engine | Go · Qdrant · Ollama |
| [oss-radar](https://github.com/flipslidersand-labs/oss-radar) | OSS trending collector with semantic search · MINIPC cron | Python · Qdrant |
| [scam-alert](https://github.com/flipslidersand/scam-alert) | OCR-based scam pattern detector · Cloud Run | Go · GCP Vision API · React |
| [city-score](https://github.com/flipslidersand/city-score) | City livability scoring with original indicators · e-Stat API | Python · Streamlit |
| [loopnest-core](https://github.com/flipslidersand-labs/loopnest-core) | BtoB Quote-to-Billing platform (M01–M14) | TypeScript · PostgreSQL |
| [phone-guard](https://github.com/flipslidersand/phone-guard) | Fixed-line scam guard — ESP32 FSK decode + LINE notification on unknown numbers | Go · GCP · ESP32 |
| [pachinko-analysis](https://github.com/flipslidersand/pachinko-analysis) | Pachinko/slot prediction system with SHAP feature importance & FastAPI | Python · SHAP · FastAPI |
| [doc-ingest](https://github.com/flipslidersand-labs/doc-ingest) | Document ingestion pipeline — external API docs / arxiv papers → Qdrant | Python · Qdrant |

▶️ **[Portfolio Board](https://github.com/users/flipslidersand/projects/11)** — every card links to Issues ↔ PRs ↔ commits

---

## Tech Stack

```text
Primary / 現職使用:
  Go · TypeScript · React · Python · PostgreSQL
  GCP (Cloud Run · Cloud SQL · Vertex AI · Pub/Sub · Secret Manager)
  Docker · Kubernetes · Argo CD · GitHub Actions
  OpenTelemetry · Prometheus · Grafana
  Claude · Gemini · Vertex AI · RAG · Vector Search

R&D / 個人開発:
  Rust · WebAssembly · PySpark · Delta Lake
  Qdrant · BadgerDB · NATS · Terraform · k3s
```

---

## Writing / 発信

**Zenn** (Japanese · 46 articles): [zenn.dev/flipslidersand](https://zenn.dev/flipslidersand)  
技術記事・AI-native 開発フロー・OSS 実装記録

**Dev.to** (English · 4 articles): [dev.to/flipslidersand](https://dev.to/flipslidersand)
- [I Thought I Used 1 Billion Tokens in Claude Code Last Week. Turns Out 97% Was Cache.](https://dev.to/flipslidersand)
- [AI-Native Development Flow: 4 Months, 153 PRs, Production](https://dev.to/flipslidersand/ai-native-development-flow-4-months-153-prs-production-10j3)
- [The AI Is Fast. The Decisions Are Mine.](https://dev.to/flipslidersand/the-ai-is-fast-the-decisions-are-mine-35p5)

---

## Contact

- **Zenn**: [zenn.dev/flipslidersand](https://zenn.dev/flipslidersand)
- **Email**: yukihanajob2025@gmail.com
- **Open to**: FDE / Applied AI Engineer / Solution Architect roles · Remote preferred · Relocation possible
