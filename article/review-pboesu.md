This is a very nice and compact replication of the original article by Wilson and Yoshimura. The paper is clear, concise, and well written. The accompanying code is clear and well annotated. The results from the original work are fully replicated.

I only have some relatively minor suggestions, none of which are critical to the substance of the reproduction:

1. Random seeds: I'd love to get input on this from the author and editor(s), but I was wondering whether in the pursuit of full reproducibility it would be preferable to always use explicit RNG seeds for stochastic simulations?
As is, the code will reproduce almost, but not quite identical figures every time the manuscript is reproduced from scratch.

2. Figure captions: The author clearly explains plotting symbols in the text, but the figure captions themselves are rather too terse. I'm a big fan of "stand-alone" figure captions, and would prefer if the plotting symbols were explained in the figure captions.

3. Figure 3 axis labels: I personally find the format of the axis tick labels (fractional powers of 10) in Figure 3 unintuitive, and would prefer the use of integers and/or as in Fig. 4 of the original study.

4. Figure 4 z axis label: The z axis in Figure 4 is missing a label.

5. Figure and Table cross references: Possibly an issue with templates in the markdown to PDF toolchain for ReScience, but figure and table cross references lack a label. E.g. https://github.com/PoisotLab/ReScience-submission/blame/poisot-2017/article/Poisot-2017.md#L151 prints as 'All default parameter values are given in 1.' rather than 'All default parameter values are given in Table 1.'

6. I believe the reference for Pielou's evenness index J' is incorrect. The cited paper discusses the uses and misuses of the Shannon-Weaver diversity index, and makes no mention of evenness. The earliest derivation of J' I could find (in an non-exhaustive search) is in Pielou 1966 J Theor Biol 10:370-383 https://doi.org/10.1016/0022-5193(66)90133-0 .
