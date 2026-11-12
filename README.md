## Hi, I'm Christian

AI product manager with a background in property operations. I own a product
end to end — problem, spec, evaluation, release — and direct a team of coding
agents to build it.

### Product work you can inspect

**[Verwalino](https://github.com/itskeKs/verwalino)** — property management for
German rentals and homeowners' associations, built from my own years of running
properties. **Status: in active development.** It does not work end to end yet;
the releases so far test the deployment path, not the product. The
[feature status](https://github.com/itskeKs/verwalino/blob/main/docs/feature-status.md)
lists what works and what does not.

- **AI features:** import of declarations of division with human review, and
  property Q&A with cited sources. The model proposes; evidence validation and a
  reviewer decide what becomes data. Each organization brings its own provider
  (OpenAI, compatible APIs or Anthropic) with per-run and monthly limits — see
  [ADR 0014](https://github.com/itskeKs/verwalino/blob/main/docs/adr/0014-provider-neutral-ai-runtime.md)
  and the [offline evals](https://github.com/itskeKs/verwalino/tree/main/backend/app/evals).
  No model is marked as evaluated yet; live quality is tracked in
  [#399](https://github.com/itskeKs/verwalino/issues/399).
- **How I specify:** [roadmap](https://github.com/itskeKs/verwalino/blob/main/docs/roadmap.md),
  [14 architecture decision records](https://github.com/itskeKs/verwalino/tree/main/docs/adr)
  and [72 Gherkin feature files](https://github.com/itskeKs/verwalino/tree/main/features).
- **How I build:** 380+ issues, 190+ merged pull requests, 5 test releases.

**[project-kit](https://github.com/itskeKs/project-kit)** — the operating model
behind it: bootstrap, playbook and session briefs for repositories where several
coding agents work in parallel.

**[coddy-agent](https://github.com/coddy-project/coddy-agent)** — contributions
to an open-source coding agent in Go, focused on context cost (on-demand tool
schema loading). Three pull requests, currently open.

### Get in touch

[keks.it](https://keks.it) · [LinkedIn](https://www.linkedin.com/in/christian-kunkel-93a684232)
