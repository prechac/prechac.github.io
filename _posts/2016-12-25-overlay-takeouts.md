---
layout: post
title:  "Overlay Takeouts"
date:   2016-12-25 22:12:37 +0100
---
{:cimg: style="text-align: center;"}

<script type="text/javascript"
            src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
</script>
<link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">   

By [Florian Marienfeld](https://github.com/flowma) ([<i class="fa fa-github"></i>](https://github.com/flowma), [<i class="fa fa-twitter"></i>](https://twitter.com/JugglingFlo)),
Jochen Hänsel,
[Jochen Pfeiffer](https://github.com/jjochen) ([<i class="fa fa-github"></i>](https://github.com/jjochen), [<i class="fa fa-twitter"></i>](https://twitter.com/JochenPfeiffer)) and 
Tine Oymann. 
            
**_Takeouts_ or stealing patterns have been around for a long time already and are still very popular. Yet, working with even newly created takeout patterns feels like doing the same fourcount based patterns over and over again. We propose to break this stagnation by leveraging _Prechac_ based patterns and make both passers and manipulators do passing actions that combine the fun of takeout- and Prechac-patterns.**

<video width="640" height="360" controls preload="auto">
  <source src="http://juggling.tv/download/encoded/16242/-mission-impossible-passing-overlay-takeout.mp4" type="video/mp4" />
</video>                                 


## Introduction

In juggling the term "takeouts" typically refers to one or more jugglers doing a pattern while an extra juggler (often referred to as manipulator) "stealing" a prop out of the pattern and replacing it with another. This style has been known at least as far back as 1995 (see [Charlie Dancey's Compendium of Club Juggling](https://www.amazon.com/Charlie-Danceys-Compendium-Club-Juggling/dp/1898591148) and [Walter N. Long's Wally Walk](http://juggling.tv/7068)). These patterns were increasingly popular and were soon also performed on stage ([Take That Out performance starting in 2000](https://vimeo.com/161766794) and its sequel [Get The Shoe starting in 2002](https://www.youtube.com/watch?v=Yemkg_z7MAE)). Takeout enthusiasts have generated an enormous variety of complicated and beautiful patterns, many of them collected in [Aidan Burns' famous 'How to steal from your friends'](http://www.geocities.ws/aidanjburns/passing.html). An example applies this style in a very focused manner is [Bruno's Ace](https://www.youtube.com/watch?v=49Z7-wo_XtI&t=60s) -- Bruno's Nightmare with two rotating manipulators.

However, all these variations boil down to three club cascades with synchronous 4-count passes manipulated with substitutions, intercepts and carries, as [Warren's article on Scrambled Passing Patterns](http://ezine.juggle.org/2014/05/26/scrambled-passing-patterns-and-takeout-notations-part-1/) explains, some 2-, 3- and 5-counts being the exception.

Another line of developing new interactions between jugglers is based on [Christophe Prechac's article on Symmetric Passing Patterns](https://www.passingdb.com/articles.php?id=13). He essentially extended the generative power of [siteswaps](https://en.wikipedia.org/wiki/Siteswap) to the passing world. This technique has been extensively investigated by the [Gandinis](http://www.gandinijuggling.com), leading to Sean's well known [Prechac explanation](http://www.owenreynolds.net/notation/Symmetric_patterns_C.pdf) and ultimately to the well known [Social Siteswaps DVD](https://www.youtube.com/watch?v=W_G74eLnK1U). A practical tool to generate these patterns is [PrechacThis](http://prechacthis.org). A denser compilation of takeout-inspired Prechac Siteswap patterns is the [Under Prechac routine](http://underprechac.de).

Yet, that branch is focused on symmetrical patterns, i.e. every juggler is doing the same pattern. In takeouts on the other hand, a base pattern is manipulated by someone who does something to the pattern. 

Our idea was to join these two lines of development: the running manipulators and unrestricted patterns. More specifically, instead of limiting the interactions to only three different ones between manipulator and passers and mostly four-count based passing, we looked at various periods for a pattern (3, 4, 5, 6) with no limitation on the number of passes and no limitations on selfs and passes (0, 1, 2, 3, 4 as selfs and 1p, 1.5p, 2p, 2.5p, 3p, 3.5p, 4p, 4.5p as passes).

The basic idea we explored is: Choose a Prechac passing pattern and _overlay_ it with a custom made manipulation siteswap (another Prechac pattern).

In the next section we introduce such a new pattern as an example to give a quick start to the broad idea. This is followed by a deeper and more general explanation of the approach. By exploring a further example, with more of the intended features, we elaborate on advantages that we found in this new technique.

## Motivating Example: Delightful

One well established takeout pattern is the so called [roundabout](https://www.google.de/search?q=roundabout+juggling&tbm=vid): a 6 club 4-count with a manipulator substituting passes and selves, where the manipulator swaps roles with a passer who will then become the new manipulator and so on. 

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
* _B_: 1 3 3p 3
* _M_: 1 1p 1 3

Note that both _B_ and _M_ are staggered in reference to _A_, i.e. they are throw their passes to _A_ half a period shifted from _A_.

A good way to get the pattern started is to let _A_ have two clubs in the right hand and start with the right hand into 3p 3 1 1p, zipping the 1 into a wrong end catch. _B_ and _M_ can react intuitively.

<video width="640" height="360" controls preload="auto">
  <source src="http://juggling.tv/download/encoded/16241/delightful-passing-overlay-takeout.mp4" type="video/mp4" />
</video>

The runaround part (swapping roles) is almost as easily achieved as in the classic roundabout. Passer _A_ gives her last club to manipulator _M_ and walks over with one club to the other passer _B_, leaving _M_ as the new passer and becoming the new manipulator. Passer _B_ has to do a short pattern change, i.e. 3p 3 1 3 _3p_ 3 _3p_ 3, where the two-count style clubs are thrown to first the former passing partner _A_ and then to the new passing partner _M_.



## The General Principle

With this simple example in mind we will have a look at a set of more generic activities (algorithm), that will always generate valid patterns:

1. Start with a two juggler symmetric passing pattern with a length of _period_, that contains at least one _self_ where \\(self >= 1 + \frac{period}{2} \\).
2. Take a solo pattern of length _period_ containing _self_. Transform that _self_ into the \\(manipulation\\_pass = self - \frac{period}{2} \\).
3. Let the manipulator _M_ do the pattern from step 2, exchanging the _manipulation\_pass_ with _A_; let passer _B_ juggle the pattern from step 1; and let passer _A_ do the pattern from step 1 with _B_, except, instead of _self_, the _manipulation\_pass_ exchanged with _M_. _B_ and _M_ are juggling their patterns with the starting points staggered appropriately from _A_.
4. Optionally, walk around, swapping roles, e.g.
  - _M_ becomes a _B_ passer
  - _A_ runs to the other side and becomes a manipulator
  - _B_ then starts in role _A_.

The total amount of clubs \\(n_{total}\\) equals the amount of clubs of the passing part \\(n_{passing}\\) plus the clubs of the solo version of the manipulation pattern \\(n_{solo}\\) minus 1, since the manipulator adds \\(n_{solo}\\) clubs but shares one club with a passer:

\\( n_{total} = n_{passing} + n_{solo} - 1  \\)

In theory, this always works. In practice, there are two things that one should bear in mind to avoid an unnecessarily hard pattern: a) Don't catch passes under 4s as this will often lead to timing issues; b) if you have a 1p or 1.5p make sure you can resolve the resulting wrong-end catch, by enforcing a 1 or 2 self on that 1.5p-club immediately before or after the 1.5p. You will find this tweak in the following example.

## Fully Fledged Example: Mission Impossible

Now that we have established the general approach, consider a pattern that incorporates more of the elements that we aimed for in the first place:

* It should be left-right-handed, hence with an odd period. We'll use period 5.
* There should be a 1 1.5p, i.e. a "smash-in" preceded by a grip-correcting 1.
* Not too difficult for the passers, i.e. 5 clubs, just one pass and a low one at that.

This is what [PrechacThis offered us](http://prechacthis.org/index.php?persons=2&objects=5&lengths=5&max=4&passesmin=1&passesmax=1&jugglerdoes=&exclude=&clubdoes=1+4+or+2+4&react=&results=42).

Our first attempt is [4 2.5p 1 2 3]("http://prechacthis.org/info.php?pattern=[p(1,0,1),p(2,0,2),p(3,0,3),p(4,0,4),p(2.5,1,5)]&persons=2&swap=[]&back=persons%3D2%26amp%3Bobjects%3D5%26amp%3Blengths%3D5%26amp%3Bmax%3D4%26amp%3Bpassesmin%3D1%26amp%3Bpassesmax%3D1%26amp%3Bjugglerdoes%3D%26amp%3Bexclude%3D%26amp%3Bclubdoes%3D1%2B4%2Bor%2B2%2B4"). As always in odd-period patterns, the 2.5p implies that one passer goes straight and one goes cross, 2.5p being a floaty flat (aka "zap" or "joe pass").

![4 2.5p 1 2 3]({% include img param="42.5p123.png"%})
{:cimg}

The next step is to construct a manipulation pattern. [We start from a solo pattern of period 5 with a 4 in it](http://prechacthis.org/index.php?persons=1&objects=2&lengths=5&max=4&passesmin=0&passesmax=_&jugglerdoes=4&exclude=&clubdoes=&react=&results=).

Number one on that list is [0 1 2 3 4]("http://prechacthis.org/info.php?pattern=[p(4,0,4),p(0,0,0),p(1,0,1),p(2,0,2),p(3,0,3)]&persons=1&swap=[]&back=persons%3D1%26amp%3Bobjects%3D2%26amp%3Blengths%3D5%26amp%3Bmax%3D4%26amp%3Bpassesmin%3D0%26amp%3Bpassesmax%3D_%26amp%3Bjugglerdoes%3D4"). If we transform the 4 into a pass, we get 0 1 2 3 1.5p. It looks like this, again, with one passer doing straight and the other cross passes:

![0 1 2 3 1.5p]({% include img param="01231.5p.png"%})
{:cimg}

When we overlay the two patterns, we end up with:

| _A_:| 3 | | 1.5p | | 2.5p | |  1   | | 2   |
| _M_:| | 2   | |  3   | |  1.5p | | 0   | | 1 |    
| _B_:| | 1   | |  2   | |  3    | | 4   | | 2.5p |

The passers have to agree on who passes the 2.5p straight and who passes it cross. For the 1.5p, the manipulator can dodge the flat passes between _A_ and _B_ best if she smashes the 1.5p straight, while the passer doing the overlay smashes the 1.5p _cross_. Note that in contrast to conventional takeouts the passer, too, has a smash-in.

![1 2 3 1.5p 2.5p]({% include img param="1231.5p2.5p.png"%})
{:cimg}

We call this combination Mission Impossible, partly because it was surprisingly difficult to get your head around the overlay part (_A_), partly out of reverence for Lalo Shifrin's famous movie theme - one of the few widely known songs in a 5/4 time signature. Try chanting along with the rhythm!

<iframe width="100%" height="450" scrolling="no" frameborder="no" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/70927998&amp;auto_play=false&amp;hide_related=false&amp;show_comments=true&amp;show_user=true&amp;show_reposts=false&amp;visual=true"></iframe>

Once you have this pattern solid you can move on to the Impossible Roundabout, a matter for a second article. As a preview we can already outline the most important and difficult aspect, which is to be clear about what is cross and what is straight. There are some intricacies about starting, permutations and a peculiar role swapping irregularity - but we will cover these in a follow up post.

## Observations, Discussion

What we find most remarkable about this set of patterns is how hard it is to get one's head around the overlay role (passer _A_). Even though in both examples all the two-person passing parts are fairly easy, it takes quite some time to manage both patterns at once. Naturally, this applies especially to odd period patterns, where you have to learn the pattern once for the first half and another time when you switch hands.

However, and this is true for many takeouts and (mini) Prechac patterns - once you master the timing around the difficult throws like the 4s __and__ you don't have to think actively any more, you can get the pattern solid relatively quickly. And doing the pattern solidly then suddenly feels like being part of a clock work on the one hand and watching it with a detached kind of admiration at the same time on the other hand. This mix probably accounts for a significant amount of the attraction of juggling takeout patterns.

The second observation worth noting is that the passers are aware of the manipulation, much in contrast to conventional takeouts where the manipulation is supposed to be transparent to the passers, in that the passers do not notice it. 

In our view this is not problematic, since in reality the passers are always aware of the manipulation - an intercepted self is sometimes even called a 'pelf' to indicate that it is thrown gently (like a light **p**ass) towards the manipulator. In contrast, our approach explicitly spells out the interaction between manipulator and passer, rather than assuming that it is transparent to the latter.

## Future Work

We have various future plans to cover more of this family of patterns.  

First of all we need a more solid description of the run around version of Mission Impossible. To do that, a closer comparison of these patterns with Aidan's and Ed's framework should help. We might be able to describe the run around aspect elegantly with that notation. Taking this idea further, it would be nice to have a general theory to turn our set of patterns into runarounds, which could possibly be as easy as confirming that Ed's notation can be applied in general.

The more practical way ahead is obviously to generate more interesting patterns, especially with slightly more clubs to eliminate situations where we could actually stop the pattern with two clubs for each person. Examples of that could be a manipulated versions of "Why Not", "Not Why" or "Why the heck".
