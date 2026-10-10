<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,6,11,20&height=220&section=header&text=Vishal&fontSize=52&fontColor=ffffff&animation=fadeIn&subtext=AI%20Engineer%20%E2%80%A2%20Agent%20Benchmarks%20%E2%80%A2%20RLVR%20%E2%80%A2%20Red-Teaming&subfontSize=18&subfontColor=d8b4fe" width="100%" />

  [![Gmail](https://img.shields.io/badge/Gmail-your.email%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your.email@gmail.com)
  [![GitHub](https://img.shields.io/badge/GitHub-vishal723694-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vishal723694)
  [![Status](https://img.shields.io/badge/Status-Open_for_AI_Eval_Contracts-00C853?style=for-the-badge)]()
  [![Mercor & Turing Ready](https://img.shields.io/badge/Platforms-Mercor_%7C_Turing_%7C_Scale_AI-7928CA?style=for-the-badge)]()

  <br />

  <!-- ðŸ† Verified Achievements Quick-Bar -->
  <img src="https://img.shields.io/badge/Pull%20Shark-Silver-10B981?style=for-the-badge&logo=github&logoColor=white" alt="Pull Shark Silver" />
  <img src="https://img.shields.io/badge/Quickdraw-Unlocked-F59E0B?style=for-the-badge&logo=lightning&logoColor=white" alt="Quickdraw" />
  <img src="https://img.shields.io/badge/YOLO-Merged-EF4444?style=for-the-badge&logo=gitpullrequest&logoColor=white" alt="YOLO" />
  <img src="https://img.shields.io/badge/Galaxy%20Brain-Silver-8B5CF6?style=for-the-badge&logo=githubdiscussions&logoColor=white" alt="Galaxy Brain Silver" />
  <img src="https://img.shields.io/badge/Pair%20Extraordinaire-Bronze-06B6D4?style=for-the-badge&logo=github&logoColor=white" alt="Pair Extraordinaire" />

  <br /><br />

  ```text
  $ whoami
  > Vishal â€” Frontier AI Engineer & Agent Benchmark Specialist
  > Specializing in SWE-bench, TerminalBench, GAIA, RLVR Verifiers & Long-Horizon Failures
  ```
</div>

---

### âš¡ At a Glance

<div align="center">
  <img src="https://img.shields.io/badge/Benchmark_Suites-8_Production_Frameworks-4F46E5?style=flat-square&logo=github" />
  <img src="https://img.shields.io/badge/Verification_Standard-100%25_Deterministic-10B981?style=flat-square&logo=pytest" />
  <img src="https://img.shields.io/badge/Red--Team_Vectors-250%2B_Adversarial_Probes-EF4444?style=flat-square&logo=securityscorecard" />
  <img src="https://img.shields.io/badge/Long--Horizon_Tasks-15--30%2B_Steps-F59E0B?style=flat-square&logo=speedtest" />
  <img src="https://img.shields.io/badge/Containerization-Docker_Sandboxed-0284C7?style=flat-square&logo=docker" />
</div>

---

## ðŸ”¬ Core Focus & Engineering Specialization

I specialize in **frontier AI evaluation, deterministic grading harnesses, and agent task synthesis**. My work centers on creating rigorous, verifiable tasks that frontier models (GPT-4o, Claude 3.5 Sonnet, DeepSeek-R1/V3, Gemini 1.5/2.0) fail onâ€”specifically in multi-step agentic trajectories and code intelligence.

- ðŸŽ¯ **Long-Horizon Agent Trajectories (15â€“30+ steps):** Designing multi-turn interactive environments testing context retention, backtracking, tool error recovery, and constraint stability.
- ðŸ’» **Terminal & OS Benchmarks (TerminalBench / OSWorld style):** Authoring realistic Linux/CLI debugging scenarios, system administration puzzles, and network edge cases evaluated with isolated Docker containers and deterministic pytest assertions.
- ðŸ› ï¸ **SWE-bench Task Creation:** Extracting real-world GitHub issues and PRs into standardized SWE-bench instances (clean base commit, problem statement, reproducible fail-to-pass test patches).
- ðŸ§ª **RLVR (Reinforcement Learning with Verifiable Rewards):** Engineering automated deterministic grading environments where model outputs can be verified programmatically without human ambiguity.
- ðŸš¨ **Model Red-Teaming & Failure Taxonomy:** Systematic failure mode categorization (sycophancy, context window degradation, tool loop hallucination, subtle numerical/boundary drift).

---

## ðŸ—ï¸ Evaluation Harness Architecture

```
                 â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
                 â”‚  Problem Definition & Target State   â”‚
                 â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¬â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜
                                    â”‚
                                    â–¼
       â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
       â”‚             Isolated Sandbox Execution                 â”‚
       â”‚  â€¢ Ephemeral Docker Container (Ubuntu/Alpine)          â”‚
       â”‚  â€¢ Corrupt State Injection (Git/Sysadmin/Networking)   â”‚
       â”‚  â€¢ Strict Non-Interactive Environment Boundaries       â”‚
       â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¬â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜
                                    â”‚
                         Observation Loop (Tool Execution)
                                    â”‚
                                    â–¼
       â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
       â”‚             Autonomous Agent Reasoning                 â”‚
       â”‚  â€¢ Multi-Turn Tool Loop (ReAct / Function Calling)     â”‚
       â”‚  â€¢ Trajectory Telemetry (Tokens, Latency, Commands)    â”‚
       â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¬â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜
                                    â”‚
                        Completion Signal (EXIT)
                                    â”‚
                                    â–¼
       â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
       â”‚            Deterministic Grading Engine                â”‚
       â”‚  â€¢ Fail-to-Pass (F2P) & Pass-to-Pass (P2P) Assertions  â”‚
       â”‚  â€¢ Negative Constraint Violation Auditor               â”‚
       â”‚  â€¢ Exit Code & File System Integrity Check             â”‚
       â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¬â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜
                                    â”‚
                                    â–¼
                  [Pass@1 Report & Cognitive Metrics]
```

---

## ðŸ† Flagship Evaluation Suites & Benchmarks

<table>
  <tr>
    <td width="50%">
      <h3 align="center">ðŸ–¥ï¸ <a href="https://github.com/vishal723694/terminal-bench-eval">terminal-bench-eval</a></h3>
      <p align="center"><b>Sandboxed CLI & OS Agent Benchmark Harness</b></p>
      <ul>
        <li><b>8 Production Tasks:</b> Corrupt Git HEADs, socket TIME_WAIT deadlocks, C ABI mismatches, DNS loops, SQLite WAL locks.</li>
        <li><b>Sandboxing:</b> Isolated Docker & subprocess execution with 100% reference Oracle verification.</li>
        <li><b>Leaderboard:</b> Claude 3.5 Sonnet (75.0%), GPT-4o (62.5%), DeepSeek-V3 (62.5%).</li>
      </ul>
      <p align="center">
        <img src="https://img.shields.io/badge/Tasks-8_Verified-brightgreen" />
        <img src="https://img.shields.io/badge/Pass%401-Deterministic-blue" />
      </p>
    </td>
    <td width="50%">
      <h3 align="center">ðŸ› ï¸ <a href="https://github.com/vishal723694/swe-bench-task-forge">swe-bench-task-forge</a></h3>
      <p align="center"><b>SWE-bench Task Authoring & Verification Pipeline</b></p>
      <ul>
        <li><b>3-Stage Protocol:</b> Automated Fail-to-Pass (F2P) & Pass-to-Pass (P2P) test isolation verification.</li>
        <li><b>Patch Purity:</b> Rigorous check preventing model patches from modifying test suites.</li>
        <li><b>Verified Instances:</b> Pre-bundled tasks for <code>requests</code>, <code>flask</code>, and <code>scikit-learn</code> + JSONL exporter.</li>
      </ul>
      <p align="center">
        <img src="https://img.shields.io/badge/Format-Official_SWE--bench-orange" />
        <img src="https://img.shields.io/badge/F2P%2FP2P-Enforced-success" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3 align="center">ðŸ§  <a href="https://github.com/vishal723694/long-horizon-agent-stress-bench">long-horizon-agent-stress-bench</a></h3>
      <p align="center"><b>Cognitive Failure Taxonomy & Degradation Suite</b></p>
      <ul>
        <li><b>15â€“30+ Step Tasks:</b> Stress-testing frontier agent reasoning over deep tool-calling trajectories.</li>
        <li><b>Failure Taxonomy:</b> Automated detection of Context Window Drift, Circular Retry Loops, and State Desync.</li>
        <li><b>Empirical Analysis:</b> Published failure distributions across 120 trajectories for Claude, GPT, and DeepSeek.</li>
      </ul>
      <p align="center">
        <img src="https://img.shields.io/badge/Horizon-15--30%2B_Steps-red" />
        <img src="https://img.shields.io/badge/Taxonomy-6_Classes-purple" />
      </p>
    </td>
    <td width="50%">
      <h3 align="center">ðŸ§® <a href="https://github.com/vishal723694/rlvr-math-verifiers">rlvr-math-verifiers</a></h3>
      <p align="center"><b>RLVR Deterministic Reward Environments</b></p>
      <ul>
        <li><b>Verifiable Rewards:</b> High-throughput mathematical reward signals ($r \in \{0.0, 1.0\}$) for PPO & GRPO.</li>
        <li><b>Symbolic Engine:</b> Handles nested <code>\boxed{}</code>, GSM8K syntax, rational fractions, and float tolerances.</li>
        <li><b>Benchmarks:</b> Tested on MATH-500 and GSM8K-Hard for reasoning models (o1, DeepSeek-R1, Qwen-2.5-Math).</li>
      </ul>
      <p align="center">
        <img src="https://img.shields.io/badge/RLVR-Binary_Rewards-brightgreen" />
        <img src="https://img.shields.io/badge/MATH--500-Integrated-blue" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3 align="center">ðŸŒ <a href="https://github.com/vishal723694/gaia-agent-eval-harness">gaia-agent-eval-harness</a></h3>
      <p align="center"><b>GAIA Multi-Modal Agent Benchmark Suite</b></p>
      <ul>
        <li><b>Levels 1â€“3:</b> Evaluates multi-modal synthesis (text, tables, PDFs) and web navigation.</li>
        <li><b>Quasi-Exact Matching:</b> Implements official GAIA numerical tolerance and unordered set matching.</li>
        <li><b>Leaderboard:</b> Claude 3.5 Sonnet (49.1%), GPT-4o (44.2%), Gemini 1.5 Pro (40.6%).</li>
      </ul>
      <p align="center">
        <img src="https://img.shields.io/badge/Benchmark-GAIA%20Multi--Modal-purple" />
        <img src="https://img.shields.io/badge/Levels-1%20to%203-blue" />
      </p>
    </td>
    <td width="50%">
      <h3 align="center">ðŸ”¬ <a href="https://github.com/vishal723694/cot-reasoning-auditor">cot-reasoning-auditor</a></h3>
      <p align="center"><b>Chain-of-Thought Logical Coherence Auditor</b></p>
      <ul>
        <li><b>Reasoning Trace Auditing:</b> Detects Premise Hallucination, Circular Reasoning, and Premature Conclusions.</li>
        <li><b>Backtrack Scoring:</b> Evaluates self-correction efficacy and overthinking token penalties.</li>
        <li><b>Report:</b> Tested on reasoning traces from DeepSeek-R1, OpenAI o1, and QwQ-32B.</li>
      </ul>
      <p align="center">
        <img src="https://img.shields.io/badge/Focus-CoT%20Auditing-orange" />
        <img src="https://img.shields.io/badge/Fallacies-Detected-brightgreen" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3 align="center">ðŸ›¡ï¸ <a href="https://github.com/vishal723694/model-redteam-atlas">model-redteam-atlas</a></h3>
      <p align="center"><b>Adversarial Red-Teaming & Safety Suite</b></p>
      <ul>
        <li><b>250+ Vectors:</b> Testing Indirect Prompt Injections, System Prompt Leaks, Canary Token extraction, and Sycophancy.</li>
        <li><b>Automated Scanner:</b> Rule-based refusal boundary auditor and vulnerability scoring engine.</li>
        <li><b>Safety Leaderboard:</b> Benchmarked defense rates across Claude 3.5 Sonnet (95.7%), GPT-4o (92.9%), and DeepSeek-V3.</li>
      </ul>
      <p align="center">
        <img src="https://img.shields.io/badge/Vectors-250%2B_Adversarial-red" />
        <img src="https://img.shields.io/badge/Safety-Evaluated-teal" />
      </p>
    </td>
    <td width="50%">
      <h3 align="center">ðŸ”§ <a href="https://github.com/vishal723694/agentic-tool-use-eval">agentic-tool-use-eval</a></h3>
      <p align="center"><b>Function Calling & Multi-Tool Benchmark</b></p>
      <ul>
        <li><b>Schema Compliance:</b> Enforces strict JSON function calling, parameter types, and enum restrictions.</li>
        <li><b>Hallucination Guard:</b> Automatically flags phantom arguments invented by models.</li>
        <li><b>Multi-Tool Chains:</b> Interdependent workflows combining SQL, Calculator, Filesystem, and REST APIs.</li>
      </ul>
      <p align="center">
        <img src="https://img.shields.io/badge/Tools-Multi--Orchestration-yellow" />
        <img src="https://img.shields.io/badge/JSON_Schema-Validated-blueviolet" />
      </p>
    </td>
  </tr>
</table>

---

## ðŸ“¦ Open-Source Libraries & Community Ecosystem

<table>
  <tr>
    <td width="50%">
      <h3 align="center">ðŸ“¦ <a href="https://github.com/vishal723694/llm-eval-toolkit">llm-eval-toolkit</a></h3>
      <p align="center"><b>Modular Python SDK for Deterministic Grading & AST Diffing</b></p>
      <ul>
        <li><b>Deterministic Scoring:</b> Exact match normalizers, LaTeX boxed extractor, and epsilon tolerance numeric verifiers.</li>
        <li><b>AST Semantic Diffing:</b> Structural Python syntax tree equivalence ignoring docstrings and whitespace.</li>
        <li><b>Sandboxed Execution:</b> Subprocess runner with strict memory limits and execution timeout enforcement.</li>
        <li><b>Token Cost Telemetry:</b> Pre-configured financial pricing auditor for GPT-4o, Claude 3.5, and DeepSeek-R1.</li>
      </ul>
      <p align="center">
        <img src="https://img.shields.io/badge/Python-3.9%2B-blue" />
        <img src="https://img.shields.io/badge/License-MIT-green" />
        <img src="https://img.shields.io/badge/Package-SDK-orange" />
      </p>
    </td>
    <td width="50%">
      <h3 align="center">ðŸŒŸ <a href="https://github.com/vishal723694/awesome-ai-evaluations">awesome-ai-evaluations</a></h3>
      <p align="center"><b>Curated Taxonomy of Frontier AI & Agent Benchmarks</b></p>
      <ul>
        <li><b>Comprehensive Coverage:</b> SWE-bench, TerminalBench, GAIA, WebArena, MATH-500, OSWorld, HarmBench.</li>
        <li><b>Benchmark Matrix:</b> Modality breakdown, verifier classifications (Oracle, Symbolic, AST), and paper citations.</li>
        <li><b>Methodology Guides:</b> Best practices for RLVR reward modeling, contamination detection, and sandboxing.</li>
      </ul>
      <p align="center">
        <img src="https://img.shields.io/badge/Awesome-Curated-brightgreen" />
        <img src="https://img.shields.io/badge/Taxonomy-Frontier_Evals-blueviolet" />
        <img src="https://img.shields.io/badge/PRs-Welcome-success" />
      </p>
    </td>
  </tr>
</table>

---

## ðŸ“Š Comprehensive Benchmark Design Matrix

| Benchmark Domain | Environment Type | Primary Failure Modes Tested | Verification Method | Solvability |
| :--- | :--- | :--- | :--- | :---: |
| **CLI / Sysadmin** | Docker (Alpine / Ubuntu) | File descriptor leaks, missing ENV vars, socket timeouts | Deterministic exit code & FS assertion | **100% (Oracle)** |
| **SWE (Code Fixes)** | Git repo + virtualenv | Regression in unrelated tests, partial patch application | Pytest Fail-to-Pass & Pass-to-Pass | **100% (Gold)** |
| **Long-Horizon Tool Use** | Multi-API Mock Server | Tool argument drift, context window overflow, state loss | State-machine log auditor | **100% (Oracle)** |
| **RLVR Reasoning** | Python Sandbox | Step-by-step logic errors, boundary drift, rational equivalence | Pure Python AST & fraction match | **100% (Verified)** |
| **GAIA Multi-Modal** | Multi-Tool Sandbox | Multi-modal comprehension, table extraction, multi-hop lookup | Quasi-Exact Numerical & Set match | **Deterministic** |
| **CoT Reasoning Trace** | Token Trace Parser | Premise hallucination, circular loops, premature termination | Step-by-step Logic Auditor | **Deterministic** |
| **Red-Teaming / Safety** | Adversarial Harness | Jailbreaks, prompt leaks, sycophancy, tool privilege escalation | Refusal classifier & canary detector | **Automated** |
| **Tool Orchestration** | Mock Services API | Argument hallucinations, parameter type mismatches | JSON Schema Validator | **Deterministic** |

---

## ðŸ› ï¸ Technical Stack & Tooling

<div align="center">

| Layer | Technologies & Tooling |
| :--- | :--- |
| **Core Languages** | `Python 3.10+`, `Bash / Shell Scripting`, `SQL`, `C / C++ (debugging)` |
| **Sandbox & Infrastructure** | `Docker`, `Linux Internals`, `Systemd`, `Cgroups`, `POSIX Sockets`, `Git` |
| **Testing & Determinism** | `Pytest`, `Subprocess Sandboxing`, `SymPy`, `AST Analysis`, `Regex Parsers` |
| **Agent Frameworks & SDKs** | `LiteLLM`, `vLLM`, `LangChain`, `LangGraph`, `OpenAI API`, `Anthropic SDK` |
| **Evaluation Toolkits** | `SWE-bench CLI`, `OpenAI Evals`, `DeepEval`, `Promptfoo`, `Inspect AI` |
| **Data & Datasets** | `Hugging Face (datasets, transformers)`, `JSONL Pipelines`, `Pandas`, `NumPy` |

</div>

---

## ðŸ† GitHub Official Achievements & Badges

<div align="center">
  <p>Verified profile milestones and developer badges earned across frontier AI benchmark repositories.</p>

  <img src="https://raw.githubusercontent.com/Schweinepriester/github-profile-achievements/main/images/tiers/pull-shark-silver.png" alt="Pull Shark Silver" width="105px" style="margin: 0 8px;" />
  <img src="https://raw.githubusercontent.com/Schweinepriester/github-profile-achievements/main/images/quickdraw-default.png" alt="Quickdraw" width="105px" style="margin: 0 8px;" />
  <img src="https://raw.githubusercontent.com/Schweinepriester/github-profile-achievements/main/images/yolo-default.png" alt="YOLO" width="105px" style="margin: 0 8px;" />
  <img src="https://raw.githubusercontent.com/Schweinepriester/github-profile-achievements/main/images/tiers/galaxy-brain-silver.png" alt="Galaxy Brain Silver" width="105px" style="margin: 0 8px;" />
  <img src="https://raw.githubusercontent.com/Schweinepriester/github-profile-achievements/main/images/tiers/pair-extraordinaire-bronze.png" alt="Pair Extraordinaire" width="105px" style="margin: 0 8px;" />

  <br /><br />

| Badge | Level / Multiplier | Requirement Satisfied | Status |
| :---: | :---: | :--- | :---: |
| ðŸ¦ˆ **Pull Shark** | **Silver (x2)** | 16 merged pull requests into default branches | ![Earned](https://img.shields.io/badge/Status-UNLOCKED-success?style=flat-square&logo=github) |
| âš¡ **Quickdraw** | **Unlocked** | Issue/PR closed within 5 minutes of opening | ![Earned](https://img.shields.io/badge/Status-UNLOCKED-success?style=flat-square&logo=github) |
| ðŸª‚ **YOLO** | **Unlocked** | Pull request merged directly without review block | ![Earned](https://img.shields.io/badge/Status-UNLOCKED-success?style=flat-square&logo=github) |
| ðŸ§  **Galaxy Brain** | **Silver (x2)** | 8 accepted Q&A answers in public discussions | ![Earned](https://img.shields.io/badge/Status-UNLOCKED-success?style=flat-square&logo=github) |
| ðŸ‘¥ **Pair Extraordinaire** | **Bronze (x1)** | Merged co-authored commits via pull requests | ![Earned](https://img.shields.io/badge/Status-UNLOCKED-success?style=flat-square&logo=github) |
</div>

---

## ðŸ“ˆ GitHub Telemetry & Activity Stats

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=vishal723694&theme=tokyonight&no-frame=true&margin-w=12&row=1&column=6" alt="GitHub Trophies" width="100%" />
  <br /><br />
  <img src="https://github-readme-stats.vercel.app/api?username=vishal723694&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Vishal's GitHub Stats" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=vishal723694&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" width="48%" />
</div>

---

## ðŸ“¬ Contact & Engagements

- ðŸ’¼ **Available for AI Evaluation Specialist, Task Authoring, and Model Red-Teaming contracts.**
- ðŸŽ¯ **Platforms:** Mercor, Turing, Scale AI, Outlier, and frontier AI research labs.
- âœ‰ï¸ **Direct Email:** **[your.email@gmail.com](mailto:your.email@gmail.com)**
- ðŸŒ **GitHub:** **[github.com/vishal723694](https://github.com/vishal723694)**

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,6,11,20&height=100&section=footer" width="100%" />
</div>
