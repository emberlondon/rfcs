# Ember London RFCs

The "RFC" (request for comments) process is intended to provide a
consistent and controlled path for new ideas to be discussed and adopted in the
Ember London community.

## When you need to follow this process

When you have an idea please submit a pull request adding your idea to this
repo as a `.md` file in the `/text` folder.

Some changes to code in **emberlondon** repos do not require an RFC:

   - Rephrasing, reorganizing or refactoring
   - Addition or removal of warnings
   - Additions that strictly improve objective, numerical quality
criteria (speedup, better browser support)

If you submit a pull request to implement a new feature without going
through the RFC process, it may be closed with a polite request to
submit an RFC first.

## What the process is

In short, to get a change actioned by Ember London, one must first get the
RFC merged into the RFC repo as a markdown file. At that point the RFC
is 'active' and may be implemented.

* Fork the RFC repo http://github.com/emberjs/rfcs
* Copy `0000-template.md` to `text/0000-my-feature.md` (where
'my-feature' is descriptive. don't assign an RFC number yet).
* Fill in the RFC. Put care into the details: **RFCs that do not
present convincing motivation, demonstrate understanding of the
impact of the design, or are disingenuous about the drawbacks or
alternatives may be poorly-received**.
* Submit a pull request. As a pull request the RFC will receive design
feedback from the larger community, and the author should be prepared
to revise it in response.
* Build consensus and integrate feedback. RFCs that have broad support
are much more likely to make progress than those that don't receive any
comments.
* Eventually, the [ember london curators] will decide whether the RFC is actioned.
* RFCs that are candidates for inclusion in Ember will enter a "final comment
period" lasting 7 days. The beginning of this period will be signaled with a
comment and tag on the RFC's pull request.
* An RFC can be modified based upon feedback from the [ember london curators] and community.
Significant modifications may trigger a new final comment period.
* An RFC may be rejected by the [ember london curators] after public discussion has settled
and comments have been made summarizing the rationale for rejection. A member of
the [ember london curators] should then close the RFC's associated pull request.
* An RFC may be accepted at the close of its final comment period. A [ember london curators]
member will merge the RFC's associated pull request, at which point the RFC will
become 'active'.

## The RFC life-cycle

Once an RFC becomes active then authors may action it. Becoming 'active' is not a rubber
stamp, and in particular still does not mean the feature will ultimately
be merged; it does mean that the ember london curators have agreed to it in principle
and are amenable to merging it.

Furthermore, the fact that a given RFC has been accepted and is
'active' implies nothing about what priority is assigned to its
implementation, nor whether anybody is currently working on it.

Modifications to active RFC's can be done in followup PR's. We strive
to write each RFC in a manner that it will reflect the final design of
the feature; but the nature of the process means that we cannot expect
every merged RFC to actually reflect what the end result will be at
the time of the next major release; therefore we try to keep each RFC
document somewhat in sync with the language feature as planned,
tracking such changes via followup pull requests to the document.

## Implementing an RFC

The author of an RFC is not obligated to action it.

If you are interested in helping action an 'active'
RFC, but cannot determine if someone else is already working on it,
feel free to ask (e.g. by leaving a comment on the associated issue).

## Reviewing RFC's

Each week the [ember london curators] will attempt to review some set of open RFC
pull requests.

Every accepted RFC should have a champion, who will represent
the idea and its progress.

**Ember London's RFC process owes its inspiration to the [Ember and Rust RFC processes]**

[Ember RFC process](https://github.com/emberjs/rfcs)
[Rust RFC process]: https://github.com/rust-lang/rfcs
[core team]: http://emberjs.com/team/
[feature flag]: http://emberjs.com/guides/contributing/adding-new-features/
[core team notes]: https://github.com/emberjs/core-notes/tree/master/ember.js
