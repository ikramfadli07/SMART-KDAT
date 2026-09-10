SMART KDAT v7 — AI Hybrid

Architecture:
1. Local JSON is the source of truth.
2. SMART Data Engine calculates/searches the actual records.
3. WebLLM runs an open-source LLM in the user's browser (WebGPU) to understand/explain the structured result.
4. If AI/WebGPU is unavailable, the factual SMART Data Engine still works.

Requirements for AI mode:
- Recent Chromium browser with WebGPU support.
- HTTPS hosting such as GitHub Pages.
- First AI use downloads the browser model, so it can take time and use significant device resources.

Files must be uploaded to the ROOT of the GitHub repository.
