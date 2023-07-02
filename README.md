# Problem statement

How do you know what to trust? With the rise of Large Language Models (LLMs) it becomes trivial to generate documents that are utterly believable. How then, do you determine fake content from real?

# Introduction

On the surface the issue appears to be an extension of the classic spam problem. That is, there's a profit motivation for producing false or misleading documents. At first this was an issue of tricking people into paying money to Nigerian princes and buying bills to "enhance" themselves in some way.

A hypothetical, what if I wanted to sell you something fake. In the past, I could setup a website and create a spamming operating; Sending out mass emails, setting up a spam operation on Facebook, etc. These have become relatively easy to thwart, as I have to spend time and money crafting messages to get through spam blockers. The spam blockers look for repetative content that doesn't appear to written by a person. But with LLMs, I can now launch a multi-pronged and organic-like spam campaign. I can customize emails to each individual user, based on what I can find out about them with a google search. I can post content on Facebook that is contextual, but also relates to selling my product. I can create fake testimonials, positive reviews, and organic content with ease. I can make an entire story centered around my fake product so it becomes very difficult if not imspossible to tell my fake content from real reviews, tesimonials, word of mouth, etc.

Spam filtering falls down on spotting on nearly perfect content. Say the spam filter can tell the difference between real human content and LLM content with some small margin of error. Given that a bad actor can figure out content that is accepted by the spam filter, they can then train an LLM on that content and produce near perfect content that emulates the real content. Thus, the filters success leads to its own uselessness over time. With nearly perfect content, a spam filter has to be arbitrarily precise to be worth using. Why? Because of cost. How much does it cost to produce high quality content with an LLM? Practically nothing. And so, in order for an such filter to be effective, it has to be effective enough to increase the cost of creating spam content above a threshold that prevents bad actors from producing. In other words, if a filter is so good that it can spot almost all spam content, why bother trying to make spam content in the first place? There are other ways of making money.

# Proposal

Given these difficulties in detection, I believe the way forward lies outside of traditional methods, and a new approach can be used: repute. That is, the reputation of a known author can be indicative of the accuracy of a document. Rather than spending time attempting to filter the signal from the noise, use a set of known good agents as a source of truth, and assume everything else is spam.
