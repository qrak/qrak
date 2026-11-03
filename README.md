# qrak

I build small, verifiable systems — mostly Python, mostly around LLMs.

## Semantic Signal — an LLM trading agent that shows its work

Every four hours it renders the candles into a 1920×1080 chart, sends the image with 79 Numba-compiled
indicators, the news context and its own closed-trade memory to a multimodal model, then passes the
answer through deterministic risk gates before booking a paper trade. The prompt, the retrieved memory,
the verdict and the losses are public.

[Code](https://github.com/qrak/LLM_trader) · [Live dashboard](https://semanticsignal.qrak.org) · [Ledger](https://qrak.org/results/) · [How one cycle works](https://qrak.org/story/)

## Around it

- **[ti_numba](https://github.com/qrak/ti_numba)** — 79 technical indicators in Numba JIT, the ones the bot calls every cycle.
- **[candledownloader](https://github.com/qrak/candledownloader)** — OHLCV downloader with gap detection across exchanges.
- **[telegram-commandcode](https://github.com/qrak/telegram-commandcode)** — MCP server that lets a coding agent send Telegram messages and files.

Paper trading only. No fund management, no signal selling, and no performance claim that the public
ledger cannot reproduce.
