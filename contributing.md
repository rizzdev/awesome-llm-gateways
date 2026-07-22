# Contribution Guidelines

Thanks for helping keep **Awesome LLM Gateways** genuinely open. This isn't a
comprehensive index — it's a curated list of LLM gateways, routers, and caches
you can run yourself. Please read this before opening a pull request.

## The bar for inclusion

Every entry must pass **all three** tests. If a tool misses even one, it
doesn't belong here — no matter how good it is:

1. **Self-hostable** — you run the gateway yourself, with no mandatory vendor
   endpoint in the request path. Your API keys and traffic never pass through
   someone else's servers.
2. **Open-source** — a real OSI license, with source you can audit before it
   sits in your critical path.
3. **No lock-in** — it speaks an OpenAI-compatible or standard interface, so
   you can pull it out; it isn't dead weight without a paid proprietary backend.

Cloud-only gateways and source-available-but-not-OSI projects (e.g. Elastic
License, BSL) are out of scope by design. That's not a knock on the tool — it's
just not what this list is for.

## Adding a tool

- One tool per pull request.
- Add it alphabetically within the most appropriate category.
- Format: `- **[Name](repo-url)** · Short, objective description of what it does`
- The description states what the tool *does*, not that it's "awesome" or "the best."
- Start with a capital letter. Keep it to one line.
- Link to the **source repository**, not a marketing page.
- Add a red flag (`open-core`, `fiddly setup`, `slowing down`, `early`) only
  when it genuinely applies and is verifiable on the repo page.

## Editing or removing

- Open a PR if a tool has gone cloud-only, closed-source, relicensed away from
  OSI, unmaintained (archived or no commits in 6+ months), or otherwise stopped
  meeting the bar.
- Corrections to links, descriptions, licenses, or flags are always welcome —
  this list lives or dies on being accurate.

## Quality checklist

- [ ] The tool passes all three inclusion tests.
- [ ] The entry is in the right category, in alphabetical order.
- [ ] The description is objective, one line, and correctly capitalized.
- [ ] The link points to the canonical source repository (not a fork or mirror).
- [ ] Any red flag applied is verifiable on the repo page.
- [ ] Spelling and formatting match the surrounding entries.

By contributing, you agree to release your contributions under the CC0 license.
