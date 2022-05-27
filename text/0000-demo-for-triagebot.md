- Feature Name: `demo_for_triagebot`
- Start Date: 2022-05-27
- RFC PR: [rust-lang/rfcs#0000](https://github.com/rust-lang/rfcs/pull/0000)
- Rust Issue: [rust-lang/rust#0000](https://github.com/rust-lang/rust/issues/0000)

# Summary
[summary]: #summary

Demoing traigebot merge of RFC

# Motivation
[motivation]: #motivation

Eventually triagebot will do this mechanical step for us.

# Guide-level explanation
[guide-level-explanation]: #guide-level-explanation

For the short term, my goal is to be able to run
```
GITHUB_API_TOKEN=$(pass gh-tok-play) cargo run --bin rfc_merge_pr 3216
```
(where "3216" is an appropriate selected RFC number. For a while I was using
that actual RFC PR, but then I realized that I really should have my development
work point at a different repository.)

# Reference-level explanation
[reference-level-explanation]: #reference-level-explanation

skip this.

# Drawbacks
[drawbacks]: #drawbacks

Maybe humans are better at this fuzzy stuff after all.

# Unresolved questions
[unresolved-questions]: #unresolved-questions

* Who is going to maintain this?

* When will we get the fun part of an actual `@triagebot` command on github itself?
