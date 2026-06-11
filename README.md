# Knowledge in AI

Two short learning reports on why philosophy is practical knowledge for an AI engineer, built from my philosophy reading and my responsible-AI notes. Same berry aesthetic, matching interactive pages.

## Pages

| Page | What it covers |
|------|----------------|
| [Epistemology for AI Engineers](index.html) | Why a model that cannot tell knowledge from a confident guess is the core problem, with Nagel's JTB, Gettier, testimony and contextualism mapped to RAG and grounding. |
| [Practical Ethics for AI Engineers](practical-ethics-for-ai-engineers.html) | Rachels, Hume, Kant, Parfit and Singer on whether ethics is objective, mapped to bias, RLHF, fairness and alignment. |

Each page has live interactive demos (a JTB switchboard, a Kant maxim tester, scenario sliders) and a short "why it matters for AI" section.

## Run locally

Both are single static HTML files, no build step:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploy

Served on GitHub Pages from `main` via the workflow in `.github/workflows`. Just push and the Action handles it.

## Sources

- Jennifer Nagel, *Knowledge: A Very Short Introduction*
- James Rachels, *The Elements of Moral Philosophy*
- My responsible-AI and RAG study notes
