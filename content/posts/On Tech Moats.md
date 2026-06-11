+++
title = "On Tech Moats"
date = "2026-06-09"
+++
## On Tech Moats

As of the writing of this article, I work at Lucio - a legal AI tool. At the core, we are a Claude
for lawyers. This means that we get asked about how our products are different from Claude and ChatGPT.
If we are using the same foundational models, how do we compete with these bigger players? Is there
any moat? What about bigger players in the same space?
These questions have only become more pointed recently, with Claude expanding into legal and the
release of Mike OSS.

Our organization is just an example, but this question of moats applies to almost all AI companies
in the world right now. There seems to be no true technical moat, almost no SAAS product today really
has something that others can't copy. To me it also seems that this has been the case for a while now,
even pre-AI. AI has just made getting to a viable product faster, which has made it evident that there
is no moat in the traditional sense. However it is a fact that some companies are doing far better
than others - part of this can be explained by them being first, having better distribution, better
service and so on. These factors are generally harder to copy than the product itself, they require
a different kind of expertise.

The argument I'm going to make is that engineering and product require a similar kind of expertise,
that the moat lies there, and not in the final product itself.

Let me give a little background on Lucio's journey.
Over the last couple of years we have had the opportunity of releasing multiple features and products.
Some worked, some didn’t - but we started to notice unique quirks and patterns that lawyers had when
using Lucio. We spoke to our users a lot, some of them had wonderful ideas on features and improvements
they wanted - most of which stuck and are a part of our product right now. We gradually began to
develop a strong intuitive sense of how lawyers think and interface with software. This tacit knowledge
helped us build products that lawyers want to use over a general purpose tool like GPT.

It is evident that the competitive axiom is not “Who has the smartest model”. Building a good legal
tool is not a model intelligence issue, it's a design and engineering problem. It is an understanding
of the end-to-end legal workflows. It is knowledge of legal reasoning patterns, review habits, drafting
expectations and interaction patterns. It is the fact that this knowledge permeates through our whole
organization, including the engineering team.

Granted, the end product that comes from this understanding is "copyable" - but only in the
superficial sense. The underlying judgement system is not. New competitors can imitate visible
artifacts, but do not have the context of:
Why certain choices were made and what was intentionally omitted and
Which tradeoffs matter

This is true for any company. However, having this context creates 2 main forms of compounding
advantage:

Faster iteration velocity: We can distinguish signal from noise faster and which friction points to
prioritize. As an example, time from feature plan to production for a feature that lets you draft in
2 languages simultaneously was less than 2 weeks.
Product coherence: Legal work is highly contextual. It’s easier to copy isolated features but miss
the integrated experience. We have a feature that lets you enhance your prompt while you’re typing
it out - getting this feature discovered and adopted by lawyers in particular requires a deep 
understanding of what user experience patterns they are used to in the current version of the product,
as well as other products that they use.

Here is a concrete example:
Let us take citations as a problem. Citing back to source text is not as easy as it first seems.
There are multiple issues that arise. The language model tends to make mistakes regurgitating exact
text from the document when the context is long, the document you open and see on the web app is
most times different from the source document format (due to certain constraints I won’t go into
right now) and what the language model sees is a structured, processed version of the document
content derived from the source document - as opposed to its raw text.
Because of all these issues, highlighting the source clause/section/paragraph is not as simple as
doing a reverse string search (which is also slow). I cannot elaborate on the exact technique we
employed to solve this, but to work through the problem we had to think about the fundamentals of
what citations are to lawyers - what about them is so powerful and what are the underlying attributes
that make them valuable. The result is that users are able to reliably get precise citations back to
the exact page and section of the document.
 
The truth.
This much is clear by now - domain specific products like Lucio have real engineering advantage over
a general purpose tool and over someone who is not already into building products for that domain,
but it is only a temporal advantage. What about the companies who have been building legal products
for some time, maybe the same time as us - do we not have an advantage over them?

Clearly not. However, the fact of the matter is that as things stand, adoption rates for all of the
leading products in the legal AI space are more or less the same. This should tell us something
about moats.
