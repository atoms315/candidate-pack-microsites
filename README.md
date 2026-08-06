# Candidate pack microsites — three directions for one role

**[View the live pack →](https://atoms315.github.io/candidate-pack-microsites/)**

A candidate pack for a single senior engineering role, designed three different
ways to find out which version a candidate would actually finish reading.

Atomic Recruiting is my LLC and the role is invented for it. 

---

## The problem

Most job ads fail in the same three places:

1. **No salary.** The candidate assumes the worst number.
2. **No explanation of the interview stages.** The candidate prepares for the
   wrong thing, and reads the silence as disorganisation.
3. **No admission that anything is hard.** Nobody believes it, so the whole
   page loses credibility.

Candidates fill those gaps with their least generous assumption, and the good
ones self-select out before you ever speak to them.

## What all three directions commit to

- The salary band published up front 
- Every interview stage named, timed, attributed to a person, and paired with
  **what we look for** at that stage.
- A section headed **Honest caveats**: the legacy codebase, the refactors that
  get deprioritised, the moving roadmap.
- One action to take, and it's "reply to a named human" — no portal, no form.

Same content. Same commitments. Three different arguments about how a company
should sound while making them.

## The three directions

| | Direction | The argument | Best for |
|---|---|---|---|
| [`bold.html`](bold.html) | **Bold & brand-forward** | Big type, hard numbers in the first screen, one saturated section. | Cold outbound, where you have five seconds to look like a company worth reading about. |
| [`editorial.html`](editorial.html) | **Editorial feature** | A long-form piece with a byline and a pull quote, written by the hiring manager rather than by HR. | Warm candidates already weighing up whether to take the call. |
| [`playlist.html`](playlist.html) | **Interactive playlist** | The pack as seven playable tracks with a working player — press play and it walks itself. | Getting shared internally. Memorable; almost certainly the weakest converter. |

## What I'd test next

Completion rate and reply quality per direction, split by source.

My hypothesis: bold wins the clicks, editorial wins the replies you actually
want, and the playlist gets forwarded around a company by people who will never
apply.

## How it's built

Plain HTML — open any file in a browser, no install, no build step.

All three run on one design system (colour, type, spacing and components from a
shared token set), so the directions differ by **layout and voice**, not by
palette. That was deliberate: it isolates the variable being tested.

Team photographs are drop-in placeholders.

---

*Concept work. The company, the role, the team and every number in these pages
are invented for the exercise.*
