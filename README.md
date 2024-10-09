# Set Cover Problem &#129517;

Explore optimization techniques for solving the set cover problem, utilizing algorithms such as *hill climbing* and *tabu search*.

## Description
This project addresses the **set cover problem** using two different optimization techniques: *hill climbing* and *tabu search*. It evaluates the performance of these algorithms under varying conditions, including different sizes of the universe (`UNIVERSE_SIZE`), diverse numbers of sets (`NUM_SETS`), and varying densities of elements (`DENSITY`). Performance is assessed in terms of solution accuracy and the time taken to obtain results. 

It has been observed that tabu search generally outperforms hill climbing in solving the set cover problem. This superiority is attributed to its enhanced ability to explore the solution space and avoid local optima, resulting in more accurate solutions.

## Instances
Below is a list of all instances that can be utilized in the code. Each instance is defined by its universe size, number of sets, and density. Using a for loop, the following six instances will be tested in a single run of the algorithm.

```
ALL_INSTANCES = [
    {"UNIVERSE_SIZE": 100, "NUM_SETS": 10, "DENSITY": 0.2},
    {"UNIVERSE_SIZE": 1000, "NUM_SETS": 100, "DENSITY": 0.2},
    {"UNIVERSE_SIZE": 10_000, "NUM_SETS": 1_000, "DENSITY": 0.2},
    {"UNIVERSE_SIZE": 100_000, "NUM_SETS": 10_000, "DENSITY": 0.1},
    {"UNIVERSE_SIZE": 100_000, "NUM_SETS": 10_000, "DENSITY": 0.2},
    {"UNIVERSE_SIZE": 100_000, "NUM_SETS": 10_000, "DENSITY": 0.3}
]
```

## &#128200; Results
| # INSTANCE | FINAL FITNESS | TIME |
| :----------: | :------------- | :--------: |
| 1          | -279.18492230048645 | immediate |
| 2          | -6565.265134206568  | 0.9 s |
| 3          | -122897.22285322139 | 26.6 s |
| 4          | -279.18492230048645 | immediate |
| 5          | -279.18492230048645 | immediate |
| 6          | -279.18492230048645 | immediate |

## Contributions
If you want to contribute to this project, feel free to fork the repository and submit a pull request. 

To implement the Tabu Search algorithm and enhance its efficiency, reference was made to the slide of the Computational Intelligence Course and to the Wikipedia page on [Tabu Search](https://en.wikipedia.org/wiki/Tabu_search) and the accompanying pseudocode provided there.

## Contact
For questions, contact me at agnesere43@gmail.com.