# Who Actually Owns Your AI Assistant?

Most people don't think about this until something goes wrong. Then it becomes very obvious, very fast.

You've built a workflow around a tool. Your team uses it daily. Your processes depend on it. Then the company behind it gets acquired, or pivots, or raises prices by 300%, or just quietly changes the terms of service to include a clause about training on your inputs. And you're stuck, because the thing you depend on isn't yours.

This is the ownership problem with AI tooling, and it's going to cause a lot of pain over the next few years as the market consolidates.

---

Right now there are hundreds of AI products competing for business customers. Pricing is aggressive because everyone's chasing adoption. Terms are generous because they need users. The market looks like a buyer's market and in some ways it is.

That's not the permanent state of affairs.

When a market consolidates - and AI tooling will consolidate, because the compute costs create massive scale advantages and most players will either fold or get acquired - pricing power shifts to whoever's left. The customers who built deep dependencies on a specific platform during the growth phase are the ones who pay for it in the consolidation phase.

It's happened in every previous wave of enterprise software. CRM, ERP, marketing automation - in each case, the scrappy competitors offered great deals to build market share, then the market consolidated around two or three players who gradually raised prices and locked in switching costs. The customers who signed up early because it was cheap often ended up with the worst deals.

AI is following the same pattern. The question is what you can do about it.

---

The technical answer is local deployment where it's viable.

Running AI models on your own infrastructure means you control the software version, you don't send your data to anyone else's servers, you're not subject to external pricing decisions, and you don't have a dependency on a vendor's continued existence. The tradeoff is that frontier model capability usually isn't available locally - you can run very good open models, but they're not as capable as the top commercial offerings.

For a lot of business use cases, "very good but not frontier" is completely fine. Internal document Q&A, meeting summarisation, first-draft writing, code assistance, data analysis - these don't require GPT-4 level capability. A well-configured local model on decent hardware does the job, costs nothing per API call, and keeps your data entirely under your control.

For use cases where you genuinely need frontier capability - complex reasoning, multi-step research, sophisticated analysis - that probably means a commercial API. Just go in with eyes open about the dependency you're creating.

---

The data question is separate from the hosting question and in some ways more important.

When you use a cloud AI tool, the data you put into it - your client information, your internal documents, your business logic, your competitive thinking - leaves your systems and enters someone else's. The terms of service determine what they can do with it. Most enterprise tiers include contractual protections against using your data for training. Most consumer and SME tiers don't.

The specific risk isn't usually that a human at the AI company is reading your business strategy. It's more diffuse. Your inputs contribute to model improvement in ways that might be hard to track or reverse. In a data breach, your inputs might be in the exposed data. Regulatory changes might create liabilities for data you provided years ago under less regulated conditions. A future acquirer inherits access to years of your data under terms you agreed to with the original company.

None of these are catastrophic on their own. The aggregate risk over years of deep dependency is real enough to be worth managing deliberately.

The practical thing is to run a 10-minute audit of every AI tool your business uses. What data goes into it? What do the terms say about that data? What would happen if the vendor disappeared tomorrow or doubled their prices? Which of these tools are you genuinely dependent on versus which are conveniences?

Most businesses haven't done this. It takes an afternoon and it tells you a lot about where your real risks are.

---

The longer-term answer for businesses that want genuine control over their AI capability is building around open-source models and open infrastructure.

This is more technically involved than buying a SaaS product. It requires someone who knows what they're doing - either internally or as a consultant. It's not the right answer for every business today. But for businesses that are making AI central to their operations, the argument for owning the infrastructure gets stronger as the dependency deepens.

The open-source AI ecosystem has advanced enormously in the last two years. Models that would have been commercially unviable to run locally a year ago are now practical on mid-range hardware. The tools for deployment, fine-tuning, and management are more accessible. The capability gap between open and commercial models is narrowing on most practical tasks.

A business that builds on open infrastructure owns its AI capability the same way it owns its other systems. It can update, customise, and migrate without vendor permission. It pays for hardware and expertise, not API calls and annual subscription increases.

That's a different kind of cost profile - higher upfront, lower ongoing - and a fundamentally different risk profile.

---

The question I'd ask about any AI tool your business relies on: if this vendor didn't exist tomorrow, what would you do?

If the answer is "we'd be significantly disrupted and it would take months to recover," that's a dependency worth managing down. Diversify across vendors. Explore local alternatives. Document your workflows so they can be rebuilt if needed. Don't let a single external platform sit at the critical path of your business without a recovery plan.

If the answer is "we'd find an alternative in a week," fine. That's a healthy level of dependency on a useful tool.

The goal isn't to avoid AI tools - that's commercially self-defeating. It's to use them without creating dependencies that someone else will eventually be able to charge you a fortune for.

Ownership matters. In every other part of your business, you know what you own and what you rent. Your AI stack deserves the same clarity.
