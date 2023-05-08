# comap-2023-data-analytics

Repository for submission for the 2023 COMAP math modeling competition Problem C.

Our solution was judged to be Meritorious (top 10%). Official results are here: https://www.contest.comap.com/undergraduate/contests/mcm/contests/2023/results/ (Team Number 2322040, question C)

We modeled the distribution of Wordle players over time, analyzed why words are more/less challenging for Wordle players, and used these models to make predictions about word distributions on future dates.

We developed this project in 4 days as a solution to the 2023 MCM competition: https://contest.comap.com/undergraduate/contests/mcm/contests/2023/problems/2023_MCM_Problem_C.pdf.

Our final paper is in the FinalSubmission.pdf file. This file contains our aggregate results.

We did our data cleaning and enriching in the `.ipynb` files. We cleaned the input dataset with `cleanData.ipynb`, added information about common bigrams with `addBigram.ipynb`, enriched with the frequency of the occurence of words in `frequencyList.ipynb` and `wordFreq.ipynb`, added vowel analysis with `vowels.ipynb`, and worked on some exploratory linear regressions with Pytorch in `numberOfParticipants.ipynb`.

We modeled the distribution of the number of participants over time with a Frechet Distribution (see `FrechetWithPlots.xlsx`).

We modeled the percent of hard mode players over time with a sigmoid function (see `sigmoidPercentHard.xlsx`).

The visual results of our models are in the `plots` folder.
