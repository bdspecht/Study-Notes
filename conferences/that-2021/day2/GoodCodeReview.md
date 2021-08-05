### Anatomy of a good code review
* References
  * [Slide Deck](https://github.com/eagroom/That_2021_CodeReview)
* What a code review is not
  * A chance to show off how much better of a developer you are
  * A time to nitpick
* Why this is important
  * Code is never "checked-in" before it is reviewed
* What code reviews can offer
  * Better code quality and maintainability (readability, uniformity, understandability...)
  * Finding defects such as problems, security, vulnerabilities, malware
  * Learning and knowledge transfer
  * Increase sense of mutual responsibility
  * Find better solutions
  * Complying to QA guidelines
    * Mandatory in some contexts such as air traffic software
  * Normalize failure
* Ways to do a code review
  * Scheduled meeting
    * Needs to be a purposeful meeting
  * Over the shoulder
  * Pair programming
  * Pull request reviews
* Author
  * Who: Writers of the code
  * Responsibilities:
    * Write readable, testable code you are proud of
    * Create a clear concise statement of what you wrote and why
    * Clearly relate the code to a requirement from the client
    * Prepare for the review, being ready to answer questions and demo the code
* Reviewer
  * Look through the code, looking for
    * Design flaws
    * Logic errors
    * Memory leaks
    * Performance issues
    * Does it meet the client's requirements
    * Does it meet the architectural design
    * Automated tests are written cover the new code
    * Code maintainability
    * Code readability
    * Security vulnerabilities
    * Coding standards like SOLID and DRY principles
  * Add comments
* How to be a good reviewer
  * Be considerate and constructive
  * Ask questions rather than making comments
  * Be timely
  * Take it seriously
* Going from a good reviewer to great
  * If you don't understand or wonder why something was a done a certain way ask
  * Pull it and run it locally
* Traps to avoid
  * Rubber stamping your approval
  * Thinking you can't ask
  * Inheriting the author's biases
  * Putting to much ceremony around code reviews
* When to do a code review
  * Good - before it goes to production
  * Better - before a QA process begins
  * Best - before the code is merged into the feature branch
* Remove commented out code
  * This is why source control exists
