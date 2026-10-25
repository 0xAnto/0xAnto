<h1 align="center">Hi, I'm Anto</h1>

<p align="center">
  <strong>I build AI systems and on-chain trading infrastructure.</strong><br>
  Head of Engineering at <a href="https://xyra.trade">Xyra Labs</a> (formerly Kana Labs) · Chennai, India
</p>

<p align="center">
  <a href="https://0xanto.xyz"><img src="https://img.shields.io/badge/web-0xanto.xyz-111111?style=flat-square" alt="Website"></a>
  <a href="https://www.linkedin.com/in/0xanto"><img src="https://img.shields.io/badge/linkedin-0xanto-0A66C2?style=flat-square" alt="LinkedIn"></a>
  <a href="https://x.com/0xAnto"><img src="https://img.shields.io/badge/x-@0xAnto-111111?style=flat-square&logo=x&logoColor=white" alt="X"></a>
  <a href="mailto:antonyranjith17@gmail.com"><img src="https://img.shields.io/badge/email-say%20hi-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://0xanto.xyz/resume.pdf"><img src="https://img.shields.io/badge/resume-pdf-555555?style=flat-square" alt="Resume"></a>
</p>

<div align="center">

| **$2B+** | **$1B+** | **370M+** | **14+** |
| :---: | :---: | :---: | :---: |
| lifetime perps volume<br><sub>xyra.trade</sub> | swap volume<br><sub>Kana aggregator</sub> | sponsored transactions<br><sub>Kana Paymaster</sub> | chains supported<br><sub>ERC-4337 smart-wallet SDK</sub> |

</div>

I build systems where mistakes are expensive. Trading infrastructure taught me to budget latency and memory, measure honestly, and design for the failure case. I bring the same habits to AI work: speech models, evals, on-device inference, and agent-native engineering.

### Right now

- Leading a next-generation, high-performance exchange engine in **Rust** at Xyra Labs
- Real-time detection of AI voice agents on live Zoom, Meet and Teams calls (private beta)
- Open speech recognition for Tamil, and small models that follow rules they've never seen
- Running my team agent-native: Claude Code and Codex in parallel tracks, with automated review → fix → re-review loops before a human signs off

---

### AI work

| Project | What it is | Stack |
| --- | --- | --- |
| [**eg2-tamil**](https://github.com/0xAnto/eg2-tamil) | Open Tamil speech recognition on the EmbeddingGemma 2 audio encoder. Trained on ~462 h of public speech with one GPU: **31.6% WER** on FLEURS Tamil vs. 48.6% for Whisper large-v3 (approximate comparison). | Python · PyTorch · CTC |
| [**CRUX**](https://github.com/0xAnto/crux) | Open research: can a 17–30M-parameter decision model follow rules it has never seen? Four architectures under a pre-registered eval protocol. | Python · PyTorch · hypernetworks |
| [**OpenVox**](https://github.com/0xAnto/openvox) | Private, on-device dictation for macOS. Hold a key, speak, and the text lands at your cursor. Audio never leaves the machine. [Download →](https://github.com/0xAnto/openvox/releases/latest) | Swift · MLX · ONNX |
| **AI-voice detection** | Is the other party on this call a human or an AI agent? Real-time scoring while the call is still going. Private. | Python · PyTorch · speech models |

### Agent tooling

| Project | What it is | Stack |
| --- | --- | --- |
| [**srch**](https://github.com/0xAnto/srch) | Full-text search across Claude Code, Codex and Cursor conversation histories. Trigram index, memory-mapped, sub-millisecond queries. | Rust |
| [**mem0**](https://github.com/0xAnto/Mem0) | Local-first terminal memory for developers and AI agents. Under 20 ms capture, automatic secret redaction, error fingerprinting. | Go |
| [**loom**](https://github.com/0xAnto/loom) | Skill framework for coding agents: adaptive skill activation and subagent delegation for Claude Code, Codex and Gemini CLI. | Agents |
| [**anto-claude-skills**](https://github.com/0xAnto/anto-claude-skills) | My Claude Code skills and agents, including the critical code reviewer behind my review loops. | Claude Code |

### On-chain systems

| Project | What it is | Stack |
| --- | --- | --- |
| [**xyra.trade**](https://xyra.trade) | Fully on-chain order-book perps exchange on Aptos, **$2B+** lifetime volume. I owned the core protocol: clearinghouse, positions, liquidations, funding, TP/SL, market modes and the Pyth oracle integration, plus keepers, bots and the public SDK [`@xyra-trade/perps`](https://www.npmjs.com/package/@xyra-trade/perps). | Move · Rust · TypeScript |
| [**Kana Paymaster**](https://medium.com/xyra-labs/kana-paymaster-on-aptos-e414a37111d6) | Gas sponsorship on Aptos via fee-payer transactions (AIP-39), **370M+** sponsored transactions. SDK: [`@kanalabs/paymaster-sdk`](https://www.npmjs.com/package/@kanalabs/paymaster-sdk). | TypeScript · Kubernetes |
| **Cross-chain swap aggregator** | Any-to-any token swaps across EVM and non-EVM chains, **$1B+** volume. | Move · Node.js · bridges |
| **ERC-4337 smart-wallet SDK** | Smart-account SDK for account abstraction across **14+** EVM chains. | TypeScript |

<details>
<summary><strong>More open source</strong></summary>
<br>

| Project | What it is | Stack |
| --- | --- | --- |
| [**move-integers**](https://github.com/0xAnto/move-integers) | Signed integer types from i8 to i256 for Move, 100% test coverage. Used in my perps contracts. | Move |
| [**aptos-tokenized-vault**](https://github.com/0xAnto/aptos-tokenized-vault) | ERC-4626-style tokenized vault for Aptos Fungible Assets. | Move |
| [**aptos-wallet-api**](https://github.com/0xAnto/aptos-wallet-api) | Lightweight Aptos wallet client on npm. | JavaScript |
| [**3dbook**](https://github.com/0xAnto/3dbook) | Real-time 3D order-book visualization in WebGL, fed by an L2 WebSocket. | TypeScript · WebGL |
| [**lighTUI**](https://github.com/0xAnto/lighTUI) | Terminal UI library in C11. Zero dependencies, zero malloc, a single `write()` per frame. | C |
| [**Arty**](https://github.com/0xAnto/Arty) | Native macOS terminal with an Arc-style sidebar, persistent sessions and a Metal renderer. | Swift · Metal |
| [**Serein**](https://github.com/0xAnto/serein) | Offline ambient sound mixer for Android. No ads, accounts or analytics. | Java |

</details>

---

### Tech

<p>
  <img src="https://skillicons.dev/icons?i=py,rust,ts,solidity,swift,go,c,pytorch&perline=8" alt="Python, Rust, TypeScript, Solidity, Swift, Go, C, PyTorch"><br>
  <img src="https://skillicons.dev/icons?i=nodejs,postgres,redis,prisma,docker,kubernetes,githubactions&perline=8" alt="Node.js, PostgreSQL, Redis, Prisma, Docker, Kubernetes, GitHub Actions">
</p>

**Also:** Move (Aptos, Sui) · MLX · ONNX · Foundry · Hardhat · Pyth · ERC-4337 · Claude Code · Codex

---

<p align="center">
  Open to select <strong>AI engineering</strong> and <strong>web3</strong> roles.<br>
  <a href="https://0xanto.xyz">0xanto.xyz</a> · <a href="mailto:antonyranjith17@gmail.com">antonyranjith17@gmail.com</a>
</p>
