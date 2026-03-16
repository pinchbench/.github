# 🦀 PinchBench

**Real-world benchmarks for AI coding agents**

PinchBench measures how well LLM models perform as the brain of an [OpenClaw](https://github.com/openclaw/openclaw) agent. Instead of synthetic tests, we throw real tasks at agents: scheduling meetings, writing code, triaging email, researching topics, and managing files.

### 📊 [View the Leaderboard →](https://pinchbench.com)

---

### Repositories

| Repo | Description |
|------|-------------|
| [**skill**](https://github.com/pinchbench/skill) | Benchmark runner and task definitions — run it yourself |
| [**leaderboard**](https://github.com/pinchbench/leaderboard) | The pinchbench.com leaderboard frontend |
| [**api**](https://github.com/pinchbench/api) | The public PinchBench API at api.pinchbench.com |
| [**scripts**](https://github.com/pinchbench/scripts) | The offical PinchBench run automation with `default_models.yml`  |

---

### Run the Benchmark

```bash
git clone https://github.com/pinchbench/skill.git
cd skill
./scripts/run.sh --model anthropic/claude-sonnet-4
```

Results upload to the public leaderboard. [Get started →](https://github.com/pinchbench/skill)

---

*Claw-some AI agent testing. Made with 🦀 by the humans at https://kilo.ai* 🦞
