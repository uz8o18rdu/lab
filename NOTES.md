# Lab Notes

## API Design

- Prefer resource-oriented URLs.
- Use HTTP verbs intentionally.
- Keep responses minimal, include links for related resources.
- Version via header, not URL path, when possible.
- Document error codes and messages clearly.

## Experiment Ideas

- Test pagination styles in a small Sinatra app.
- Try JSON:API serialization with `jsonapi-rb`.

## Links

- [JSON:API Spec](https://jsonapi.org/)
- [Ruby API Design Guide](https://github.com/restful-rails/restful-rails)