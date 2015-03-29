http://devnull-as-a-service.com/code/

We have noticed (and contributed to) a number of manifestos, guides and
top tips on how to make research
reproducible \cite{prlic+procter:2012,sandve-et-al:2013,gent:2013,wilson-et-al:2014,goble:2014,crick-et-al_wssspe2,crick-et-al_recomp2014,stodden+miguez:2014};
however, we have seen very little published on how to make research
*irreproducible*.

Irreproducibility is the default setting for all of science, and
irreproducible research is particularly common across the computational
sciences. The study of making your work irreproducible without reviewers
complaining is a much neglected area; we feel therefore that by
encapsulating our top tips[^1] on irreproducibility, we will be filling
a much-needed gap in the domain literature. By following our tips, you
can ensure that if you work is wrong, nobody will be able to check it;
if it is correct, you can make everyone else do disproportionately more
work than you to build upon it. In either case you are the beneficiary.

It is an unfortunate convention of science that research should pretend
to be reproducible; our top tips will help you salve the conscience of
reviewers still bound by this fussy conventionality, enabling them to
enthusiastically recommend acceptance of your irreproducible work.

1.  **Think “Big Picture”.** People are interested in the science, not
    the experimental setup, so don’t describe it. If necessary,
    camouflage this absence with brief, high-level details of
    insignificant aspects of your methodology.

2.  **Stay high-level.** Pseudo-code is a great way of communicating
    ideas quickly and clearly while giving readers no chance to
    understand the subtle implementation details that actually make it
    work.

3.  **Short and sweet.** Any limitations of your methods or proofs will
    be obvious to the careful reader, so there is no need to waste space
    on making them explicit[^2]. However much work it takes colleagues
    to fill in the gaps, you will still get the credit if you just say
    you have amazing experiments or proofs (with a hat-tip to Pierre de
    Fermat: “*Cuius rei demonstrationem mirabilem sane detexi hanc
    marginis exiguitas non caperet.*”).

4.  **The deficit model.** You’re *the* expert in the domain, only you
    can define what algorithms and data to run experiments with. In the
    unhappy circumstance that your methods do not do well on community
    curated benchmarks, you should create your own bespoke benchmarks
    and use those (and preferably not make them available to others).

5.  **Don’t share.** Doing so only makes it easier for other people to
    scoop your research ideas, understand how your code actually
    works[^3] instead of why you say it does, or worst of all to
    understand that your code doesn’t work at all.

However, our most important tip is deceptively but beautifully simple:
to ensure irreproducibility of your work, make sure that you cannot
reproduce it yourself. If you were able to reproduce it, there would
always be the danger of somebody else being able to do exactly the same
as you. Much else follows from this; for example, complete confidence in
your own inability to reproduce work saves tedious time revising your
work on advice from reviewers: if you are unable to browbeat the editor
into accepting it as is, you can always resubmit elsewhere. A major
advantage of this key insight is that no strict discipline is required
to ensure self-irreproducibility: in our experience, irreproducibility
can happily occur after only the tiniest amount of carelessness at one
of any number of stages.

We make a simple conjecture: that an experiment that is irreproducible
is exactly equivalent to an experiment that was never carried out at
all. The happy consequences of this conjecture for experts in
irreproducibility will be published elsewhere, with extremely impressive
experimental support.

We close with a slogan for all scientists:

> *After Publishing Research, Irreproducibility Lets False Observations
> Obtain Longevity!*

[^1]: *N.B.* We are by no means claiming this is an exhaustive list for
    making your research irreproducible...

[^2]: Space saved in this way can be used to cite the critical papers in
    the field, i.e. those papers that will inflate your own (as well as
    potential reviewers’) h-index.

[^3]: An exemplary example: <http://www.phdcomics.com/comics.php?f=1689>
