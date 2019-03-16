# Pronunciations of Names in the ACL Community

## Quick start

The database is stored in [_data/pronunciations.yaml].
This site is meant to be viewed [on the web](https://mjpost.github.io/pronunciations/).

## Clarification

This project began as a set of private notes that helped me introduced speakers properly.
As such, there are many hidden assumptions here that may limit the usefulness to other people.
Based on discussion with a number of linguists on Twitter, building this properly would:

- use IPA instead of my made-up phonetic scheme
- perhaps also include an English approximation but in some standard scheme
- include audio files of people pronouncing their names in their native pronunciations

While conceding these points, it's beyond the scope of my original intent, and I hope that the project as it stands will still be useful.
In the interest of building on standards, I am removing my own private scheme in favor of [ARPABET](https://nlp.stanford.edu/courses/lsa352/arpabet.html)
Ones that have been transitioned are between slashes (/.../), while the old scheme uses quotes ("...").

## Background

Properly pronouncing a person's name is a basic tenet of respect and decency.
It is often jarring to hear people's names mispronounced, for example at introductions of speakers for invited talks.
(Equally bad is for an introducer to mention that they don't know how to pronounce it---why didn't you find out ahead of time?!)
At the same time, it is often difficult to know how to pronounce someone's name in light of English's terrible orthography, which has resisted centuries of attempted spelling reforms going back at least to the 16th century.
Moreover, there are no clearly defined social conventions for asking someone how to pronounce their name, so doing so can sometimes be awkward.

This repo is an attempt to solve this problem by providing a database of phonetic transcriptions of names of folks in the [ACL community](http://aclweb.org/).
Please contribute!

Some guidelines:
- The goal is to project name pronunciations into the English phoneme system.
- Identically spelled last names might have different pronunciations, so transcriptions should include links to homepages or other identifying information.
- There are many names that many people might consider unambiguous, but ambiguity is in the eye of the beholder.
  Therefore any name that has given any person trouble could be included.
