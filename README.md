# General
- Choose a (tf) model to benchmark
    - Convert model to a tflite model
- Write paper
- Run all the benchmarks on an actual k8 cluster
- factor in model compression vs runtime
- different sized models

# Faasm
- run with the chosen tflite model
- try to figure out protofaaslets
- run x jobs at once, measure time, calc throughput
- run benchmarks multiple times, compute avg

# Kserve
- Scale up the cpu usage
- run with the chosen tf model
- run my own benchmark as a job/task
- run x jobs at once, measure time, calc throughput
- run benchmarks multiple times, compute avg

# Knative
- setup knative cluster to serve tflite predictions
- benchmark it



# Paper

## Understanding the field
### why FAAS
### why FAASM
### why prediction serving

## Methology
## Tools
## BM setup

## Evaluation
### Faasm vs Kserve
### Faasm vs Knative
### Snapshot vs no snapshot
### Faasm vs native
