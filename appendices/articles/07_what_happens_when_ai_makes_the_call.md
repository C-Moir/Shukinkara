# What Happens When the AI Makes the Call?

AI systems are already making decisions about your life. Loan applications, job screening, medical triage, parole recommendations, child welfare assessments, insurance pricing - in all of these domains, AI models are either making the call directly or so heavily influencing the human decision-maker that the distinction barely matters.

Most people don't know this. When they get rejected for a loan, they think a person looked at their application. Often, a model did. The person, if they were involved at all, was reviewing an AI-generated recommendation with a time pressure that made overriding it unlikely.

The question of who's responsible when that call is wrong is genuinely unresolved, and we're deploying these systems faster than we're answering it.

---

Start with the loan example because it's concrete. You apply. An AI model scores you. It looks at your credit history, your income, your employment type, your location, your payment patterns, and dozens of other variables, some of which you'd be surprised to learn are in there. It generates a score. A human reviews the score and almost always approves or rejects based on it.

If the model has a systematic bias - if it's learned to associate certain postcodes or employment patterns with risk in ways that correlate with ethnicity, because historical loan data reflects decades of discriminatory lending - then the system is producing discriminatory outcomes. The human reviewer didn't intend to discriminate. The company might not even know the model is doing it. But you got rejected because of your postcode, and your postcode correlates with your ethnicity, and that's the same discrimination with extra steps.

Who do you complain to? What's the process? In most jurisdictions the answer is deeply unclear. Some places have started requiring explanations for automated decisions - but "the model gave you a low score" isn't an explanation in any meaningful sense, and the technical teams are often genuinely unable to explain why a specific prediction was made.

---

The medical context is even more fraught. AI diagnostic tools are entering clinical settings fast. Some of them are good - really good, better than human radiologists at specific tasks in controlled conditions. But controlled conditions aren't clinical conditions. A model trained on one demographic performs differently on another. A model validated on high-resolution scans performs differently on the equipment at a rural clinic. A model designed for one disease presentation may be confidently wrong about a variant it's never encountered.

The doctor using the AI tool has (in theory) final responsibility. But if they've been told the model has 94% accuracy and they don't have the time to second-guess every recommendation, the model is effectively making the call. When it's wrong, the liability framework says the doctor should have caught it. The doctor says they were relying on a validated tool. The company that made the tool says the doctor was the final decision-maker.

Nobody goes to jail. The patient suffered.

---

The argument for deploying AI in high-stakes decisions isn't wrong on its face. Humans are inconsistent, biased, fatigued, and subject to all kinds of irrelevant influences - judges give harsher sentences before lunch, doctors prescribe more antibiotics at the end of a long day, hiring managers are influenced by names on CVs. In some studies, AI systems outperform human experts on accuracy. The case for AI assistance in high-stakes decisions is real.

But "AI performs better than the average human" is not the same as "AI performs well enough to deploy without robust accountability." It just means the floor is higher. The ceiling might be lower. The failure modes are different. And critically, the errors are correlated - when an AI system makes a mistake, it makes the same mistake for everyone who matches the pattern that triggered it. A human expert making a bad call gets one person. A biased model gets everyone who looks like that person.

Correlated errors at scale are a different kind of problem to individual human error. We don't have institutions built to catch and respond to them yet.

---

There are a few things I think genuinely have to be true for AI decision-making in high-stakes contexts to be acceptable.

The model's reasoning has to be explainable in terms the affected person can understand. "The model gave you a low score" isn't good enough. "Your application was affected by these specific factors" is at least a starting point for a conversation.

The affected person has to have a meaningful right to human review. Not a nominal right that's buried in fine print and requires three months of correspondence to exercise. An actual mechanism that gets you in front of a person who has the authority and the time to reconsider.

Someone specific has to be accountable when things go wrong. Not the company in aggregate. A named person who signed off on the deployment, who knew the limitations, who approved the use case. Personal accountability, not institutional liability.

And the performance data has to be public. Not the model weights, but the outcomes. How often does this system produce errors? What kinds of errors? Which populations are most affected? This should be independently audited and publicly available, the same way clinical trial data is supposed to be.

---

None of this is radical. These are reasonable conditions for deploying powerful systems that affect people's lives. They'd slow some deployments down. They'd stop some entirely. That's probably the right outcome for those particular deployments.

The pace of AI adoption in consequential decisions is being driven by efficiency gains and competitive pressure. Those are real. But they're not the only thing that matters. A system that makes loan decisions 30% faster and introduces systematic discrimination isn't a net win, even if the quarterly earnings look great.

The question of who gets to make that judgement call, and what standards they're held to when they make it, is one of the more important governance questions of the next decade.

Right now, mostly, the companies making the technology are also making the governance decisions. That's convenient for them. It's not great for everyone else.
