## Curated Learning Resources

### [Summary and Criticism of Fowler’s “Refactoring”](https://marklooi.medium.com/summary-and-criticism-of-fowlers-refactoring-71d5c9892fcc)
**Mark Looi**, President, Looi Consulting

In this article, Mark summarizes Martin Fowler's book *"Refactoring: Improving the Design of Existing Code"*. The book has become a vital resource in the field of software engineering for over two decades. Refactoring, the practice of improving existing software code without changing its functionality, is explained in the book with numerous examples and patterns.

The article emphasizes the importance of regular refactoring to prevent code deterioration and maintainability issues. Code can atrophy due to changing environments or the need for additional functionality, leading to decreased effectiveness and increased complexity. Mark provides an example from the book that demonstrates the refactoring process. Fowler suggests breaking up large functions, decoupling data processing from printing and calculation, and using polymorphism to simplify conditional logic. The article also mentions the significance of automated testing to ensure the code remains functional after each refactoring step.

Mark concludes by acknowledging some criticisms of the book and the need for a nuanced discussion on challenges and functional programming principles in refactoring.

---

### [Rub a dub dub](https://www.joelonsoftware.com/2002/01/23/rub-a-dub-dub/)
**Joel Spolsky**, CEO, Stack Overflow

FogBUGZ started as an experiment but grew popular over time. The code base became messy and difficult to improve. Instead of rewriting the code from scratch, Joel decided to do a thorough refactoring by cleaning up the code without adding new features. This refactoring took three weeks and involved separating HTML from logic, removing hard-coded values, and restructuring the code.

Joel argues that this refactoring approach saved time compared to a complete rewrite while still improving the code and fixing bugs. The schedule was predictable and the code is now easier to add new features to. He recommends refactoring tools to make such code cleanups more efficient.

---

### [Fleet Management at Spotify (Part 3): Fleet-wide Refactoring](https://engineering.atspotify.com/2023/05/fleet-management-at-spotify-part-3-fleet-wide-refactoring/)
**Matt Brown**, Staff Software Engineer, Spotify

Spotify manages its software across thousands of repositories. They created tools to enable refactoring code across all repos at once, called fleet-wide refactoring. They use a BOM to manage dependencies and Fleetshift to generate code changes and pull requests across repos. They introduced automerging to automatically merge changes as long as tests pass. They monitor post-merge health to catch issues. They use gradual rollouts for riskier changes.

These tools have reduced the time to adopt new library releases from 200+ days to under 7 days. More teams are embracing the fleet-first mindset and using Fleetshift. However, they aim to improve the tools to make fleet-wide changes easier and support monorepos.
