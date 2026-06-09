As of the writing of this article, I work at Lucio - a legal AI tool. At the core, we are a ChatGPT
for lawyers. We have always been asked about how our products are different from any general purpose 
chat like Claude even any other  legal tool. These questions have only become more pointed recently,
with Claude expanding into legal and the release of Mike OSS. The underlying question here is this:
What is our tech moat?

The truth is that there is no tech moat, at least not in the usual sense of the word. What I consider
to be our edge is a little more complex, and needs an understanding of what our engineering values
are and how they have been shaped.

Over the last couple of years we have had the opportunity of releasing multiple features and products.
Some worked, some didn’t - but we started to notice unique quirks and patterns that lawyers had when
using Lucio. We spoke to our users a lot, some of them had wonderful ideas on features and improvements
they wanted - most of which stuck and are a part of our product right now. We gradually began to
develop a strong intuitive sense of how lawyers think and interface with software.


So, what’s the moat then?

The competitive axiom is evidently not “Who has the smartest model”. Building a good legal tool is
not a model intelligence issue, it's a design and engineering problem. It is an understanding of the
end-to-end legal workflows. It is knowledge of legal reasoning patterns, review habits, drafting
expectations and interaction patterns. It is the fact that this knowledge permeates through our whole
organization, including the engineering team.

Granted, the end product that comes from this understanding is copyable - but only in the
superficial sense. The underlying judgement system is not. New competitors can imitate visible
artifacts, but do not have the context of:
Why certain choices were made and what was intentionally omitted and
Which tradeoffs matter

This is true for any company. There is no true technical moat, no product in any space today really
has something that others can't copy. However, having this context creates 2 main forms of compounding
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
This much is clear by now - domain specific products like Lucio have a real advantage over a general
purpose tool and over someone who is not already into building products for that domain, but it is
only a temporal advantage. What about the companies who have been building legal products for some
time, maybe the same time as us - do we not have an advantage over them?

Clearly not. However, the fact of the matter is that as things stand, adoption rates for all of the
leading legal products are more or less the same. This should tell us something about moats.
Technology is changing insanely fast and the world is having to adapt. The products that win long-term
won't be those with the best model or the most features today. They'll be the ones whose core product
philosophy and culture can absorb and withstand the changes in the world.
