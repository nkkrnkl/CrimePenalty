# CrimePenalty

In this data analysis, I will be analyzing and applying statistical practices on a dataset about the death penalty in the USA.

A/B Testing
A/B testing is a form of hypothesis testing that allows you to make comparisons between two distributions.

If the null hypothesis of an A/B test is correct, then even if the order of the labels are shuffled it would not affect the differences in means between each group. By randomizing the data and creating multiple simulations we can compare it to the initial outcome to determin the "fairness" of a claim.

Murder Rates
Punishment for crime has many philosophical justifications. An important one is that fear of punishment may deter people from committing crimes.

In the United States, some jurisdictions execute people who are convicted of particularly serious crimes, such as murder. This punishment is called the death penalty or capital punishment. The death penalty is controversial, and deterrence has been one focal point of the debate. There are other reasons to support or oppose the death penalty, but in this project I've focused on deterrence.

The key question about deterrence is:

Through this exploration, does instituting a death penalty for murder actually reduce the number of murders?

Different sides have variously argued that the death penalty has no deterrent effect and that each execution prevents 8 murders, all using statistical arguments!

The data
The main data source for this data analysis comes from a paper by three researchers, Dezhbakhsh, Rubin, and Shepherd. The dataset contains rates of various violent crimes for every year 1960-2003 (44 years) in every US state. The researchers compiled the data from the FBI's Uniform Crime Reports.

Since crimes are committed by people, not states, we need to account for the number of people in each state when we're looking at state-level data. Murder rates are calculated as follows:

murder rate for state X in year Y=number of murders in state X in year Ypopulation in state X in year Y∗100000
(Murder is rare, so we multiply by 100,000 just to avoid dealing with tiny numbers.)

This analysis was done by Niki Karanikola in the Data Science Class | Spring 2023 | Instructor: Robert Blair | University of East Anglia¶
