# Plackett-Luce
<p>
    <a href="https://cran.r-project.org/package=Seurat">
        <img src="https://www.r-pkg.org/badges/version/Seurat"
            alt="python"></a> &nbsp;
    <a href="https://opensource.org/licenses/MIT">
        <img src="https://img.shields.io/badge/license-MIT-brightgreen.svg"
            alt="MIT license"></a> &nbsp;
</p>

Link to the project [report](__report__/report.pdf) and [presentation](__presentation__/presentation.pdf). 

In this project, we rank the relative skills of `24` poker players over `134` poker games. For each game, there is a ranking for each participant. 
- Plackett-Luce model for multiple players as a generalization of the Bradley-Terry model for two players
- Elicit prior, perform posterior inference with MCMC, and estimate the Bayes factor with the Bridge estimator
- In particular, we want to understand whether the performance of the players depends on two covariates: `seniority (age)` and `skill`
