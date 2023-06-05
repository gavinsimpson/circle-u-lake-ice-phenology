# Loss of lake ice cover in northern hemisphere lakes

## Gavin Simpson (Department of Animal and Veterinary Sciences, Aarhus University)

## Stefano Mezzini (Department of Biology, University of British Columbia)

### June 6, 2023

## Slides

* [HTML slide deck](https://gavinsimpson.github.io/circle-u-lake-ice-phenology/index.html)

## Abstract

Records of lake ice cover have been kept for many lakes worldwide for decades, or even centuries in some instances. These recordings reflect the profound social and cultural importance or lake ice for, inter alia, transportation, fishing, and cultural and spiritual activities in many communities and cultures. These records of lake ice cover also represent an excellent repository of information on climatic change as the formation and loss of lake ice is extremely sensitive to variations in climatic conditions, especially air temperature. Using these records, early lake ice phenology studies have demonstrated long-term changes in lake ice formation, with later ice-up, earlier ice-out, and consequently shorter duration of lake ice cover in many lakes. More recently, research has focussed on understanding the spatial and temporal patterns of these changes in lake ice phenology. Trends in lake ice freeze and thaw dates have traditionally been estimated using simple linear regression models. There are a number of issues with this methodology, however: i) freeze and thaw dates are one form of time-to-event data, which are not well-fitted by the Gaussian distribution assumed in linear regression, ii) observations of freeze dates especially may be censored (i.e. a lake may not freeze in a given year), iii) the linear trends estimated are not flexible enough to answer questions pertaining to how rates of change in freeze and thaw dates themselves have changed over time, and iv) the available data represent a sample of convenience, a feature that is rarely considered when calculating average "change" statistics for the sample.

Here, we will discuss how an event history model - the piece-wise exponential additive mixed model, or PAMM - can be used to address each of the issues. This is achieved through the use of appropriate conditional distributions for time-to-event data, which can also account for event censoring, while the use of penalised splines in the model structure addresses the remaining problems by fitting trends that can be non-linear and allowing for the control of effects from confounders. We illustrate our event history approach using a northern hemispheric data set of lake ice freeze and thaw dates from 563 lakes, and compare results from our models with previously published studies which used simpler, linear regression estimates. We show that, by using a modelling approach that is specifically tailored to the time-to-event nature of the observations, we are better able to estimate trends, rates of change, and uncertainties in those estimates.
