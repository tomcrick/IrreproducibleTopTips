Top Tips to Make Your Research Irreproducible
==============================

The [Software Sustainability Institute](software.ac.uk) is proud to be associated with a major new paper on  *irreproducible research*.  The new paper is called *"Top Tips to Make Your Research Irreproducible"* by 
[Neil Chue Hong](http://software.ac.uk/about/people/neil-chue-hong), [Tom Crick](http://drtomcrick.com), [Ian Gent](http://ian.gent) and [Lars Kotthoff](http://4c.ucc.ie/~larsko/), and is published today (April 1st) on [arxiv](http://arxiv.org).  We present some excerpts of the paper with permission of the authors.  Readers are encouraged to read the [full version](ITT.pdf).

> We have noticed (and contributed to) a number of manifestos, guides and
top tips on how to make research
reproducible; 
however, we have seen very little published on how to make research
*irreproducible*.

> It is an unfortunate convention of science that research should pretend
to be reproducible; our top tips will help you salve the conscience of
reviewers still bound by this fussy conventionality, enabling them to
enthusiastically recommend acceptance of your irreproducible work.




> By following our tips, you
can ensure that if your work is wrong, nobody will be able to check it;
if it is correct, you can make everyone else do disproportionately more
work than you to build upon it. In either case you are the beneficiary.



> 1.  **Think “Big Picture”.** People are interested in the science, not
    the experimental setup, so don’t describe it. 
    
> 2.  **Stay high-level.** Pseudo-code is a great way of communicating
    ideas quickly and clearly while giving readers no chance to
    understand the subtle implementation details that actually make it
    work.

> 3.  **Short and sweet.** Any limitations of your methods or proofs will
    be obvious to the careful reader, so there is no need to waste space
    on making them explicit.
    

> 4.  **The deficit model.** You’re *the* expert in the domain, only you
    can define what algorithms and data to run experiments with. 
    
> 5.  **Don’t share.** Doing so only makes it easier for other people to
    scoop your research ideas, understand how your code actually
    works instead of why you say it does, or worst of all to
    understand that your code doesn’t work at all.
    
    
![Comic number 1869 from phdcomics.com](phd031214s.gif) ["Piled Higher and Deeper" by Jorge Cham
www.phdcomics.com](http://www.phdcomics.com/comics.php?f=1689). Used with permission.

> However, our most important tip is deceptively but beautifully simple:
to ensure irreproducibility of your work, make sure that you cannot
reproduce it yourself. If you were able to reproduce it, there would
always be the danger of somebody else being able to do exactly the same
as you.

As an example of how much progress can be achieved via irreproducible research, the authors have used an automated theorem prover to obtain a wonderful demonstration of the most important theoretical question in Computer Science: does P=NP?   What follows is a transcript from a virtual machine interaction with their prover. 

	vagrant@vagrant-ubuntu:~$ ./prove P=/=NP
  	  Attempting proof of: P=/=NP
      Proof successful. Statement is confirmed.
      11608 seconds required
      
In case the reader is concerned that no proof was given, they provide additional information as an option to the prover:

    vagrant@vagrant-ubuntu:~$ ./prove P=/=NP --verbose
      Attempting proof of: P=/=NP
      Proof successful. Statement is confirmed.
      13804 seconds required
        Proof: Cuius rei demonstrationem mirabilem sane 
        detexi hanc marginis exiguitas non caperet

To ensure the true irreproducibility of this proof we understand the authors of the paper have deposited the virtual machine with a service dedicated to ensuring irreproducibility, [/dev/null as a service](http://devnull-as-a-service.com/).

The authors conclude their paper with the following statement, which we believe sums up the benefits of truly irreproducible research:

> *After Publishing Research, Irreproducibility Lets False Observations
> Obtain Longevity!*

At the Software Sustainability Institute, particularly given the current state of research today, we recommend that all researchers read the paper if they wish to undertake irreproducible research.


