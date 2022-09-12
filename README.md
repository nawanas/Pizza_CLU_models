# Pizza_CLU_models

This repo contains model for performing extractions for the [Pizza Bot model](https://github.com/Azure/pizza_luis_bot) using CLU. This includes creating two models to perform the different levels of parsing of a user utterance.
* MicrosoftPizza_Small: this is the leaf entities extracted from a user utterance
* MicrosoftPizza_LArge: this extracts the larger parse defining a full order, with everything else removed (including the classes that are present in the MicrosoftPizza_Small model.


