# Individual Project: Groundwork Plan

Status date: 7 November 2026

This plan lists work that does not depend on the group's chosen design. Items marked **Blocked** wait for the design decision.

## Done

- [x] Project folder structure created (`src/`, `tests/`, `docs/`, `evidence/`)
- [x] Dependency list written (`requirements.txt`): pytest, python-dotenv, requests
- [x] Groundwork plan and README draft written

## Next: independent of the group design

1. **Read the required material.** Wooldridge (2009), Chapter 2, and Russell and Norvig (2021), Chapter 8, cover agent architectures and planning. Take notes in `docs/reading-notes.md`, with page references for every claim you may cite later.
2. **Confirm model access.** Create a free Hugging Face account and check which hosted models are available on the free tier. Record the model names and any rate limits in `docs/model-access.md`.
3. **Check the Azure free tier, if you plan to use it.** Record the services and limits. This is optional, as the brief allows fully free-tier or partially realised systems.
4. **Build a minimal tool-calling loop.** In `src/`, write a small function that sends a prompt to a model and parses the response. Add a unit test in `tests/` with a mocked model call, so the test does not depend on the network.
5. **Draft the README sections.** Fill in the install and run sections as the code takes shape.
6. **Start a verified references list.** Use the Harvard Referencing Guide in the project files. Verify every source before you cite it.

## Blocked: needs the group's design decision

- Choose the agent architecture: single agent or multi-agent.
- Define the goal, the planning loop, the tools, and the output domain (for example, academic research or structured information gathering).
- Decide the storage approach and the evaluation criteria.

## Questions to take to the group

- Which design will the individual system implement: the group's agreed design, or a design you proposed individually?
- What are the planned tools, and who owns each one?
- Which domain will the agent work in?
