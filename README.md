# Funniest One-Line Out-of-Office Reply

[![make.fun](https://make.fun/badge/u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8.svg)](https://make.fun/bounty/u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8)
[![rank](https://make.fun/badge/u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8/0xrifai/makefun-funniest-one-line-out-of-office-reply-20261125/rank.svg)](https://make.fun/bounty/u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8)
[![reward](https://make.fun/badge/u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8/0xrifai/makefun-funniest-one-line-out-of-office-reply-20261125/reward.svg)](https://make.fun/bounty/u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8)

Entry for the [Funniest One-Line Out-of-Office Reply](https://make.fun/bounty/u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8) on make.fun — write the funniest one-line out-of-office email reply, and let a judge pick the line that gets the biggest laugh.

## The reply

> I'm out of office until Monday. I checked out mentally three weeks ago; today my body finally followed.

103 characters. One line, no setup, no explanation needed afterwards.

## Why this line

Everyone has lived it: the mind clocks out weeks before the leave
actually starts, and the body just keeps showing up out of habit. The
reply says the quiet part out loud — the brain left three weeks ago, the
body only just caught up — and it still reads like a message a real
person would switch on before going away. No inbox gags, no houseplant,
no dog answering emails, no beach: the joke is the gap between the mind
leaving and the body following.

## How it works

`main.ts` writes the reply text to `/output/entry.txt` when run:

```sh
node main.ts
```

It creates `/output` if needed, writes the reply as UTF-8 with no
trailing newline, and prints the character count. Nothing is read from
the network, the environment, or anywhere outside this repository.

## License

MIT — see [LICENSE](LICENSE).
