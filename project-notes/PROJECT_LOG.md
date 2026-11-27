# Project log

**Team name:** Chris  
**Startup name:** CampusSwap  
**Live site link:** https://chrisdauphinee.github.io/CampusSwap/

## Work sessions

### Session — Nov 24, 2026 — driver: Chris

- **Goal:** Understand the assignment and choose a business idea.
- **Key AI prompts (summarized):** Explain the assignment requirements; build the CampusSwap website.
- **What worked:** I chose a marketplace for university students and used ChatGPT to generate the initial website code.
- **What broke, and how we fixed it:** I had trouble signing into GitHub, so I continued working offline. I eventually got my account set up.
- **Committed?** No — work was offline.

### Session — Nov 25, 2026 — driver: Chris

- **Goal:** Set up my project repository.
- **Key AI prompt (summarized):** Explain how to set up the repository.
- **What worked:** I got into GitHub and reviewed the assignment materials on Moodle.
- **What broke, and how we fixed it:** I couldn't find the starter template. I contacted my professor, who later sent me the link.
- **Committed?** No confirmed commit.

### Session — Nov 27, 2026 — driver: Chris

- **Goal:** Get CampusSwap into the official starter repository.
- **Key AI prompt (summarized):** Help set up CampusSwap using GitHub.
- **What worked:** I used the link from my professor to create my own repository from the template. With AI assistance, the website code was uploaded and committed.
- **What broke, and how we fixed it:** The GitHub integration couldn't find a repository at first. Once I created my repository, it became accessible.
- **Committed?** Yes — Add AI-assisted CampusSwap marketplace prototype (b9d5c5d).

### Follow-up — Nov 27, 2026 — publication and review

- **Goal:** Publish the website and review the code.
- **Key AI prompt (summarized):** Check the website for problems.
- **What worked:** I enabled GitHub Pages using the main branch and root folder. An AI-assisted source review found no missing element references or duplicate IDs and confirmed the mobile viewport and prototype footer were included.
- **What broke, and how we fixed it:** Initially, live browser testing was unavailable during the source review. After GitHub Pages finished publishing, I opened the live website and tested the search, category filters, saved items, product details, demo purchase request, new listings, network effects sliders, mobile layout and student prototype footer. All checklist tests worked.
- **Committed?** Yes — Record Pages configuration and static code checks.

## Things that broke (running list)

| Date | What went wrong | What we tried | What finally fixed it |
|---|---|---|---|
| Nov 24 | Trouble signing into GitHub | Continued working offline and tried signing in | Account setup eventually succeeded |
| Nov 25–27 | Couldn't locate the starter template | Checked Moodle and contacted the professor | Professor provided the link |
| Nov 27 | Repository was not accessible through the GitHub integration | Created my repository using the template | Repository became accessible |
| Nov 27 | Live browser testing unavailable during review | Checked the committed source code | Opened the published website and completed the testing checklist |

## What a real version would need

| Feature we faked or skipped | Why a real company would need it | How hard / expensive? |
|---|---|---|
| Student verification | Restrict campus accounts and improve trust | Medium difficulty, low to moderate cost at launch. An existing login service (SaaS) saves development time, but student email verification still needs to be set up. Costs could increase as more students join. |
| Shared database | Make listings available to all users rather than one browser | Medium difficulty, low to moderate ongoing cost at first. A managed database (PaaS) avoids running our own servers, but someone needs to connect it to the website and manage access. Storage and usage costs grow with activity. |
| Payment processing | Collect optional promoted listing fees | Medium difficulty, relatively low setup cost if an existing payment processor is used. There would be fees on each payment, and refunds and disputes would need to be handled. |
| Messaging | Let buyers and sellers coordinate collection | Medium to high difficulty and moderate cost. Private messaging needs a backend, message storage and notifications. Moderation and spam prevention add ongoing costs. |
| Security and privacy | Protect account information and messages | High difficulty and potentially expensive. Secure accounts, access controls, regular updates and monitoring require ongoing technical work, particularly as the platform grows. |
| Listing moderation | Remove scams and misleading listings | Medium to high difficulty and potentially expensive as usage increases. Reporting tools can help, but people may still need to review complaints and remove fake listings. |
| Customer support | Resolve complaints and technical problems | Medium difficulty, low cost initially if the founders handle support. As the platform grows, support software and paid staff could become a significant expense. |
| Backups | Recover information after failures | Low to medium difficulty and relatively low ongoing cost for a small platform using managed backups. Recovery testing takes time, and storage costs increase as more data is collected. |

Cost and difficulty ratings are rough estimates for an early-stage campus marketplace, not supplier quotes. Costs depend on usage, staffing and the providers selected.

## Reflection

1. What surprised you most about building software with AI?
2. Which parts were easy, and which were hard? Why do you think that is?
3. If a competitor had the same AI tool, how long would it take them to copy your site?

