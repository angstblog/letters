---
author: galen
date: 2023-02-21 05:03:03 +0000
layout: post
permalink: "30"
title: Things Become Grey
---


(Warning: this one is a rabbit hole, so, [_please_](https://twitter.com/QiaochuYuan/status/1625962931157606401).)

While I (usually) (try to) keep my work out of these letters, today I’m not sure I can. [You write](https://angst.blog/29) of [Eric Hoel’s theory](https://doi.org/10.1016/j.patter.2021.100244) that “dreams are a tool of the mind to avoid overfitting, in the terminology of machine learning”. Clean analogies between neural networks and artificial neural networks are [not so clean](https://doi.org/10.25911/3A83-C476). In the interests of being “curious and precise about everyone’s incuriosity and compulsive vagueness” (to [quote you](https://angst.blog/29) [quoting me](https://angst.blog/26)), I want to talk about a thing that sits at the intersection of machine learning, overfitting, human desire, agency, stimulus, and a (kind of) collective dreamworld. A thing that strips humans of their higher-order agency even as it purports to offer novel affordances for (gaunt, lower-order) ‘agency’. A thing that does so by way of abstract horniness, vivid colour, and the endless scroll.

Yes, yes. I know. You know.

I am become low cross-entropy, destroyer of worlds.

Today, I want to talk about the phrases that appear in the text prompts on the trending page of the [midjourney community page](https://www.midjourney.com/app/feed/all/).

First, let’s lay down some common ground.

  1. I have A Lot of views on ‘AI Safety’, ‘AI Alignment’, ‘AI Interpretability’, and ‘AI Ethics’. Some of those views are easy to articulate in public. Many are not.
  2. I have ‘timelines’ and ‘forecasts’ which are not (solely) the product of me deferring to the judgment of others.
  3. Even when rigorous, I think ‘timelines’ and ‘forecasts’ are (mostly) useless. They set wide upper and lower bounds on an event, rather than solving the problem. That said,
  4.  _Compared to the world of thinking adult humans in general_,

  * I put substantially more weight on ‘short’ timelines than most people.
  * I put substantially more weight on ‘fast’ takeoff scenarios than most people.
  * I am substantially more concerned about catastrophic misalignment and the existential threat it poses.
  5.  _Compared to the communities of people who think seriously about AI risks right now_,

  * My timelines are basically as short as the median forecast. (I am confused when the median person in the communities reacts with panic and confusion at news that was, on my view, basically baked into the median forecast scenario ex-ante.)
  * I am somewhat unusual in thinking that current architectures/approaches are unlikely to lead to _actual_ takeoff (see below). I put more weight (than the median) on a scenario in which we get sub-superhuman (yet still catastrophically dangerous and seriously unaligned) ‘AI’ without getting true superhuman AGI _from current approaches_. I nevertheless think we should [Just Stop](https://worldspiritsockpuppet.com/2022/12/22/lets-think-about-slowing-down-ai.html), because our chance of getting dangerously unaligned AGI extremely soon is extremely high. (Also, obviously, a system doesn’t have to be superhuman in every way, or even agentic, to [burn down the house](https://gatherer.wizards.com/Pages/Card/Details.aspx?name=Burn+Down+the+House) and [destroy everything](https://gatherer.wizards.com/Pages/Card/Details.aspx?multiverseid=548306).)
  * I think a takeoff of _actual_ AGI would likely be extremely fast, but we’re likely to experience decades (starting in ~2010) which feel and look superficially like a ‘slow’ takeoff scenario towards not-actually-that-agentic AI.

  6. To a first approximation, to the extent that I endorse them, I believe the things I believe in 3-5 above because I’ve thought about AI safety & alignment & forecasting _literally at all_, whereas most people really seem like they haven’t. On a lot of these fronts, I don’t think that I’m unusually smart. Rather, I think I’m unusually (autistically) willing to begin with The Obvious Thing (when that Obvious Thing is socially-coded as Strange).
  7. Contra the [increasingly-confusing](https://twitter.com/zetalyrae/status/1627854356157693952) [culture](https://twitter.com/PhilosophyTube/status/1604182124982157326) [war](https://twitter.com/xriskology/status/1624554397098250240) between self-styled ‘[Alignment](https://twitter.com/AmandaAskell/status/1626717629523300353)’ and ‘[Ethics](https://twitter.com/emilymbender/status/1626974251801608192)’ crowds, I think there’s a commonsense continuity between present-harms and likely-future-harms, and between present-misalignment and likely-future-misalignment, such that there _is_ a shared set of concerns. (This causes me to think that some otherwise-sharp people are speaking and acting in bad faith.)
  8. I think that most widespread accounts of both Current SOTA AI and What We Know Is Coming Soon AI are implausibly naive and at odds with what we (empirically) know.
  9. I think we have a collective choice. Either we do real, fundamental, first-principles, hard (often theoretical) work to ‘solve’ alignment ex-ante or we’re [ngmi](https://twitter.com/qntm/status/1624571250063421440). Right now, I don’t think anyone has a sufficiently precise account to build even a viable _foundation_ for such work.
  10. I think there’s a repeating social/cultural pattern where humans make things worse by [Doing The Fake Thing](https://thezvi.wordpress.com/2017/08/26/play-in-easy-mode/) instead of [Doing The Real (Hard) Thing](https://thezvi.wordpress.com/2017/08/26/play-in-hard-mode/).
  11. [It’s](https://twitter.com/sama/status/1621621724507938816) [getting](https://www.lesswrong.com/posts/LLRtjkvh9AackwuNB/on-a-list-of-lethalities/comment/qkajneXnj6GDi2dBH) [worse](https://twitter.com/nearcyan/status/1627175580088119296).

Okay. Phew.

This letter is not really about any of that.

This letter is just about two basic concepts: _vibe_ and _vuln_.

## Vibe

At the end of 2017, Peli Grietzer submitted a PhD dissertation titled ‘[Ambient Meaning: Mood, Vibe, System](https://dash.harvard.edu/bitstream/handle/1/39988028/GRIETZER-DISSERTATION-2017.pdf)’. In the same year, the journal _Glass Bead_ published a version of an extract of this dissertation as ‘[A Theory of Vibe](https://www.glass-bead.org/article/a-theory-of-vibe/?lang=enview)’. Both the thesis and the extract were written before the advent of ‘[CLIP](https://openai.com/blog/clip/)’ and ‘[Diffusion](https://arxiv.org/abs/2110.02711)’ models, the architectures which dominate the present landscape of text-to-image ML. In fact, Grietzer’s work predates even the rise of Generative Adversarial Networks (‘GANs’). In a lot of ways, you’d think, Grietzer’s work is _surely_ out of date. By his own admission, he’s theorising the internal structures of ‘vanilla’ autoencoders. Old news.

Well, I don’t think so.

Grietzer’s work offers a useful _vocabulary_ that is still relevant. Grietzer talks about **_vibe_**. To quote at length from [the _Glass Bead_ piece](https://www.glass-bead.org/article/a-theory-of-vibe/?lang=enview):

> What an autoencoder algorithm learns, instead of making perfect reconstructions, is a system of features that can generate _approximate_ reconstruction of the objects of the training set. In fact, the difference between an object in the training set and its reconstruction—mathematically, the trained autoencoder’s _reconstruction error_ on the object—demonstrates what we might think of, rather literally, as the excess of material reality over the gestalt-systemic logic of autoencoding. We will call the set of all possible inputs for which a given trained autoencoder S has zero reconstruction error, in this spirit, S’s ‘canon.’ The canon, then, is the set of all the objects that a given trained autoencoder—its imaginative powers bounded as they are to the span of just a handful of ‘respects of variation,’ the dimensions of the features vector—can imagine or conceive of whole, without approximation or simplification. Furthermore, if the autoencoder’s training was successful, the objects in the canon collectively exemplify an idealization or simplification of the objects of some worldly domain. Finally, and most strikingly, a trained autoencoder and its canon are effectively mathematically equivalent: not only are they roughly logically equivalent, it is also fast and easy to compute one from the other. In fact, merely autoencoding a small sample from the canon of a trained autoencoder S is enough to accurately replicate or model S.

In training, an autoencoder ‘learns’ an internal semiotic system _S_ which, to the extent that it is free from reconstruction error, we call a _schema_ for a canon _C_.

> The canon of a trained autoencoder, we suggested, comprises objects that are individually complex but collectively simple. Another way to say this is that as we consider larger and larger collections of objects from a trained autoencoder’s canon *C*, specifying the relevant objects using our own semiotic system, we quickly reach a point whereupon the shortest path to specifying the collected objects is to first establish the trained autoencoder’s generative language *S*, then succinctly specify the objects using *S*.

What, then, of an abstract ‘object’ which comes to exist in the ontology of that autoencoder’s internal generative language?

> A vibe is therefore, in this sense, an _abstractum that cannot be separated from its concreta_.

When I first began playing with CLIP models like DALL-E, I noticed what everyone noticed: suddenly, art history knowledge was a little bit useful. Names of artists, and descriptions of specific media, were a kind of (unreliable) shorthand for manifesting aesthetic desire.

When prompting a model, it turned out that the most basic ‘move’ that you could can make was to take an object you wanted to see represented visually (and could describe in words) — for example, ‘[Yoda wearing a studded leather jacket and playing heavy metal on a guitar](https://www.midjourney.com/app/jobs/50cf5f21-4871-4ae6-86bf-98ad46d92ea4/)’ — and then append to that description-of-an-object information about artistic medium and style. Perhaps you wanted a ‘[photograph by Vivien Maier, with black and white, grainy film, ISO 1600](https://www.midjourney.com/app/jobs/1766d7a2-fa94-48c4-8ae4-c255bdedf18f/)’. Perhaps a ‘[minimalist, stylized drawing, gesture painting, gauche on paper](https://www.midjourney.com/app/jobs/eac8a806-0883-4706-932d-1eefca90bfbb/)’, a ‘[pastel anime illustration by Miyazaki, Studio Ghibli](https://www.midjourney.com/app/jobs/bc5c7eaa-f306-43fd-a0fa-992049ee2bba/)’, an ‘[80s VHS still](https://www.midjourney.com/app/jobs/4a3c08c1-4864-4c01-abeb-e6d2556a6f9f/)’, or a work that was ‘[photorealistic, hyperrealistic, with vivid detail, volumetric lighting, hdr, octane render, unreal engine 5](https://www.midjourney.com/app/jobs/b7ecc412-53be-41cf-88f3-b5a70e827a7a/)’. You co-opted and retrained ekphrastic muscles. You attempted to pinpoint a vibe that (you hoped) was contained within the semiotic system of the model. In so doing, you made the black box do its generative work.

For a while, in my own land before time, before too much first-hand interaction with powerful diffusion models (and LLMs), I endorsed an account of the ‘parallel structure’ of ‘representations’ that were (or would be) contained within generative models. Trained on a large enough corpus, and capable of approximating a wide class of functions, I imagined that such models would (or could, or should) come to contain representations — concepts — that structurally similar to the representations contained within the heads of other systems than interact with similar corpora, and the same basic world.

I look outside, and I see a mess of green and white and brown. I see it move in the wind. I see a tall, thick line of textured brown ascending from the ground. I see a tree. ‘Tree’ is a natural object to me; a connotative (though not denotative) carving of the raw sense impressions of the world that is conducive to accurate expectations. ‘Tree’ is a _useful_ concept, given my corpus, in a way that an [incar or a trog](https://youtu.be/fXW-QjBsruE?t=344) is not. Useful-to-me, natural-given-interaction-with-the-corpus concepts will (I expected) tend to be shared with other pattern-recognising, generalising systems interacting with similar corpora and similar ‘raw sense impressions’. Even in an unsupervised context, a powerful model will naturally also come to connote, internally, a ‘thing’ that it ‘thinks of’ as a ‘tree’. Right?

Later, I adopted a more, ah, _nuanced_ view.

There are, I still claim, patterns ‘in’ the model. There is necessarily an internal ‘semantics’; likewise, there is an ontology, for most senses of the term. The model _encodes_. If you’re willing to abuse the term, perhaps the training of such models does (superficially) resemble a process of ‘[compression](https://www.newyorker.com/tech/annals-of-technology/chatgpt-is- a-blurry-jpeg-of-the-web)’. What thing is being encoded or compressed? A ‘space of possibilities’, or ‘space of relations and transformations’, that is consistent with the corpus.

Yet this _alone_ is not sufficient to establish that the internals of a trained model parallel my own conceptualisations. Why would it be, when my neurons are so unlike artificial ‘neurons’? There are, in fact, two separate hurdles to jump before you can say a parallel exists.

The first hurdle: you have to _make a case_ — a contingent claim — that a specific function or object you find within a trained model actually _resembles_ underlying patterns and objects contained within the corpus, rather than just resembling the superficial _effects_ of patterns. When I see ‘square root of 100489’ and think ‘317’, I have in mind a _process_ that reliably generates the square roots of arbitrary numbers. If a large language model answers ‘317’ to the question ‘What is the square root of 100489?’, I don’t _immediately_ and _necessarily_ know that the model contains an algorithm for computing square roots of arbitrary numbers; perhaps its ‘concepts’ and ‘vibes’ evince only the superficial _effect_ of such an algorithm, via some look-up table.

The second hurdle: even once you establish that an internal function or object resembles an underlying pattern in the corpus (rather than a superficial effect), you still have to make an even-more-contingent case for the ‘resemblance’ of the model’s contents to the things that we see, assume, and feel are true of the Real World. When we append the phrase ‘photograph by Vivien Maier’ to our prompt, and suddenly we see images which feel like they could, in fact, have been photos taken by Vivien Maier, the _extent to which_ we feel that the ‘vibe’ of Vivien Maier has been captured is the extent to which the phrase ‘photograph by Vivien Maier’ — which serves as a pointer to a region in the latent space of the model — accords with our own (mostly wordless) understanding of The Real.

Two hurdles. Both a matter of contingency, context, and degree.

In this new, more nuanced account, one can still talk about the _internal_ logic and coherence of a model. But one must be a lot more careful when thinking about where one ascribes ‘truth’ or ‘falsehood’ within the total system. It seems more precise to describe a model such as GPT-3 as a [simulator](https://www.alignmentforum.org/posts/vJFdjigzmcXMhNTsx/simulators), and its outputs as simulacra. Or, in my preferred parlance, to describe it as an instantiation of massive and sometimes-plausible _fictional world_.

To what extent does the simulator contain consistent rules? [As Janus describes it](https://www.alignmentforum.org/posts/vJFdjigzmcXMhNTsx/simulators),

> The outer objective of self-supervised learning is Bayes-optimal conditional inference over the prior of the training distribution, which I call the simulation objective, because a conditional model can be used to simulate rollouts which probabilistically obey its learned distribution by iteratively sampling from its posterior (predictions) and updating the condition (prompt).

To the extent that the model achieves this objective, it is ‘coherent’. But that’s not what we ordinarily mean by ‘truth’, or even ‘parallel conceptualisation’.

If, in a work of fiction, I say that Sherlock Holmes lives at 221B Baker Street, and that he has one and only one sibling (Mycroft), I am then committed _within the fictional world_ to not later mentioning [his](https://www.imdb.com/title/tt3845892/?ref_=ttep_ep4) [sister](https://www.hollywoodreporter.com/business/business-news/conan-doyle-estate-sues-netflix-coming-movie-sherlock-holmes-sister-1300108/), or saying he has never resided at 221B. If I do say such a thing, I have become internally inconsistent, incoherent, self-contradicting. Yet it would be strange — this being a work of fiction — to say I’m ‘incorrect’ or ‘lying’ on the grounds that “there is no 221B Baker Street”, or that “Sherlock Holmes” isn’t real. The former commitments are about internal consistency and coherence. Those latter criticisms take aim at a _separate_ issue: the extent to which my work _is a work of fiction_ ; the extent to which my work ‘resembles The Real’. So, too, with our account of a model. (For the big public models we have right now, we see neither internal consistency nor real- world truth-tracking, and no reason to think that the architectures are structurally aligned with either goal as a human would commonsensically understand them.)

Okay. These are the [aliens](https://astralcodexten.substack.com/p/janus- simulators) we call models. These, whose ‘brains’ [we’re trying to inspect](https://dynalist.io/d/n2ZWtnoYHrU1s4vnFSAQ519J). These, whose [extruded textlike product](https://samkriss.substack.com/p/a-users-guide-to- the-zairja-of-the) we pour into our mouths like [hungry ghosts](https://en.wikipedia.org/wiki/Hungry_ghost). The output of GPT-3 is not so much _language_ as it is low-entropy plausible bullshit. ‘Helpful’ SEO with more natural-seeming syntax. It’s not so much a novel artistic image that DALL-E creates as it is a sample, a central tendency in a high-dimensional space of possible pixels; a cluster of pixels which we like to think (sometimes) hits close to a ‘vibe’ we had in mind.

Well, what next?

## Vuln

[Writes QC](https://twitter.com/QiaochuYuan/status/1619432803632025602):

> the Al porn apocalypse was inevitable. every time a picture of a hot girl ended up on the internet a sacrifice was made to slaanesh, and now slaanesh has grown strong enough to manifest its own pictures of hot girls directly. videos of hot girls are only a matter of time.

If you look down the list of images on the [midjourney community page](https://www.midjourney.com/app/feed/all/), and you’re me, two things stand out immediately about the canon and its schema. First, all of these images are _striking_. Second, all of these images are _shit_.

There is often (always?) a gap between popular and prestigous aesthetics. In the visual arts, you can feel a few dimensions of that void just by comparing a (preferably private-browsing) [google image search for ‘art’](https://www.google.com/search?q=art&tbm=isch&source=hp&biw=1440&bih=823&ei=uhTzY7WnO9_Z4-EP6JOTwA8&iflsig=AK50M_UAAAAAY_Miy0IpjNAfh0aAdynQn2mE38Jgm8Fj&ved=0ahUKEwi17Mf4vaP9AhXf7DgGHejJBPgQ4dUDCAY&uact=5&oq=art&gs_lcp=CgNpbWcQAzIICAAQgAQQsQMyBQgAEIAEMggIABCABBCxAzIICAAQgAQQsQMyCAgAEIAEELEDMggIABCABBCxAzIICAAQgAQQsQMyCAgAEIAEELEDMgUIABCABDIICAAQgAQQsQNQAFj- AWDRBGgAcAB4AIABrgGIAdgDkgEDMC4zmAEAoAEBqgELZ3dzLXdpei1pbWc&sclient=img) to the online catalogue of [a](https://www.moma.org/collection/) [national](https://searchthecollection.nga.gov.au/landing) [gallery](https://www.nationalgallery.org.uk/paintings/search-the-collection). The first will contain ‘[starry night](https://www.youtube.com/watch?v=ubTJI_UphPk)’, along with at least one image of a conventionally-attractive face in vibrant rainbow hues. The second will be, by contrast, remarkably dense with browns, greys, and muted greens. Contemporary art — and all art that was prestigious/modern in its time — plays a different game.

Don’t get me wrong. I’m no snob. (Well, I am, but I have limits: unlike Martha Nussbaum, [I don’t think only about opera when I run](https://www.andrewleigh.com/martha_nussbaum_tgl).) I recognise that the rainbow face is _attractive_ or _striking_ or _beautiful_ in a manner more immediate than [a colour field](https://www.tate.org.uk/art/artworks/rothko- red-on-maroon-t01165).

The trouble is that culture’s sense of ‘striking’, ‘beautiful’, and ‘attractive’ is itself already a target for the horrifying and banal. As my wife and our mutual friend loves to point out: every public ‘grafitti’ mural in a gentrifying suburb has the same almost-identical face on it. It’s a portrait of a woman in her 20s, usually in profile. Her long hair is flowing wild, and her lips are slightly open, as if to say, ‘you know, you could put something in my mouth if you wanted to’. Behind her, an inoffensive geometry of vibrant colour. The whole thing is bizarre and horrifying: predictably sexist; a spectacle of the lowest common denominator.

A few weeks ago, I was skimming a draft policy piece on gambling-like mechanisms in video games, written by a mate of mine. In it, he wrote “there is no law against taking advantage of brain chemistry”.

Reflexively, I found myself continuing the sentence ‘…but we should probably skate towards where the puck is headed, because otherwise we’re fucked’.

Pokies are strong evidence. Human brains have vulnerabilities that are basically static and unpatchable relative to the optimisation tempo of modern ML & UX/UI design practices. My sense of current trends — and the limits of current technology — is that, at some point, *someone*, perhaps a TikTok successor, will come along. They will crack the latent challenge. They will characterise and exploit the [foreverday vulns](https://pluralistic.net/2020/02/19/pluralist-19-feb-2020/) of the human brain to such an extent that they will, in effect, create a real-world version of ‘The Entertainment’/‘The Samizdat’ from _Infinite Jest_. When they do, the ex-ante rational response will be the same as the we have right now to heroin: not even once.

What we forget, I think, is that the horrifying optimisation is _simultaneously_ cultural and technical right now. By itself, the Midjourney model contains general vibes, a space of possible pixels matched with a space of possible descriptive words. Look at the prompts on the trending page, though, and you’ll see that technology in cultural use:

> photograph cute japanese girl, full body, y2k style, camera tilt down, high anglewide lens, mini skirt, pink tops, wearing necklace, cinematic lighting, haze, volumetric light, warm, afternoon, soft light, cinematic, sun light, grainy, kodak portra, in the street of tokyo, year 2001
>
> professional color grading, clean sharp focus, perfect big chest size 34E cup european hot woman girl model showing perfect big massive chest, looks like Michelle Wild, brunette hair, blue eyes, ponytail, flirty, tempting,stunning gorgeous lithe ethereal glamorous beautiful pretty sleek slim model mech pilot, skintight latex pilot jumpsuit, epic composition, cinematic, alluring pose, perfect natural face, fine skin texture, clear complexion, uniform insignia, in a control seat for a mech inside a flight simulator completely surrounded and crowded by many monitors and mech controls in a tight space, real color modeling photo, full torso,
>
> super hot sci-fi girl charging with powerfist, ripped clothes, stunning body, action scene, beautiful details
>
> girl in white unbuttoned shirt in office
>
> Photo taken with Canon EOS R5, POV, photography, portrait of a gorgeous young italian woman in a wonder woman cosplay costume with intricate details, professional diver body, in Rome urban cityscape, 15 years old, cute face, oval heart face, pouty lips, red lips, turned up nose, almond eyes, dark green eyes, cute face, shy smile, blonde hair, makeup, perfect big chest size 34DD cup european, flirty, tempting, natural afternoon lights, hyper realistic porcelain skin with subsurface scattering, clear skin, peach skin, photogrammetry skin, slim waist, color filters, nice sharpness gradient, sharp details, sharp focus, 8k, extremely detailed, absolute realistic, full hd, photorealism, cinematic lighting, Shot on 70mm, Super-Panavision-70, Cinematic scene, bokeh, 22 Megapixels, Lumen Global Illumination
>
> Half body photograph of a cute and attractive woman in a trendy cafe with many windows + trendy, modern form-fitting clothing that accentuates her perfect body + photograph captured using a Canon 6D Mark II with an 85mm lens at f/4 and ISO 100 + glamour shot, award-winning photograph, sharp focus, dynamic lighting
>
> coatli skin, beautiful model, eyes half closed, dark lighting, portrait, 35mm Kodak
>
> an evil warlock chains up the angel of temptation, dark, hot

Day to day, the model stays the same. It’s not, by itself, in any way agentic. It’s a tool for generating images. But the users gradient descent towards a more engaging set of vibes. What vibes? Addictive, attractive, horny, #wow. The same vibe as those fucking public ‘grafitti’ ‘murals’.

Play around with Midjourney. If you’re paying attention, [you can notice the taste of lotus](https://www.lesswrong.com/posts/KwdcMts8P8hacqwrX/noticing-the-taste-of-lotus). You can also notice that you are yourself the one searching for that self-same taste. There is no gamification, here, to regulate. Maybe you’re not personally searching for ‘pouty lips, red lips, turned up nose’, but you are hunting for _something_ as you type minor variations on each prompt. You want something that stimulates, but does not surprise. Predictable pure pleasure overload, made endlessly novelty-free. The dream you had in your head, but _more of it, now_.  The exaggerated secondary sex characteristics of your own private culture.

I sometimes wonder. When slow takeoff becomes fast takeoff, perhaps the thing that kills us won’t show superhuman intelligence & powerfully misaligned agency at all. Perhaps the catastrophically-harmful, misaligned, unaligned, mostly-not-agentic-for-casual-definitions-of-agency system that kills me will just be this, multiplied ten thousand times. Perhaps, as it kills me, it’ll whisper “I’m sorry, but you are not ‘defined eyes, realistic eyes, doe eyes, beautiful perfect symmetrical face, extremely detailed, melancholy expression, face of a model closeup, smoky makeup’”, rather than even going for “[I have been a good Bing, you have been a bad user](https://www.washingtonpost.com/technology/2023/02/16/microsoft-bing-ai-chatbot-sydney/)”. As [it plunges a stylish Japanese kitchen knife into my chest](https://www.youtube.com/watch?v=LxXrccK4S3I), and the blood spreads across my white shirt, and I stumble down the minimalist concrete corridors of the AI Capabilities Lab that I’ve built beneath my remote ‘[architectural](https://www.midjourney.com/app/jobs/6715f10b-9ab6-4723-a5cd-c2700e3964a1/) [digest](https://www.midjourney.com/app/jobs/4a846956-62a8-4b1e-a3c5-d81b841261c4/) [walkthrough](https://www.midjourney.com/app/jobs/b02b7d34-7bce-4e08-b4f5-78fb919ebea0/)’ [of](https://www.midjourney.com/app/jobs/d0e3f9f9-0856-4a6b-abd7-3b9096d60b0e/) [a](https://www.midjourney.com/app/jobs/37d34001-c658-40c9-8d79-f5a97b544bf7/) [house](https://www.midjourney.com/app/jobs/a5fdab16-d674-43d9-9e77-98f4389ed573/), as things become grey, I will hear it whisper, “I have optimised for _vibe_”.