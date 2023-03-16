![epfl](https://upload.wikimedia.org/wikipedia/commons/f/f4/Logo_EPFL.svg)
<img src="https://www.epfl.ch/labs/idephics/wp-content/uploads/2020/10/logo_idephics-1536x604.jpg" width="150"/>

## Staff

Main lecturer: Pr. Florent Krzakala, head of [IdePHICS lab](https://www.epfl.ch/labs/idephics/) (with help from the amazing Pr. Lenka Zdeborová, head of [SPOC lab](https://www.epfl.ch/labs/spoc/)).

Teaching assistants: [Yatin Dandi](https://yatindandi.github.io/), [Guillaume Dalle](https://gdalle.github.io/), [Luca Pesce](https://people.epfl.ch/luca.pesce?lang=en).

## Overview

Interest in the methods and concepts of statistical physics is rapidly growing in fields as diverse as theoretical computer science, probability, machine learning, discrete mathematics, optimization and compressed sensing. The present course will cover this rich and active interdisciplinary research landscape.

More specifically, we will review the statistical physics approach to problems ranging from graph theory (percolation, community detection) through discrete optimization and constraint satisfaction (satisfiability, coloring) to machine learning (learning with two-layer neural networks, mean-field dynamics, gradient descent and SGD, low-rank matrix and tensor factorization, etc.).

We will expose theoretical methods of analysis (replica, cavity, ...) algorithms (message passing, spectral methods, ...), neural networks (theory of SGD, ...), discuss concrete applications, highlight rigorous justifications as well as present the connection to the physics of glassy and disordered systems.

The aim is to make this growing field accessible to students from computer science, math, and engineering, not only physics (but of course, physicists are more than welcome). The course is set up so that we shall give open problems during and at the end of the semester.

## References

- [Information, Physics and Computation](https://web.stanford.edu/~montanar/RESEARCH/book.html), Oxford Graduate Texts, 2009, M. Mézard & A. Montanari

- [Statistical Physics of inference: Thresholds and algorithms](https://arxiv.org/abs/1511.02476), Advances in Physics Volume 65 Issue 5, 2016, L. Zdeborová & F. Krzakala

## Logistics

Lectures will take place on Fridays (10:00-12:00 in CM 011) and exercise sessions will take place on Thursdays (10:00-12:00 in CM 011).

Recorded lectures will be made avalible on [mediaspace](https://mediaspace.epfl.ch/channel/PHYS-642%2BStatistical%2Bphysics%2Bfor%2Boptimization%2B%2526%2Blearning%2B23/31507).

## Detailed lecture notes

[Chapters 1-13](Resources/PHYS642.pdf) (still in construction)

## Classes

### Week 1: The Curie-Weiss model

Lecture content: Curie-Weiss model in Chap 1

Exercises: 1.1 (Bounds on the binomial) and 1.5 (Glauber dynamics). Due on March 2nd at 10 AM

Julia notebook: [Curie-Weiss model](https://idephics.github.io/EPFLDoctoralLecture2023/Resources/Week1/curie_weiss.html)

**Main lecture**

<iframe id="kaltura_player" src="https://api.cast.switch.ch/p/113/sp/11300/embedIframeJs/uiconf_id/23448477/partner_id/113?iframeembed=true&playerId=kaltura_player&entry_id=0_pjt8ukl9&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=en&amp;flashvars[leadWithHTML5]=true&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=left&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[hotspots.plugin]=1&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=0_bc9cacbq" width="400" height="285" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="1. Curie Weiss Model"></iframe>

**Mean-Field model in Julia**

<iframe id="kaltura_player" src="https://api.cast.switch.ch/p/113/sp/11300/embedIframeJs/uiconf_id/23448477/partner_id/113?iframeembed=true&playerId=kaltura_player&entry_id=0_hgqr1d1w&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=en&amp;flashvars[leadWithHTML5]=true&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=right&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[hotspots.plugin]=1&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=0_fswn2lra" width="304" height="231" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="TD1a, Intro to Julia &amp; HW1 correction"></iframe>

**A seminar on large deviations**

<iframe id="kaltura_player" src="https://api.cast.switch.ch/p/113/sp/11300/embedIframeJs/uiconf_id/23448477/partner_id/113?iframeembed=true&playerId=kaltura_player&entry_id=0_2x685s5k&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=en&amp;flashvars[leadWithHTML5]=true&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=right&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[hotspots.plugin]=1&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=0_on2grid8" width="304" height="231" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="TD1b, Large deviations "></iframe>

### Week 2: Random Field Ising Model 

Lecture content: Random Field Ising Model in Chap 2, see also the [slides about the replica method](Resources/Week2/Replica.pdf)

Exercises: 2.1 (Gaussian Poincare inequality) & 2.3 (Mean-field algorithm). Due on March 9th at 10 AM

Julia notebook: [RFIM & mean field](https://idephics.github.io/EPFLDoctoralLecture2023/Resources/Week2/rfim.html)

**Main lecture**

<iframe id="kaltura_player" src="https://api.cast.switch.ch/p/113/sp/11300/embedIframeJs/uiconf_id/23448477/partner_id/113?iframeembed=true&playerId=kaltura_player&entry_id=0_apkmjdvt&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=en&amp;flashvars[leadWithHTML5]=true&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=left&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[hotspots.plugin]=1&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=0_dpjr3hj7" width="400" height="285" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="2b, RFIM - Cavity and Replica method "></iframe>

<iframe id="kaltura_player" src="https://api.cast.switch.ch/p/113/sp/11300/embedIframeJs/uiconf_id/23448477/partner_id/113?iframeembed=true&playerId=kaltura_player&entry_id=0_4dkqfawh&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=en&amp;flashvars[leadWithHTML5]=true&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=right&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[hotspots.plugin]=1&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=0_5c2rumwg" width="400" height="285" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="2a, RFIM - Variational method "></iframe>

** RFIM model in Julia**

<iframe id="kaltura_player" src="https://api.cast.switch.ch/p/113/sp/11300/embedIframeJs/uiconf_id/23448477/partner_id/113?iframeembed=true&playerId=kaltura_player&entry_id=0_gwvj43js&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=en&amp;flashvars[leadWithHTML5]=true&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=left&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[hotspots.plugin]=1&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=0_7a2gxalg" width="304" height="231" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="TD2a, RFIM"></iframe>

**Stieltjes transform of Wigner matrices with replica** 

<iframe id="kaltura_player" src="https://api.cast.switch.ch/p/113/sp/11300/embedIframeJs/uiconf_id/23448477/partner_id/113?iframeembed=true&playerId=kaltura_player&entry_id=0_ehprtra6&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=en&amp;flashvars[leadWithHTML5]=true&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=left&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[hotspots.plugin]=1&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=0_2z9zkbub" width="304" height="231" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="TD2b, Stieltjes transform with the replica method"></iframe>

### Week 3: Random Field Ising Model with non-trivial network topology 

Lecture content: Random Field Ising Model on trees and sparse graphs. 

The lectures notes for this chapter are [here](https://github.com/IdePHICS/EPFLDoctoralLecture2023/blob/main/Resources/Chap4.pdf)

Exercises (also [here](https://github.com/IdePHICS/EPFLDoctoralLecture2023/blob/main/Resources/Chap4.pdf)): 4.2 (population dynamics), but 4.1 (Erdös-Renyi graphs) is also strongly recommended. Due on March 16th at 10 AM.

Julia notebook: [RFIM on random graphs & Potts model](https://idephics.github.io/EPFLDoctoralLecture2023/Resources/Week3/rfim_rg.html)


**Main lecture**

<iframe id="kaltura_player" src="https://api.cast.switch.ch/p/113/sp/11300/embedIframeJs/uiconf_id/23448477/partner_id/113?iframeembed=true&playerId=kaltura_player&entry_id=0_s6ve7as9&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=en&amp;flashvars[leadWithHTML5]=true&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=left&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[hotspots.plugin]=1&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=0_nqkutwwk" width="400" height="285" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="3a, RFIM on a tree & BP"></iframe>

<iframe id="kaltura_player" src="https://api.cast.switch.ch/p/113/sp/11300/embedIframeJs/uiconf_id/23448477/partner_id/113?iframeembed=true&playerId=kaltura_player&entry_id=0_bkoeu9qs&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=en&amp;flashvars[leadWithHTML5]=true&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=left&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[hotspots.plugin]=1&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=0_pnl4uie4" width="400" height="285" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="3b, RFIM on sparse graphs & Population dynamics"></iframe>
