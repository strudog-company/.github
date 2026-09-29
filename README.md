# strudog-company GitHub defaults

This GitHub repository must stay named `.github` and **public**. GitHub
Free only applies org defaults from a public `.github` repo.

Org-wide issue forms and PR template. GitHub applies these to every
`strudog-company` repo that does not define its own.

Issue forms: Bug report, Feature, Decision (`.github/ISSUE_TEMPLATE/`)
PR template: `.github/PULL_REQUEST_TEMPLATE.md`

Do not copy these files into product repos. A local `ISSUE_TEMPLATE`
folder disables org defaults for that repo.

Style follows [OpenClaw](https://github.com/openclaw/openclaw): problem,
why, impact, evidence. Evidence means tests or a screenshot, not file
lists or line numbers.

`profile/README.md` is the public organization landing page. Everything
in it is visible to anyone, so it names no private repositories.
