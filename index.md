![epfl](https://upload.wikimedia.org/wikipedia/commons/f/f4/Logo_EPFL.svg)
<img src="https://www.epfl.ch/labs/idephics/wp-content/uploads/2020/10/logo_idephics-1536x604.jpg" width="150"/>

<script type="text/x-mathjax-config">
    MathJax.Hub.Config({
      tex2jax: {
        skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'],
        inlineMath: [['$','$']]
      }
    });
  </script>
  <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script> 

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

Julia notebook: [Curie-Weiss model](https://idephics.github.io/EPFLDoctoralLecture2023/Resources/Week1/curie_weiss.jl.html)

**Main lecture**

<iframe id="kaltura_player" src="https://api.cast.switch.ch/p/113/sp/11300/embedIframeJs/uiconf_id/23448477/partner_id/113?iframeembed=true&playerId=kaltura_player&entry_id=0_pjt8ukl9&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=en&amp;flashvars[leadWithHTML5]=true&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=left&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[hotspots.plugin]=1&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=0_bc9cacbq" width="400" height="285" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="1. Curie Weiss Model"></iframe>

**Mean-Field model in Julia**

<iframe id="kaltura_player" src="https://api.cast.switch.ch/p/113/sp/11300/embedIframeJs/uiconf_id/23448477/partner_id/113?iframeembed=true&playerId=kaltura_player&entry_id=0_hgqr1d1w&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=en&amp;flashvars[leadWithHTML5]=true&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=right&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[hotspots.plugin]=1&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=0_fswn2lra" width="304" height="231" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="TD1a, Intro to Julia &amp; HW1 correction"></iframe>

**A seminar on large deviations**

<iframe id="kaltura_player" src="https://api.cast.switch.ch/p/113/sp/11300/embedIframeJs/uiconf_id/23448477/partner_id/113?iframeembed=true&playerId=kaltura_player&entry_id=0_2x685s5k&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=en&amp;flashvars[leadWithHTML5]=true&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=right&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[hotspots.plugin]=1&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=0_on2grid8" width="304" height="231" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="TD1b, Large deviations "></iframe>

### Week 2: Random Field Ising Model 

Lecture content: Random Field Ising Model in Chap 2, see also the [slides about the replica method](Resources/Week2/Replica.pdf)

Exercises: 2.1 (Gaussian Poincare inequality) & 2.3 (Mean-field algorithm). Due on March 9th at 10 AM

Julia notebook: [RFIM & mean field](https://idephics.github.io/EPFLDoctoralLecture2023/Resources/Week2/rfim_mean_field.jl.html)

**Main lecture**

<iframe id="kaltura_player" src="https://api.cast.switch.ch/p/113/sp/11300/embedIframeJs/uiconf_id/23448477/partner_id/113?iframeembed=true&playerId=kaltura_player&entry_id=0_apkmjdvt&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=en&amp;flashvars[leadWithHTML5]=true&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=left&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[hotspots.plugin]=1&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=0_dpjr3hj7" width="400" height="285" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="2b, RFIM - Cavity and Replica method "></iframe>

<iframe id="kaltura_player" src="https://api.cast.switch.ch/p/113/sp/11300/embedIframeJs/uiconf_id/23448477/partner_id/113?iframeembed=true&playerId=kaltura_player&entry_id=0_4dkqfawh&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=en&amp;flashvars[leadWithHTML5]=true&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=right&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[hotspots.plugin]=1&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=0_5c2rumwg" width="400" height="285" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="2a, RFIM - Variational method "></iframe>

**RFIM in Julia**

<iframe id="kaltura_player" src="https://api.cast.switch.ch/p/113/sp/11300/embedIframeJs/uiconf_id/23448477/partner_id/113?iframeembed=true&playerId=kaltura_player&entry_id=0_gwvj43js&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=en&amp;flashvars[leadWithHTML5]=true&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=left&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[hotspots.plugin]=1&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=0_7a2gxalg" width="304" height="231" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="TD2a, RFIM"></iframe>

**Stieltjes transform of Wigner matrices with replica** 

<iframe id="kaltura_player" src="https://api.cast.switch.ch/p/113/sp/11300/embedIframeJs/uiconf_id/23448477/partner_id/113?iframeembed=true&playerId=kaltura_player&entry_id=0_ehprtra6&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=en&amp;flashvars[leadWithHTML5]=true&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=left&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[hotspots.plugin]=1&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=0_2z9zkbub" width="304" height="231" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="TD2b, Stieltjes transform with the replica method"></iframe>

### Week 3: Random Field Ising Model with non-trivial network topology 

Lecture content: Random Field Ising Model on trees and sparse graphs. 

The lectures notes for this chapter are [here](https://github.com/IdePHICS/EPFLDoctoralLecture2023/blob/main/Resources/Chap4.pdf)

Exercises (also [here](https://github.com/IdePHICS/EPFLDoctoralLecture2023/blob/main/Resources/Chap4.pdf)): 4.2 (population dynamics), but 4.1 (Erdös-Renyi graphs) is also strongly recommended. Due on March 16th at 10 AM.

Julia notebook: [RFIM on random graphs & Potts model](https://idephics.github.io/EPFLDoctoralLecture2023/Resources/Week3/rfim_rg.jl.html)


**Main lecture**

<iframe id="kaltura_player" src="https://api.cast.switch.ch/p/113/sp/11300/embedIframeJs/uiconf_id/23448477/partner_id/113?iframeembed=true&playerId=kaltura_player&entry_id=0_s6ve7as9&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=en&amp;flashvars[leadWithHTML5]=true&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=left&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[hotspots.plugin]=1&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=0_nqkutwwk" width="400" height="285" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="3a, RFIM on a tree & BP"></iframe>

<iframe id="kaltura_player" src="https://api.cast.switch.ch/p/113/sp/11300/embedIframeJs/uiconf_id/23448477/partner_id/113?iframeembed=true&playerId=kaltura_player&entry_id=0_bkoeu9qs&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=en&amp;flashvars[leadWithHTML5]=true&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=left&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[hotspots.plugin]=1&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=0_pnl4uie4" width="400" height="285" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="3b, RFIM on sparse graphs & Population dynamics"></iframe>

**RFIM on random graphs**

<iframe id="kaltura_player" src="https://api.cast.switch.ch/p/113/sp/11300/embedIframeJs/uiconf_id/23448477/partner_id/113?iframeembed=true&playerId=kaltura_player&entry_id=0_2apcv9ic&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=en&amp;flashvars[leadWithHTML5]=true&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=left&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[hotspots.plugin]=1&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=0_nlpkkiii" width="400" height="285" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="TD3a, RFIM on random graphs"></iframe>

**Potts model & Erdös-Renyi degree**

<iframe id="kaltura_player" src="https://api.cast.switch.ch/p/113/sp/11300/embedIframeJs/uiconf_id/23448477/partner_id/113?iframeembed=true&playerId=kaltura_player&entry_id=0_j030j5rg&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=en&amp;flashvars[leadWithHTML5]=true&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=left&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[hotspots.plugin]=1&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=0_rrkkl907" width="400" height="285" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="TD3b, Potts model & Erdös-Renyi degree"></iframe>


### Week 4: Random Energy Model

Lecture content: We study the Random Energy Model.

The lectures notes for this chapter on on chap 13 in the notes.  

Exercises: 13.1 (REM as a p-spin model, a replica computation) OR 13.3 (Maximum of Gaussians and denoising). You may do both but it is ok if you just focus on one of them! Dead line is  March 23th at 10 AM.

> Errors in Ex 13.1:
> - The Hamiltonian for the $p$-spin model is $\mathcal{H}(\mathbf{S}) = -\sum_{i_1 < \cdots < i_p} J_{i_1, \ldots, i_p} S_{i_1} \cdots S_{i_p}$
> - The interaction terms are all sampled according to a Gaussian distribution with standard deviation $\sigma = \sqrt{\frac{p!}{2 N^{p-1}}}$, that is, $\mathbb{P}(J) = \sqrt{\frac{N^{p-1}}{\pi p!}} \exp\left(-\frac{N^{p-1}}{p!} J^2\right)$
> - In question 2, the actual result you should get is (up to a change of sign on $\widehat{Q}$):

$$G(\mathbf{Q}, \widehat{\mathbf{Q}}) = -\frac{\beta^2 n}{4} - \frac{\beta^2}{2} \sum_{a<b} \left(Q^{ab}\right)^p + \mathrm{i} \sum_{a<b} \widehat{Q}^{ab} Q^{ab} - \frac{1}{N} \log \sum_{\mathbf{S}^1, \ldots, \mathbf{S}^n} \exp\left[\mathrm{i} \sum_{a<b} \widehat{Q}^{ab} \left(\mathbf{S}^a \cdot \mathbf{S}^b \right) \right]$$

> - In question 3, this is for $p \to \infty$$
> - In question 4, just show that $\mathbb{E} [\mathcal{H}(\mathbf{S})]$ and $\mathbb{E} [\mathcal{H}(\mathbf{S}) \mathcal{H}(\mathbf{S}')]$ match with the REM for $p \to \infty$

Solutions: [p-spin model](Resources/Week4/pspin.pdf) (PDF), [maximum of Gaussians](Resources/Week4/denoising.jl.html) (Julia notebook)

**Main lecture**

<iframe id="kaltura_player" src="https://api.cast.switch.ch/p/113/sp/11300/embedIframeJs/uiconf_id/23448477/partner_id/113?iframeembed=true&playerId=kaltura_player&entry_id=0_9w05zj7v&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=en&amp;flashvars[leadWithHTML5]=true&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=left&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[hotspots.plugin]=1&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=0_whvu98le" width="400" height="285" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="Random Energy Model, Full solution & Condensation"></iframe>


<iframe id="kaltura_player" src="https://api.cast.switch.ch/p/113/sp/11300/embedIframeJs/uiconf_id/23448477/partner_id/113?iframeembed=true&playerId=kaltura_player&entry_id=0_fmc04znf&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=en&amp;flashvars[leadWithHTML5]=true&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=left&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[hotspots.plugin]=1&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=0_ot78jpfl" width="400" height="285" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="4b, REM - Replica Symmetry Breaking"></iframe>


### Week 5: Graphical models & Open problems 

Fill up your preference for the open problems here https://docs.google.com/spreadsheets/d/1guW79xOLy_fOBGnfnI6lmXtH2IMZAlom-1hMBxD-rAw/edit?usp=sharing .
Lecture content: graphical models & introduction to open problems 

**Main Lecture** 
<iframe id="kaltura_player" src="https://api.cast.switch.ch/p/113/sp/11300/embedIframeJs/uiconf_id/23448477/partner_id/113?iframeembed=true&playerId=kaltura_player&entry_id=0_h8yf36uc&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=en&amp;flashvars[leadWithHTML5]=true&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=left&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[hotspots.plugin]=1&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=0_tlc4nw8d" width="400" height="285" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="5a, Graphical models"></iframe>

<iframe id="kaltura_player" src="https://api.cast.switch.ch/p/113/sp/11300/embedIframeJs/uiconf_id/23448477/partner_id/113?iframeembed=true&playerId=kaltura_player&entry_id=0_3fuxcjfi&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=en&amp;flashvars[leadWithHTML5]=true&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=left&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[hotspots.plugin]=1&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=0_5s5lhtrd" width="400" height="285" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="5b, Open problems"></iframe>
