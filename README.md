# PSF-effects-on-caterpillar-and-aphid-species
Plant-soil feedback effects on multiple aphid and caterpillar species in cabbage

Plants need to defend themselves against a wide diversity of herbivorous insects. They recruit beneficial soil microorganisms to the roots that can enhance resistance to these herbivores. However, the generality of these plant-soil feedback (PSF) effects across a wide diversity of herbivore species is unknown. In this study, we assess the effects of herbivore-induced PSF on resistance to a panel of seven aboveground herbivore species across two feeding guilds and diet breadths. We selected three aphid and four caterpillar species that have Brassica oleracea as a host, of which four were generalists and three specialists. Soils were conditioned with B. oleracea plants infested with one of the seven herbivores. Microbiome feedback effects on insect resistance to conspecific herbivores were assessed in a new plant generation grown on a mixture of sterile and rhizosphere soil from herbivore-conditioned plants. No general patterns in PSF effects were observed across feeding guilds and diet breadth. Soil conditioning with plants exposed to Mamestra brassicae decreased feeding damage and caterpillar weight and increased shoot biomass. Other herbivore species were not affected by soil conditioning. These results show that PSF induction and effects were limited to only one out of the seven tested insect species.


# General procedure statistical analysis
1. Exploring data
2. Defining different (G)L(M)M models with transformed or non transformed data and different data distributions
3. Testing which model fits the data best using the DHARMa package (I made a custom function to show model fit nicely, this function is in the R script folder)
4. Extracting statistical information of the best fitting model
5. Post hoc test on best fitting model if applicable

# Choice of data ditributions
- Continues data larger than 0: Gaussian (normal) or gamma distribution (Caterpillar weight, plant biomass, leaf damage, leaf area)
- Integer numbbers larger than 0 (count data): Poisson distribution or negative binomial distribution (Aphid population size)
- Proportions (data between 0 and 1): binomial or beta binomial distribution (Caterpillar survival)
