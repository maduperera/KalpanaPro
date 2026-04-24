Vijñāna AI | Kalpanā
Welcome to the public testing prototype of the Kalpanā Architecture by Vijñāna AI.
This repository hosts a Progressive Web App (PWA) demonstrating our proprietary $O(1)$ knowledge retrieval engine. It operates completely air-gapped on the edge, merging Holographic Hilbert Memory (HHM) with local quantized LLMs via WebGPU.
⚠️ Legal Notice & Terms of Use
© 2026 Vijñāna AI. All Rights Reserved.
This repository does not operate under an open-source license. The software, algorithms, and methodologies (including the Kalpanā architecture and HHM implementation) are proprietary and highly confidential.
By accessing, running, or interacting with this repository and its associated web deployment, you agree to the following terms:
No Reverse Engineering: You may not decompile, reverse engineer, disassemble, or attempt to derive the source code of the underlying algorithms, including attempting to decode or de-obfuscate any linked JavaScript files.
No Distribution: You may not copy, fork, modify, or distribute this codebase, in whole or in part, without explicit written consent from Vijñāna AI.
Intellectual Property: All patents, copyrights, and intellectual property rights related to the Kalpanā architecture remain the exclusive property of Vijñāna AI.
---
🚀 The Prototype
Traditional Retrieval-Augmented Generation (RAG) relies on cloud servers, vector databases, and massive Key-Value (KV) caches. This creates a "memory wall," driving up server costs and violating enterprise data privacy.
The Kalpanā Edge Prototype eliminates the cloud entirely.
How It Works
Zero-Knowledge Parsing: When you upload a massive PDF, it is processed locally in your browser. The document never leaves your RAM. No network requests are made.
Holographic Compression: Text chunks are embedded via ONNX and written into a continuous, constant-memory holographic state using mathematical wave interference ($O(1)$ complexity).
Local Edge Inference: When queried, Kalpanā isolates the precise context vectors and feeds them to a quantized, air-gapped Qwen 1.5B LLM running directly on your local GPU via WebGPU.
How to Use the App
Navigate to the live GitHub Pages link (provided by the repository owner).
Wait for the initial loading sequence. Your browser will securely download and cache the ONNX embedder and the WebLLM weights via IndexedDB. (Note: This requires an initial download of ~1.5GB. Subsequent visits will load instantly).
Once initialized, click Install in your browser's address bar to save the PWA to your desktop.
Open the standalone app, drag a document into the upload zone, and query your data with absolute privacy.
---
For business inquiries or technical deep dives regarding the architecture, please contact the founder.
