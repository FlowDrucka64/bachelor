# General
- Write paper
- Run all the benchmarks on an actual k8 cluster

# Benchmarks
- Choose a (tf) model to benchmark
    - Convert model to a tflite model
    - different sized models
- factor in model compression vs runtime
- run x jobs at once, measure time, calc throughput
- run benchmarks multiple times, compute avg

# Faasm
- run with the chosen tflite model
- try to figure out protofaaslets


# Kserve
- Scale up the cpu usage
- run with the chosen tf model
- run my own benchmark as a job/task

# Knative
- setup knative cluster to serve tflite predictions
- benchmark it



# Paper

- Understanding the field
    - why FAAS
    - why prediction serving
    - why FAASM
    - why KSERVE
    

- Methology
    - Tools
    - BM setup


- Evaluation
    - Faasm vs native
    - Faasm vs Kserve
    - Faasm vs Knative
    - Snapshot vs no snapshot

