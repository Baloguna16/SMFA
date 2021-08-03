# Modelling Input-Output Relationships to Optimize Production for Novel Vaccines

Over the course of the summer, I have been gathering data for my master's thesis project. I am studying the relationship beetween inputs to the production process for an *PfSPZ vaccine* and their corresponding outputs. By connecting these inputs and outputs, we can derive a model to predict the sporozoite yield from the inputs seeded in the mosquitoes.

## Background

Malaria is caused by the Plasmodium parasite--an organism which hosts in two different orders of multicellular organism: mosquitoes and mammals/birds. In humans, the species Plasmodium *falciparum* is endemic, typically among vulnerable populations in developing countries. Pf, as we shall abbreviate it, leads to 2 million cases of malaria and over 400,000 deaths each year around the world.

To combat this disease, the medical community has developed a vaccine, PfSPZ. PfSPZ was developed by Sanaria, and it is built on sporozoites as the active pharmaceutical ingredient or the API. Sporozoites are the infectious stage of Pf, and they are injected into humans with mosquito saliva when an infected mosquito bites a human to draw blood meal. While the vaccine proved promising after an number of trials, it comes with a set of challenges.

Given the complexity of Pf (which I will discuss in a dedicated analysis of the Pf life cycle), the sporozoites must be 'farmed' for now, in a long manual process. Assuming the technicians cultivating Pf are competent and trained, it takes a great degree of specialized skill and time to produce a single dose of vaccine. **PAPER** estimated that a team of ___ technicians working together could produce ___ doses of vaccine in one hour. To meet global demand, we would need ___ technicians to produce ___ doses annually, assuming each individual needs ___ doses. This also assumes a perfect prediction of who would contract malaria if not vaccined with PfSPZ.

This senario also does not account for the variation between technicians farming Pf. We can suspect that this variation affects the yield of sporozoites and the potency of those sporozoites. I hope to account for this variation in my model and separate it from the biological complexity of Pf, its host mosquito, and the growth media.

## About This Repository

This repository will contain a series of notebooks which will document usage of the model. It will also introduce opportunities for the improvement of the model and explanations of the steps taken. Hopefully this will result in a deeply useful and open-source tool.
