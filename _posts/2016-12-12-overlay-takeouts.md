---
layout: post
title:  "Overlay Takeouts"
date:   2016-12-13 22:12:37 +0100
---
{:cimg: style="text-align: center;"}

<script type="text/javascript"
            src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
</script>
            
## Abstract

Takeout or stealing patterns have been around for a long time already and are still very popular. On the other hand, working with even newly created takeout patterns feels like doing the same fourcount based patterns over and over again. We propose to break this stagnation by leveraging prechac created patterns and make both passers and manipulators do passing actions, that give the combined positive experience from 

Change "give the combined positive experience from" to "combine the fun of".

takeout- and prechac-patterns.

## Introduction

In juggling the term "takeouts" typically refers to one or more jugglers doing a pattern while an extra juggler (manipulator or middle-person)

You use both terms interchangeably in the article.  I think "manipulator" is becoming standard (and it's better in this article since that person isn't actually in the middle), so I would just use that.  

 interferes with that pattern, 

"stealing" a prop out of the pattern and replacing it with another.  (It's not just introducing an extra object.)

introducing an extra object. This style has been known at least as far back as 1995 (see [Charlie Dancey's Compendium of Club Juggling](https://www.amazon.com/Charlie-Danceys-Compendium-Club-Juggling/dp/1898591148)). 

It's way older than that.  See, for example, https://www.youtube.com/watch?v=sfnVE-fcatA for a 1987 reference (and it probably goes back way farther than that).  

These patterns were increasingly popular and were soon also performed on stage ([Take That Out performance starting in 2000](https://vimeo.com/161766794) and its sequel [Get The Shoe starting in 2002](https://www.youtube.com/watch?v=Yemkg_z7MAE)). Takeout enthusiasts have generated an enormous variety of complicated and beautiful patterns, many of them collected in [Aidan Burns' famous 'How to steal from your friends'](http://www.geocities.ws/aidanjburns/passing.html). An very systematic example of this style is [Bruno's Ace](https://www.youtube.com/watch?v=49Z7-wo_XtI&t=60s) - Brunos'

Bruno's

 Nightmare with two rotating manipulators.)

However, all these variations boil down to three club cascades with synchronous 4-count passes manipulated with substitutions, intercepts and carries, as [Warrens

Warren's

 article on Scrambled Passing Patterns](http://ezine.juggle.org/2014/05/26/scrambled-passing-patterns-and-takeout-notations-part-1/) explains, some 2-, 3- and 5-counts being the exception.

Another line of developing new interactions between jugglers is based on [Christophe Prechac's article on Symmetric Passing Patterns](https://www.passingdb.com/articles.php?id=13). He essentially extended the generative power of [siteswaps](https://en.wikipedia.org/wiki/Siteswap) to the passing world. This technique has been extensively investigated by the [Gandinis](http://www.gandinijuggling.com), leading to Sean's well known [Prechac explanation](http://www.owenreynolds.net/notation/Symmetric_patterns_C.pdf) and ultimately to the well known [Social Siteswaps DVD](https://www.youtube.com/watch?v=W_G74eLnK1U). A practical tool to generate these patterns is [PrechacThis](http://prechacthis.org). A denser compilation of takeout-inspired Prechac Siteswap patterns is the [Under Prechac routine](http://underprechac.de).

Yet, that branch is focused on symmetrical patterns, i.e. every juggler is doing the same pattern. In takeouts on the other hand, a base pattern is manipulated by someone how

who

 does something to the pattern. 

Our idea was to join these two lines of development: the running manipulators and unrestricted patterns. More specifically, instead of limiting the interactions to only three different ones between middle-person and passers and mostly four-count based passing, we looked at various periods for a pattern (3, 4, 5, 6) with no limitation on the number of passes and no limitations on selfs and passes (0, 1, 2, 3, 4 as selfs and 1p, 1.5p, 2p, 2.5p, 3p, 3.5p, 4p, 4.5p as passes).

The basic idea we explored is: Choose a Prechac passing pattern and _overlay_ it with a custom made manipulation siteswap (another Prechac pattern).

In the next section we introduce such a new pattern as an example to give a quick start to the broad idea. The section is followed by a deeper and more general explanation of the approach. By exploring a further example, with more of the intended features, we try to bring across the advantages that we found in this new technique.

## Motivating Example: Delightfull

Delightful (unless you were using the different spelling on purpose)

One well established takeout pattern is the so called [roundabout](https://www.google.de/search?q=roundabout+juggling&tbm=vid): a 6 club 4-count with a middle-person substituting passes and selves, where the middle-person swaps roles with a passer who will then become the new middle-person and so on. 

Based on this pattern we want to introduce our idea with a simple proof of concept. We chose to start out with a low amount of clubs (5 for the passers, 1 for the manipulator) and a not so demanding pattern [5 clubs, period 4](http://prechacthis.org/index.php?persons=2&objects=5&lengths=4&max=3&passesmin=1&passesmax=4&jugglerdoes=&exclude=&clubdoes=&react=&results=). We decided for [3p 3 1 3]("http://prechacthis.org/info.php?pattern=[p(3,1,5),p(3,0,3),p(1,0,1),p(3,0,3)]&persons=2&swap=[]&back=persons%3D2%26amp%3Bobjects%3D5%26amp%3Blengths%3D4%26amp%3Bmax%3D3%26amp%3Bpassesmin%3D1"). 

The passers face each other and all passes are straight, so for passers _A_ and _B_ the pattern looks like this:

![3p 3 1 3]({% include img param="3p313.png"%})
{:cimg}

We now add a manipulation pattern by first coming up with a solo siteswap (3 1 3 1) and then overlaying it to one of the passers by using Prechac's theory. This will allow the passer and the manipulator to share the 3 and transform it into a 1p, resulting in [3 1 1p 1]("http://prechacthis.org/info.php?pattern=[p(3,0,3),p(1,0,1),p(1,1,3),p(1,0,1)]&persons=2&swap=[]&back=persons%3D2%26amp%3Bobjects%3D3%26amp%3Blengths%3D4%26amp%3Bmax%3D3%26amp%3Bpassesmin%3D1%26amp%3Bpassesmax%3D1%26amp%3Bjugglerdoes%3D1p") between passer _A_ and manipulator _M_. _A_ and _M_ stand side by side and the 1p is going inside to outside:

![3 1 1p 1]({% include img param="311p1.png"%})
{:cimg}

If we include passer _B_ into the picture again, we see that _B_ continues with the passing pattern and _A_ does both, the passing pattern and the manipulation pattern at the same time:

![3p 3 1 1p]({% include img param="3p311p.png"%})
{:cimg}

Finally we have three different roles:

* _A_: 3p 3 1 1p
* _B_: 3p 3 1 3
* _M_: 3 1 1p 1

Overall this isn't clear to me.  In the starting pattern with no manipulator, A and B are doing staggered versions of the siteswap (A does 3p 3 1 3; B does 1 3 3p 3).  But in the final product they seem to be synchronized (both doing 3p at the same time).  How did that happen from the system?  Maybe I just need to keep reading, but so far, it's not obvious.

Ok, I wrote it out.  You mean that B does 1 3 3p 3 and M does 1 1p 1 3.  

A good way to get the pattern started is to let _A_ have two clubs in the right hand and start with the right hand into 3p 3 1 1p, zipping the 1 into a wrong end catch. _B_ and _M_ can react intuitively.

TODO Videolink static delightful

The runaround part (swapping roles) is almost as easily achieved as in the classic roundabout. Passer _A_ gives her last club to manipulator _M_ and walks over with one club to the other passer _B_, leaving _M_ as the new passer and becoming the new manipulator. Passer _B_ has to do a short pattern change, i.e. 3p 3 1 3 _3p_ 3 _3p_ 3, where the two-count style clubs are thrown to first the former passing partner _A_ and then to the new passing partner _M_.

TODO Videolink runaround delightful


## The General Principle

With this simple example in mind we will have a look at a set of more generic activities (algorithm), that will always generate valid patterns:

1. Start with a two juggler symmetric passing pattern with a length of _period_, that contains at least one _self_ where \\(self >= 1 + \frac{period}{2} \\).
2. Take a solo pattern of length _period_ containing _self_. Transform that _self_ into the \\(manipulation\\_pass = self - \frac{period}{2} \\).
3. Let the manipulator _M_ do the pattern from step 2, exchanging the _manipulation\_pass_ with _A_; let passer _B_ juggle the pattern from step 1; and let passer _A_ do the pattern from step 1 with _B_ plus, instead of _self_, the _manipulation\_pass_ exchanged with _M.
4. Optionally, walk around, swapping roles, e.g.
  - _M_ becomes a _B_ passer
  - _A_ runs to the other side and becomes a manipulator
  - _B_ then starts in role _A_.
  
  This makes it a lot more clear.  But I would still add something in step 3:  B and M are juggling their patterns with the starting points staggered appropriately from A.
  
  One small issue:  The word "plus" in step 3 is a little confusing; it makes me think we're adding two numbers together (as you do sometimes in prechac modifications).  So I would change it to "...let passer _A_ do the pattern from step 1 with _B_, except, instead of _self_...".

The total amount of clubs \\(n_{total}\\) equals the amount of clubs of the passing part \\(n_{passing}\\) plus the clubs of the solo version of the manipulation pattern \\(n_{solo}\\) minus 1, since the manipulator adds \\(n_{solo}\\) clubs but shares one club with a passer:

\\( n_{total} = n_{passing} + n_{solo} - 1  \\)

In theory, this always works. In practice, there are two things that one should bear in mind to avoid an unnecessarily hard pattern: a) Don't catch passes under 4s as this will often lead to timing issues; b) if you have a 1p or 1.5p make sure you can resolve the resulting wrong-end catch, by enforcing a 1 or 2 self on that 1.5p-club immediately before or after the 1.5p. You will find this tweak in the following example 

These are really helpful tips!  (Add a period or colon at the end of the sentence above.)

## Fully Fledged Example: Mission Impossible

Now that we have established the general approach, consider a pattern that incorporates more of the elements that we aimed for in the first place:

* It should be left-right-handed, hence period 5.

I would say, "hence with an odd period.  We'll use period 5."

* There should be a 1 1.5p, i.e. a "smash-in" preceded by a grip-correcting 1

Add a period.

* Not too difficult for the passers, i.e. 5 clubs, just one low pass.

Do you mean that low passes are hard, so we are making this easy by only having one low pass?  Or do you mean that all passes are hard, so we are making this easy by only having one pass, and it's easy because it's low?  I think you mean the first one, but it's not clear.  

This is what [PrechacThis offered us](http://prechacthis.org/index.php?persons=2&objects=5&lengths=5&max=4&passesmin=1&passesmax=1&jugglerdoes=&exclude=&clubdoes=1+4+or+2+4&react=&results=42).

Our first attempt is [4 2.5p 1 2 3]("http://prechacthis.org/info.php?pattern=[p(1,0,1),p(2,0,2),p(3,0,3),p(4,0,4),p(2.5,1,5)]&persons=2&swap=[]&back=persons%3D2%26amp%3Bobjects%3D5%26amp%3Blengths%3D5%26amp%3Bmax%3D4%26amp%3Bpassesmin%3D1%26amp%3Bpassesmax%3D1%26amp%3Bjugglerdoes%3D%26amp%3Bexclude%3D%26amp%3Bclubdoes%3D1%2B4%2Bor%2B2%2B4"). As always in odd-period patterns, one passer goes straight and one goes cross on the 2.5p

This makes it sound like the 2.5p only applies to the cross.  I would say, "the 2.5p implies that one passer goes straight and one goes cross...."

, which here is a floaty flat (aka "zap" or "joe pass").

![4 2.5p 1 2 3]({% include img param="42.5p123.png"%})
{:cimg}

[//]: # (<video width="640" height="360" controls preload="metadata" poster="42.5p123.png">
  <source src="missionImpossible.mp4#t=40s" type="video/mp4" />
</video>)                                       


The next step is to construct a manipulation pattern. [It must be period 5 and have a 1.5p in it](http://prechacthis.org/index.php?persons=2&objects=3&lengths=5&max=3&passesmin=1&passesmax=1&jugglerdoes=1.5p).

You skipped a step here.  The algorithm above says to find a *solo* pattern of length _period_ containing _self_.  Here you skipped right to a passing pattern that contained the right manipulation_pass.  

 In that list, there is [0 1 2 3 1.5p]("http://prechacthis.org/info.php?pattern=[p(0,0,0),p(1,0,1),p(2,0,2),p(3,0,3),p(1.5,1,4)]&persons=2&swap=[]&back=persons%3D2%26amp%3Bobjects%3D3%26amp%3Blengths%3D5%26amp%3Bmax%3D3%26amp%3Bpassesmin%3D1%26amp%3Bpassesmax%3D1%26amp%3Bjugglerdoes%3D1.5p"). It looks like this, again, with one passer doing straight and the other cross passes:

![0 1 2 3 1.5p]({% include img param="01231.5p.png"%})
{:cimg}

[//]: # (<video width="640" height="360" controls preload="metadata" poster="">
  <source src="missionImpossible.mp4#t=26s" type="video/mp4" />
</video>)                                       

When we overlay the two patterns, we end up with:

* _A_: 1 2 3 1.5p 2.5p
* _M_: 0 1 2 3 1.5p
* _B_: 1 2 3 4 2.5p

Now I have gotten used to your system and I know I have to stagger the starting points appropriately.  But I think for some readers it would be really helpful if you align these three rows with each other, e.g., A starts with the 1.5p, and M and B each start a half beat later with 2s.

The passers have to agree on who passes the 2.5p straight and who passes it cross. For the 1.5p, the manipulator can avoid the flat passes

When I first read "avoid", it sounded like we were trying to create a pattern that doesn't have those passes.  So I would probably say "avoid collisions with".

 to _A_ from _B_ best if she smashes the 1.5p straight, while the passer doing the overlay smashes the 1.5p _cross_. Note that in contrast to conventional takeouts the passer, too, has a smash-in.

Cool!

![1 2 3 1.5p 2.5p]({% include img param="1231.5p2.5p.png"%})
{:cimg}

We call this combination Mission Impossible, partly because it was surprisingly difficult to get your head around the overlay part (_A_), partly out of reverence for Lalo Shifrin's famous movie theme - one of the few widely known five fourth songs

songs in a 5/4 time signature

. Try chanting along 

with

the rhythm!

<iframe width="100%" height="450" scrolling="no" frameborder="no" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/70927998&amp;auto_play=false&amp;hide_related=false&amp;show_comments=true&amp;show_user=true&amp;show_reposts=false&amp;visual=true"></iframe>

Once you have the pattern solid you can move on to the Impossible Roundabout, matter of a second article. 

a matter for a second article

As an outlook 

preview

we can already outline the most important and difficult aspect, which is to be clear about what is cross and what is straight. There are some intricacies about starting, permutations and a peculiar role swapping irregularity - but we will cover these in a follow up post.

## Observations, Discussion

What we find most remarkable about this set of patterns is how hard it is to get ones

one's

 head around the overlay role (passer _A_). Even though in both examples all the bilateral
 
 two-person
 
  passing parts are fairly easy, it takes quite some time to manage both patterns at once. Naturally, this applies especially to odd period patterns, where you have to memorize
  
  learn the pattern
  
   once for the first half and another time when you switch hands.

However, and this is true for many takeouts and (mini) Prechac patterns - once you master the timing around the difficult throws like the 4s __and__ you don't have to think actively any more, you can get the pattern solid relatively quickly. And doing the pattern solidly then suddenly feels like being part of a clock work on the one hand and watching it with a detached kind of admiration at the same time on the other hand. This mix probably accounts for a significant amount of the attraction of juggling takeout patterns.

Very true!

The second observation worth noting is that the passers are aware of the manipulation, much in contrast to conventional takeouts where the manipulation is supposed to be transparent to the passers. 

Interesting point.

In our view this is not problematic, since in reality the passers are always aware of the manipulation - an intercepted self has even be called "pelf"

I would say "an intercepted self is even called a "pelf" to indicate that it is thrown gently (like a light **p**ass) towards the manipulator."  

 to indicate that it feels actually like a **p**ass. In contrast, our approach explicitly spells out the interaction between manipulator and passer, rather than assuming that it is transparent to the latter.

## Future Work

There are various intended activities, in order to cover more of this set of patterns. 

We have various future plans to cover more of this family of patterns.  

First of all we need a more solid description of the run around version of Mission Impossible. To do that, a closer comparison of these patterns with Aidan's and Ed's framework should help. We might be able to describe the run around aspect elegantly with that notation. Taking that idea further, it would be nice to have a general theory to turn our set of patterns into runarounds, which could possibly be as easy as confirming that Ed's notation can be applied in general.

The more practical way ahead is obviously to generate more interesting patterns, especially with slightly more clubs to eliminate situations where we could actually stop the pattern with two clubs for each person. Examples of that could be a manipulated "Why Not"/"Not Why"/"Why the hack"

I think you mean "What the heck".

 etc.

