# Infra charts and manifests live here.

Current infra components planned here include:

* Ollama as the in-house LLM runtime

Ollama decisions:

* managed by Helm and Argo CD
* GPU-pinned single replica
* PVC-backed model cache
* internal ClusterIP service only
* default model: `llama3.1:8b`

