<p align="center"><a href="https://resolvr.com"><img src="https://resolvr.com/resolvr-lockup.svg" width="260" alt="Resolvr"></a></p>

<div align="center">
  <h1>Solving Infrastructure for Agents</h1>

  <p><strong>Challenges, solved.</strong></p>

  <p>
    <a href="https://resolvr.com">Website</a>
    ·
    <a href="https://resolvr.com/docs">Docs</a>
    ·
    <a href="https://github.com/resolvrlabs/resolvr-typescript">TypeScript SDK</a>
  </p>
</div>

---

Your agent hits a CAPTCHA and the run stops. Resolvr is the layer that gets it moving again:
send the challenge context to one endpoint, get back the token, browser identity headers or
clearance cookies the next request needs. Every challenge is solved on real Chrome
infrastructure loading the real page, so what comes back behaves like a browser, not a
replayed string.

Solved today: [`recaptcha_v2`](https://resolvr.com/docs/recaptcha-v2) · [`recaptcha_v3`](https://resolvr.com/docs/recaptcha-v3) · [`cloudflare_turnstile`](https://resolvr.com/docs/cloudflare) · [`cloudflare_blockpage`](https://resolvr.com/docs/cloudflare) — more in active development.

#### Working agentic?

Every docs page is markdown to an agent: append `.md` or send `Accept: text/markdown`, and
[llms.txt](https://resolvr.com/llms.txt) indexes them all. Hand your agent the prompt and it
writes the integration.

<details>
<summary>Copy the prompt</summary>

```text
Implement Resolvr support for recaptcha_v2, recaptcha_v3, cloudflare_turnstile, cloudflare_blockpage in this project using the Resolvr API docs:
https://resolvr.com/docs

Start from the docs index at https://resolvr.com/llms.txt and read the overview plus the page for each task type. Every page is served as markdown when you append .md to its URL or send Accept: text/markdown.

Follow this project's existing HTTP client, configuration, error-handling, naming and test patterns. Integrate directly with the Resolvr API without duplicating existing infrastructure.
```

</details>

<div align="center">
  <h3><a href="https://resolvr.com/signup">Join us now @ resolvr.com</a></h3>
  <sub>Closed beta · sign up, tell us your use case or redeem a ref code · <a href="mailto:contact@resolvr.com">contact@resolvr.com</a></sub>
</div>
