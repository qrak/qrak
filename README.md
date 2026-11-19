# qrak

I build small, verifiable systems — mostly Python, mostly around LLMs.

## Semantic Signal — an LLM trading agent that shows its work

On every closed candle it renders the price action into a 1920×1080 chart, sends the image with 65
Numba-compiled indicators, the news context and its own closed-trade memory to a multimodal model, then
passes the answer through deterministic risk gates before booking a paper trade. The prompt, the retrieved memory,
the verdict and the losses are public.

[Code](https://github.com/qrak/LLM_trader) · [Live dashboard](https://semanticsignal.qrak.org) · [Ledger](https://qrak.org/results/) · [How one cycle works](https://qrak.org/story/)

## Other work

- **[ti_numba](https://github.com/qrak/ti_numba)** — the indicator stack the bot calls every cycle: high-performance
  technical indicators in Numba JIT.
- **[candledownloader](https://github.com/qrak/candledownloader)** — OHLCV downloader with gap detection across exchanges.
- **[DiscordCryptoAnalyzer](https://github.com/qrak/DiscordCryptoAnalyzer)** — a Discord bot that answers with AI market analysis for any trading pair.
- **[dsh-mode-switcher](https://github.com/qrak/dsh-mode-switcher)** — a DeepSeek Harness plugin: Tab toggles
  Plan/Build, and each mode keeps its own model and reasoning preset across restarts.

Paper trading only. No fund management, no signal selling, and no performance claim that the public
ledger cannot reproduce.
