# Contributing

Thanks for helping keep this list useful. Suggestions are welcome from anyone who designs, builds, writes for or runs digital products for the NSW Government.

## What belongs on the list

An entry should be:

- **Useful to people delivering NSW Government digital products.** NSW sources come first. Federal or international resources belong only where NSW teams genuinely rely on them and there is no NSW equivalent.
- **Authoritative.** Link to the official, canonical home of a standard, policy, tool or dataset, not to a blog post or copy about it.
- **Current and maintained.** No archived repositories, superseded policies or pages that have not been touched in years. If something has been replaced, link to its replacement.
- **Publicly accessible.** No intranet links or resources that need an agency login to read.

This is a curated list, not a directory. "It exists" is not enough; tell us why it is one of the best resources for its category.

## Entry format

```md
- [Name](https://example.nsw.gov.au/) - What the resource is, in one sentence.
```

- Use the resource's official name and capitalisation.
- Separate the link and the description with `-`.
- Start the description with a capital letter and end it with a full stop.
- Describe what the thing is, objectively. Avoid marketing language and do not repeat the name in the description.
- Use Australian English ([Style Manual](https://www.stylemanual.gov.au/)).
- Add new entries at the bottom of the most relevant section. Open an issue first if you want to propose a new section.

## Making a change

1. Fork or branch the repository. Branch names must follow the enforced pattern; `npm run branch:create` builds a compliant one.
2. Edit `README.md`.
3. Run `npm run lint` ([awesome-lint](https://github.com/sindresorhus/awesome-lint)) and `npm run format:check`, and fix anything they report.
4. Commit with a [Conventional Commits](https://www.conventionalcommits.org/) message, for example `docs(list): add Data.NSW`. `npm run commit` helps with this.
5. Open a pull request that explains why the resource deserves a place on the list.

Spotted a broken link, a superseded resource or a wrong description? Open an issue or a pull request; fixes are as valuable as additions.

By contributing, you agree to waive all copyright to your contribution under the [CC0 1.0 Universal](LICENSE) dedication, and to follow the [Code of Conduct](CODE_OF_CONDUCT.md).
