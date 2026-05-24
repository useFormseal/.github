## Hey 👋

This is the home of **formseal** — a small ecosystem of CLI tools for encrypted form handling.

formseal is maintained by one developer. The org exists to give the project its own space and keep things tidy.

---

### What we build

formseal is a client-side encrypted form pipeline. Submissions are sealed in the browser before reaching your backend. The server stores ciphertext only. Decryption happens locally, with a key that never leaves your machine.

Three tools, one pipeline:

- [**formseal-embed**](https://github.com/useFormseal/embed) — drop-in browser encryption runtime
- [**formseal-fetch**](https://github.com/useFormseal/fetch) — pull ciphertexts from your storage backend
- [**formseal-decrypt**](https://github.com/useFormseal/decrypt) — decrypt locally with your private key

```
Browser → encrypted submissions → your backend → fetch → decrypt → plaintext
```

No hosted service. No backend trust. No lock-in.

---

Built by [@grayguava](https://github.com/grayguava).
