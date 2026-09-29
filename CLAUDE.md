# CLAUDE.md

This repository holds Keith Huster's GitHub profile README, which github.com/husterk shows above the pinned
repositories.

## Content

- **keithhuster.com is the source of truth.** Every fact and number in `README.md` comes from the site's content
  files (`src/content/site.yaml`, `resume.yaml`, `impact.yaml`, `leadership.yaml`, `patents.yaml`, `beyond.yaml`
  in `husterk/keith-huster-dot-com-site`). When one changes there, change it here in the same words.
- **Keep it scannable in about 30 seconds.** No visitor counters, animated text, skill-badge walls or third-party
  stats cards.
- **Never name a private repository.** Describe private work without linking it.
- US English, no em dashes, straight quotes.

## Workflow

- **An issue comes first.** One branch and one PR per issue; name the branch `<type>/<issue-number>-<slug>` and put
  `Closes #<number>` in the PR body. The required `Linked issue` check fails a PR without it; Renovate PRs are
  exempt.
- **Commits** follow Conventional Commits with a body that explains why, and never contain `#<number>`. Commits on
  `main` must be signed; merge with the squash or merge button, never rebase.
- The repository follows the baseline in `husterk/.github`; run
  `mise -C ~/git-repos/.github run audit -- husterk/husterk` to compare.
