# Sharath Nair

I work on LLM agent infrastructure — the layer underneath the chat box. Task
scheduling, multi-provider model routing, sandboxed execution, and keeping a
trace of what an agent actually did so the result can be audited rather than
taken on faith.

Mostly TypeScript and Rust, with Python where the data work lives.

**[plexus](https://github.com/nairsh/plexus)** — a self-hosted server that plans
an objective into a DAG of sub-agent tasks, validates the graph before spending
anything on model calls, and runs the independent branches in parallel across
providers. Every step is persisted, so workflows can be replayed or resumed.
~27k lines of TypeScript across nine packages. Experimental.

**[Atlas](https://github.com/nairsh/grok-build)** — a fork of xAI's Grok Build
(Apache-2.0), a terminal coding agent in Rust. I maintain an independent release
track and updater; the fork's changes are mostly in the settings surface and
agent runtime.

Other things in here are forks, upstream mirrors I keep for reference, or
personal tools that aren't meant for anyone else. The two above are the ones
worth reading.
