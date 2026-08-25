# API Design Notes

Some quick reminders from today's lab session:

- Start with the resource model, not the endpoint list.
- Use consistent naming: plural nouns, kebab-case for paths.
- Keep error responses structured: `{ error: { code, message, details } }`.
- Version early, but only if the contract is likely to change.
- Document one example per endpoint, including errors.

Still need to test: rate limiting headers and idempotency keys.
