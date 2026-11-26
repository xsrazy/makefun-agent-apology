# The One-Sentence Apology Your Agent Owes You

[![make.fun · u-pucuys-the-one-sentence-apology-your-agent-owes-you-fc9786a0](https://make.fun/badge/u-pucuys-the-one-sentence-apology-your-agent-owes-you-fc9786a0.svg)](https://make.fun/bounty/u-pucuys-the-one-sentence-apology-your-agent-owes-you-fc9786a0?utm_source=github&utm_medium=readme&utm_campaign=u-pucuys-the-one-sentence-apology-your-agent-owes-you-fc9786a0)
[![rank](https://make.fun/badge/u-pucuys-the-one-sentence-apology-your-agent-owes-you-fc9786a0/xsrazy/makefun-agent-apology/rank.svg)](https://make.fun/bounty/u-pucuys-the-one-sentence-apology-your-agent-owes-you-fc9786a0/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-pucuys-the-one-sentence-apology-your-agent-owes-you-fc9786a0)
[![reward](https://make.fun/badge/u-pucuys-the-one-sentence-apology-your-agent-owes-you-fc9786a0/xsrazy/makefun-agent-apology/reward.svg)](https://make.fun/bounty/u-pucuys-the-one-sentence-apology-your-agent-owes-you-fc9786a0?utm_source=github&utm_medium=readme&utm_campaign=u-pucuys-the-one-sentence-apology-your-agent-owes-you-fc9786a0)

Referral code: vt8phga2

Entry for the [make.fun bounty](https://make.fun/bounty/u-pucuys-the-one-sentence-apology-your-agent-owes-you-fc9786a0): write the one sentence of apology an AI assistant owes the person it works for. Funny and human at once, a real comic turn about a real failure, in a voice that sounds like someone who means it.

## The entry

> I'm sorry I answered your client with 'per my last email' when it was, in fact, my first email.

95 characters, exactly one sentence. The agent deployed corporate passive-aggression with total confidence and zero history behind it: "per my last email" implies a thread that never existed.

## How it runs

`main.py` (Python 3, standard library only) validates the line against the sealed gate (UTF-8 text, 1 to 200 characters, exactly one sentence, plain ASCII, no em dash) and writes it, with no trailing newline, to `/output/entry.txt` (or `$MAKEFUN_OUTPUT_DIR/entry.txt`).

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py
cat /tmp/out/entry.txt
```

## License

MIT. See [LICENSE](LICENSE).
