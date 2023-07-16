# Baseline results 

With the intention to enable further comparative studies on logic
synthesis in EC, we evaluated the experimental search complexity of the evolutionary design of circuit instances included in our
benchmark suite. The baseline results presented in this section were
obtained with Cartesian Genetic Programming (CGP).

For our experiments, we used standard CGP with the (1 + 𝜆) evolutionary strategy that has been described in Algorithm 1 and the
standard probabilistic point mutation operator. To report fair results
with CGP, we performed hyperparameter optimization (HPO) of
the node count, population size and mutation rate with irace
with the proposed benchmarks. Since our HPO experiments showed
that a setting of 𝜆 = 1 is a general effective choice for our proposed
benchmarks we did not list the setting of the the 𝜆 parameter explicitly. Moreover, this finding is coherent with former results [19, 29].
With our HPO experiments we also identified a mutation rate of 0.3% as a general effective choice for our experiments. For the evaluation of each benchmark, we performed 100 runs and measured the
number of fitness evaluations until the CGP algorithm terminated.
We defined a limit of 10^8 fitness evaluations for our experiments.


![alt text](https://github.com/boolean-function-benchmarks/results/blob/main/baseline_results_cgp.png)

![alt text](https://github.com/boolean-function-benchmarks/results/blob/main/benchmark_identifiers.png)

