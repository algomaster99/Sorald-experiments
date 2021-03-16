# Sorald Experiments
This repository contains data related to the experiments that we conduct to assess [Sorald](https://github.com/SpoonLabs/sorald).

The structure of the repository is as follows:
- `top-rules.csv`: A list of SonarQube rules ordered by the number times they are violated in the dataset of [1].
- `considered_repos_stats.csv`: List of repositories that we consider for our experiments.
- `repair-results/`: A directory that contains data for executing Sorald on considered repositories (RQ1).
  - `sorald-results.json` file inside this directory presents a summary of results.
- `soraldbot-experiments/`: A directory containing data related to our experiments with SoraldBot (RQ2 and RQ3).
  - `commits-and-fixes.csv`: Includes data related to monitored commits and fix patches we generated for them.
  - `soraldbot-patches.txt`: The generated patches (RQ2).
  - `PRs.csv`: The submitted pull requests (RQ3).
- `sorald-on-spongebugs-data/`: The results of running Sorald on the dataset from [2].


````
[1]: Marcilio, D., Bonifácio, R., Monteiro, E., Canedo, E., Luz, W., & Pinto, G. (2019, May). Are static analysis violations really fixed? a closer look at realistic usage of sonarqube. In 2019 IEEE/ACM 27th International Conference on Program Comprehension (ICPC) (pp. 209-219). IEEE.
[2]: Marcilio, D., Furia, C. A., Bonifacio, R., & Pinto, G. (2020). SpongeBugs: Automatically generating fix suggestions in response to static code analysis warnings. Journal of Systems and Software, 168, 110671.
````