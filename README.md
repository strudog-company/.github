# Infra-Endgame GitHub defaults

This GitHub repository must stay named `.github` and **public**. GitHub
Free only applies org defaults from a public `.github` repo.

Org-wide issue forms and PR template. GitHub applies these to every
`Infra-Endgame` repo that does not define its own.

Issue forms: `.github/ISSUE_TEMPLATE/`
PR template: `.github/PULL_REQUEST_TEMPLATE.md`

Do not copy these files into product repos. A local `ISSUE_TEMPLATE`
folder disables org defaults for that repo.

Style follows [OpenClaw](https://github.com/openclaw/openclaw): problem,
why, impact, evidence. Evidence means tests or a screenshot, not file
lists or line numbers.
