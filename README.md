# Sub Pause rules

Signed rule updates for the Sub Pause app: the button words and page-reading
steps it uses to cancel and restart streaming subscriptions.

- `rules.json`: the rules. Nothing private is in here.
- `rules.sig`: the signature. The app only uses `rules.json` if this signature
  matches the publisher's key, so an edited copy is ignored.

Published with `tools/publish-rules.mjs` in the app project.
