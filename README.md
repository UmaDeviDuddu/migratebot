# MigrateBot

A hands-on AI PM learning project. **Scenario:** Contoso, a generic enterprise customer, is migrating from Azure DevOps to GitHub. MigrateBot is a Q&A assistant built one small lab at a time, with an eval in every lab.

Built on Aakash Gupta's *Technical AI PM Interview Questions*, with one question a day and one lab a week.

**Data:** public documentation and synthetic data only.

## Structure
| Folder | Module | Labs |
|---|---|---|
| m1 | Most Common | l1 tokens/temperature · l2 context window · l3 LLM vs ML |
| m2 | LLM Fundamentals | l4 hallucination · l5 embeddings |
| m3 | Evals & Metrics | l6 golden set + judge · l7 confusion matrix · l8 model-swap regression |
| m4 | RAG & Context | l9 RAG basics · l10 break RAG |
| m5 | Tools, Agents & MCP | l11 one tool · l12 MCP |
| m6 | Orchestration & Routing | l13 router |
| m7 | System Design | l14 design for failure |
| m8 | Top Companies + Capstone | l15 capstone |

Shared: `evals/` (golden set), `data/` (docs snapshot, synthetic data). Each lab: `run.py` + `results.md`.

## Results
| Lab | What I measured | PM takeaway |
|---|---|---|
| l1 | _pending_ | _pending_ |

## Run a lab
```powershell
.venv\Scripts\Activate.ps1
pip install -r requirements.txt
python m1\l1\run.py
```
Requires `ANTHROPIC_API_KEY` set as a user environment variable. Never commit keys.
