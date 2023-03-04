# General
- [ ] Write paper
- [ ] Run all the benchmarks on an actual k8 cluster

# Benchmarks
- [ ] Choose a (tf) model to benchmark
    - [ ] Convert model to a tflite model
    - [x] different sized models
- [ ] factor in model compression vs runtime
- [ ] run x jobs at once, measure time, calc throughput
- [x] run benchmarks multiple times, compute avg

# Faasm
- [ ] run with the chosen tflite model
- [x] "micro" benchmarks (timings of different parts)
- [x] try to figure out protofaaslets


# Kserve
- [ ] Scale up the cpu usage
- [x] run with the chosen tf model
- [ ] run my own benchmark as a job/task

# Knative
- [ ] setup knative cluster to serve tflite predictions
    - [ ] fix autoscaling
- [x] benchmark it



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

