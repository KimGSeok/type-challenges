---
name: Study And Issue Handling
about: https://github.com/type-challenges/type-challenges
title: "[Problem] - [ ]"
labels: ''
assignees: ''

---

## Description
It is an issue for studying type script, and each issue means a problem.

/* _____________ Type Challenges _____________ */

###type HelloWorld = any // expected to be a string

/* _____________ Your Code Here _____________ */

##

/* _____________ Test Cases _____________ */
import type { Equal, Expect, NotAny } from '@type-challenges/utils'

type cases = [
  Expect<NotAny<HelloWorld>>,
  Expect<Equal<HelloWorld, string>>,
]

/* _____________ Type Problem _____________ */

- [ ] Self Solve
- [ ] Use Solution

- Related to: https://github.com/type-challenges/type-challenges
