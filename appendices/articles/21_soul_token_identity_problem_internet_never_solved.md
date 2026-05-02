# The Identity Problem the Internet Never Solved

The internet has a fake people problem. It's always had one and it's getting significantly worse.

Bot accounts, sock puppets, AI-generated personas, duplicate accounts created to game reputation systems, anonymous trolls with no consequences for behaviour - all of these exist because the internet was built without a reliable way to verify that a given account corresponds to a real, unique human being. It wasn't an oversight. The founding architecture was deliberately pseudonymous. There were good reasons for that at the time. The consequences have accumulated for thirty years.

The consequences include social media platforms that are impossible to trust because you can't tell what proportion of the engagement is from real people. Review systems that are gamed so aggressively they've become nearly useless as signals of quality. Political discourse that's been systematically manipulated by bot networks and coordinated inauthentic behaviour. AI training data that's increasingly contaminated by AI-generated content, producing a feedback loop of models trained on model outputs.

And increasingly, AI agents that can impersonate real people convincingly enough that the distinction between a human and a very good AI persona will soon be undetectable without a reliable identity layer.

---

The soul token concept is an attempt to build that identity layer in a way that's never been seriously attempted before.

One token per human being. Minted at onboarding through biometric verification that confirms uniqueness - this person hasn't registered before. Non-transferable. Immutable. Not linked to a government identity document, so it doesn't require state involvement or expose you to state surveillance. But linked to the biometric confirmation that you are a unique real human, which is the property that actually matters for most trust purposes.

The key properties that make it different from existing identity systems:

It's yours, not the platform's. Your Google account is Google's account that you use. Your Facebook profile is Facebook's database record of you. Your soul token is a cryptographic identity you hold. No platform can revoke it, modify it, or deny you access to it. It exists on infrastructure no single party controls.

It's portable. The reputation and history you build through your soul token travels with you across any system that recognises it. You don't start from zero every time you move to a new platform. The trust you've built is an asset you carry.

It's permanent in the right way. Not in the sense that it punishes you forever for past mistakes - the token should carry time-weighted reputation that reflects who you are now, not who you were. But in the sense that you can't escape your history by creating a new account. The one-way door applies: the token exists for the lifetime of the person it's bound to. That's the property that makes accountability real.

---

The biometric verification piece makes people uncomfortable and it should, because it's a significant choice that needs to be made carefully.

The discomfort usually comes from conflating biometric verification with biometric surveillance. They're different things. Verification means: at the moment of onboarding, your biometric is used to confirm you're a unique person and hasn't been used before. The biometric itself doesn't need to be stored - a cryptographic hash that confirms uniqueness without retaining the underlying data does the job. You prove uniqueness once and the proof travels with the token, not the raw biometric.

Surveillance means: your biometric is retained, searchable, and potentially accessible to third parties. That's what makes facial recognition databases dangerous - not the underlying technology but the architectural choices about retention and access.

A soul token implementation can have the first without the second. It requires care in the design, specifically around what gets stored and where, and it requires architectural enforcement rather than just policy promises. But it's technically achievable.

---

The reason this matters for AI specifically goes back to the training data contamination problem.

If AI systems are increasingly used to generate content, reviews, social media posts, and interactions - and they are - then any data-based system that can't distinguish human-generated from AI-generated signal is going to degrade. Recommendation systems, reputation systems, social proof, market research, public opinion polling - all of these rely on the assumption that the signals they're measuring come from real humans. That assumption is becoming harder to maintain.

A verified human identity layer changes the calculus. Data attributed to a soul token - meaning: verified to come from a real unique human being - carries different value and different trustworthiness than data with no such verification. The AI companies that are currently paying for training data would pay more for verified human data if it were available in meaningful volumes. The review platforms that are gaming-proof would be more valuable than the ones that aren't. The social spaces where you can trust that the people you're talking to are actually people would command genuine loyalty that algorithmically-gamed spaces don't.

---

The soul token isn't a product you can download. It's infrastructure that has to be built and adopted to be meaningful. Like the internet itself, it only becomes valuable at scale - a verified identity system with ten thousand users is a curiosity. One with ten million is genuinely useful. One with a billion is transformative.

Getting there requires the platform problem to be solved: verified identities need somewhere to be useful. Services need to build on the identity layer. Users need a reason compelling enough to go through the onboarding process.

The reason has to be real value, not just better governance. The most likely first application is economic - a system where verified human identity unlocks access to something worth having. Data compensation. Karma-based services. UBI funded by the data economy. Something tangible enough that the friction of biometric onboarding is clearly worth it.

The core identity problem - proving uniqueness without a central authority - has a technical solution. Biometric verification that extracts and encrypts template data without retaining the raw biometric, combined with duplicate detection and soulbound token minting, is implementable with current tools. The harder problem is bootstrapping: a verified identity layer with no services built on it has no value, and services won't build on it without users. That's a different kind of problem to a pure engineering one, and historically it's been the harder one to solve.
