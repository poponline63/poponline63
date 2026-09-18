### aei0n

I build open tools for people who run AI agents all day, mostly the part nobody enjoys: proving the work actually happened.

An agent that reports success is not evidence of success. Most of what I publish sits somewhere around that problem, from writing a finish line down before the work starts, to deciding whether the result really meets it.

**What I'm working on**

- **[hermes-jev-north-star](https://github.com/poponline63/hermes-jev-north-star)** - turn an intention into a checkable finish line, generate the run prompt from it, then let a judge decide whether the work is done. Deterministic checks first, an evidence file, then [Jev](https://typesafe.ai) for the parts a script cannot read. 82 tests, no key needed for the deterministic half.
- **[awesome-agent-verification](https://github.com/poponline63/awesome-agent-verification)** - the list of tools and practices for deciding whether autonomous agent work is actually done. Eval harnesses, judges, tracing, guardrails, benchmarks.
- **[hermes-pets-all](https://github.com/poponline63/hermes-pets-all)** - a Hermes desktop plugin that browses every pet installed for a profile, past the built-in render cap.

**How I work**

Small tools that do one thing and say plainly when they cannot. If a check cannot be run, I would rather it fails than guesses. No telemetry, no accounts, no keys where a plain script will do.

Most of what I build is for [Hermes Agent](https://github.com/NousResearch/hermes-agent), the open-source agent from [Nous Research](https://nousresearch.com). Everything public here is MIT or CC0 unless the repo says otherwise.
