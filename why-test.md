# Why Test Software?
In order to judge how we should do something, we should be clear on our goal.
There are many reasonable goals for testing in general and automation in particular,
but in this book we will focus on one overriding goal:
we test so that we can release products and updates confidently, quickly.

There are two main parts to this that I want to break down.

First, we want to release 'confidently'.
By this I mean that we have a good understanding of the risk posed by the release
and are unlikely to encounter unexpected issues that meaningfully increase that risk.

Second, we want to release 'quickly'.
What counts as 'quick' obviously differs across companies or even teams,
but a good metric for what is 'quick enough' is that the feedback loop between
code being written and issues with that change being discovered and assigned for fixes
is short enough the developer or team still has the context and focus necessary
to address them without much context-switching.
In particular if the team that wrote that code struggles to remember
key information about that work, the feedback loop is likely too slow.

TODO: Bring in information from [Accelerate: The Science of Lean Software and Devops](https://www.oreilly.com/library/view/accelerate/9781457191435/)

This focus on confident, quick releases impacts the business, the users, and the development teams in positive ways:

* The Business
  * Increased speed of development
  * Lower cost of issues (money, time, customer satisfaction)
  * Improved risk management
* The Users
  * Desired features sooner and better
  * Improved product satisfaction
* The Development Teams
  * Increased productivity
  * Lower stress levels as features near release
  * Fewer undiscovered issues and edge cases

