# The CompPendium: Articles & Ideas

Computer science, made approachable. From one student to another.

This repository is the editorial roadmap for [The CompPendium](https://www.thecomppendium.com/): what is live, what could come next, and the questions each future article should help a beginner answer.

**Last updated: October 20, 2026.** Eight articles are currently live.

The editable article HTML lives in the [website repository](https://github.com/ainsleyfreedman01/TheCompPendium/tree/main/site/blog-posts). This repository tracks ideas and publication status rather than maintaining a second copy of every article.

## Contents

- [Published articles](#published-articles)
- [Suggested next articles](#suggested-next-articles)
- [Remaining original roadmap](#remaining-original-roadmap)
- [New ideas to explore](#new-ideas-to-explore)
- [Writing approach](#writing-approach)
- [Contributing](#contributing)

## Published articles

Titles below match the current website. The roadmap numbers preserve the original topic IDs; they are not the website's reading order.

| Roadmap ID | Article | What readers explore |
| --- | --- | --- |
| 1 | [What is computer science, anyway?](https://www.thecomppendium.com/blog-posts/what-is-computer-science/) | The big picture: problem-solving, algorithms, and more than just coding. |
| 2 | [What can I do with computer science?](https://www.thecomppendium.com/blog-posts/what-can-i-do/) | Different ways to use CS and find an area that sparks curiosity. |
| 3 | [So many languages. Where should I start?](https://www.thecomppendium.com/blog-posts/where-should-i-start/) | Choosing a first language based on goals, with an interactive web example. |
| 4 | [AI: where does it fit in?](https://www.thecomppendium.com/blog-posts/ai-where-does-it-fit-in/) | How AI fits into computer science and what learning from examples means. |
| 5 | [AI: responsible use and ethics](https://www.thecomppendium.com/blog-posts/ai-responsible-use-and-ethics/) | Bias, privacy, accountability, and the people behind technical decisions. |
| 6 | [How do websites actually work?](https://www.thecomppendium.com/blog-posts/how-websites-work/) | Browsers, servers, and how HTML, CSS, and JavaScript work together. |
| 11 | [What is an API, and why are they everywhere?](https://www.thecomppendium.com/blog-posts/what-is-an-api/) | Requests, responses, and how software communicates. |
| 20 | [The art of debugging: curiosity beats guessing](https://www.thecomppendium.com/blog-posts/art-of-debugging/) | Reproducing a bug, forming a hypothesis, and testing one change at a time. |

**Editorial transparency:** The websites, APIs, and debugging articles are live and explicitly labeled as drafted with AI assistance. Being published is not a claim of independent human fact-checking; review their wording, examples, and sources before presenting them as fully author-reviewed work.

### Current learning paths

The website's [learning paths](https://www.thecomppendium.com/paths/) connect these notes:

- **Find your footing:** What is CS? → What can I do with it? → Where should I start?
- **Understand the web:** Websites → APIs → Debugging.
- **Think critically about AI:** Where AI fits → Responsible use and ethics.

## Suggested next articles

These are proposed priorities, not drafts or publication commitments.

| Priority | Original ID | Working title | Beginner question and practical hook |
| --- | --- | --- | --- |
| 1 | 7 | What happens when you type a URL into your browser? | How does a name become a page? Follow DNS, HTTPS, a request, and a response; inspect one request in browser DevTools. Go deeper than the existing websites overview. |
| 2 | 8 | Frontend, backend, and full-stack: what's the difference? | Which code runs where? Trace a contact form from its HTML fields to a server endpoint without exposing secrets. |
| 3 | 17 | Version control and Git: working together on code | How do I change code without losing a working version? Make a small commit, inspect a diff, and explain a branch and pull request. |
| 4 | 9 | Data structures explained simply | Why not put everything in one list? Compare an array, stack, queue, and key-value map using familiar situations. |
| 5 | 10 | Algorithms: the secret sauce of computer science | How can two correct solutions do different amounts of work? Walk through linear and binary search on a sorted list. |
| 6 | 19 | Accessibility in tech: designing for everyone | Can someone use a page without a mouse? Try keyboard navigation, meaningful labels, alt text, and a contrast check. |

## Remaining original roadmap

All topics below remain **ideas, not completed articles**. The six priorities above are also still planned.

| Original ID | Working title | Possible angle |
| --- | --- | --- |
| 12 | Understanding databases: where data lives | Explain tables, records, keys, and a simple query using a tiny library catalog; distinguish storage from an API. |
| 13 | The evolution of programming languages | Why languages change and coexist; connect historical needs to modern trade-offs rather than ranking a winner. |
| 14 | Careers in tech: beyond software engineering | Expand the existing careers overview with concrete day-in-the-life examples in UX, security, data, QA, and technical writing. |
| 15 | The future of computing: quantum, AI, and beyond | Separate established ideas from speculation, explain limitations, and clearly date sources. Consider splitting this broad topic into smaller notes. |
| 16 | How computers "think": introduction to machine learning | A deeper follow-up to the AI overview: features, training/test data, overfitting, and why a prediction is not understanding. |
| 18 | Open source: collaboration that shapes the world | Read a project's README and license, find contribution guidelines, and make a small documentation contribution. |

## New ideas to explore

These extend the original roadmap; none are published yet.

### Build and understand

- **My first website, without a framework:** Create a small HTML/CSS/JS page, preview it over HTTP, and understand what each file does.
- **From localhost to a real URL:** Explain hosting, deployment, DNS, and HTTPS using a static site; include how to tell a failed deployment from a browser cache issue.
- **What does an error message actually tell me?** Read a stack trace, separate syntax/runtime/logic errors, and turn one message into a useful debugging question.
- **How do I know my code works?** Introduce a tiny assertion, an edge case, and the difference between unit and browser tests.
- **What does asynchronous mean?** Use a delayed request to introduce promises, async/await, loading states, and errors without assuming prior backend knowledge.

### Make technology work for people

- **Passwords, API keys, and secrets: what belongs where?** Distinguish public identifiers from credentials and explain why browser code cannot keep a secret.
- **Cookies, local storage, and sessions:** Explain what a site remembers, where it is stored, and why privacy choices matter.
- **What makes a good bug report?** Practice clear steps, expected versus actual behavior, and a minimal reproducible example without sharing private information.
- **Using AI to learn without skipping the learning:** Compare asking for an explanation, checking a generated answer, and copying code you cannot yet explain.

### Follow your curiosity

- **Spreadsheets, SQL, and code: which tool fits the question?** Solve one small data question three ways and discuss trade-offs.
- **How does a computer represent a picture?** Explore pixels, RGB values, resolution, and why file size changes.
- **Why does my program get slower as the input grows?** A visual follow-up to algorithms that introduces Big O through counted steps, not intimidating notation.

## Writing approach

Keep the purpose the same: friendly explanations for readers who may not have had access to a computer science class.

- Start with a relatable question, define new terms, and avoid assumed background knowledge.
- Use a concrete analogy, then explain where the analogy stops being accurate.
- Include a small example or optional experiment where it genuinely helps.
- End with one takeaway and a reflection question with an explanation.
- Link to related notes and reliable sources; distinguish facts from predictions.
- Disclose AI-assisted drafting and review code, factual claims, and sources before marking a piece author-reviewed.
- Keep titles and publication links here in sync with the website. Move topics to published only when their public URLs work.

For publishing instructions, see the [website README](https://github.com/ainsleyfreedman01/TheCompPendium#publish-a-field-note).

## Contributing

Have a question you wish someone had explained sooner? [Open an issue](https://github.com/ainsleyfreedman01/TheCompPendium_ArticleTopics/issues/new) with:

- A suggested topic or beginner question.
- Why it would help a new learner.
- An example, analogy, or reliable resource to consider.
- Any overlap with an existing note, and what the new piece would add.

Suggestions are welcome; ideas listed here are a flexible backlog, not a promised release schedule.
