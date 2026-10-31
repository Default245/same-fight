# Same Fight 🔁

**same fight. different day.**

Pre-launch landing page for Same Fight, a concept for an AI tool for couples. Both partners opt in. The AI reads their shared chat history and finds the fight they keep having, plus what actually ends it.

- `index.html` is a single self-contained page with no build step and no external assets.
- Hosted with GitHub Pages.

## Status

Pre-launch test.

- **Waitlist form:** posts name, email, the partner checkbox, and the `src` code to [FormSubmit](https://formsubmit.co) (free, no account), which emails each signup to the owner. It includes a `_honey` honeypot against spam. FormSubmit requires a one-time activation from the owner's inbox.
- **Visit counting:** uses the free, no-account [Abacus](https://abacus.jsn.cam) counting API. It counts one visit per browser per day, using localStorage and no cookies, both in total and per `?src=` code. Add `?test=1` to skip counting for your own checks.
- **Tally:** [`stats.html`](stats.html) shows visits, signups, and rate per source.
- **Placeholders:** the invite link and queue position. All share cards and example answers are illustrative, not real user data.

Not therapy.

## License

MIT, see [LICENSE](LICENSE).
