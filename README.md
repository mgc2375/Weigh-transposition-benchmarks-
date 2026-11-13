# Weight Transposition Benchmarks

Benchmarking skill distillation through direct weight transposition.

This project investigates whether the capabilities and skills of GLM-5.3 can be transferred into Qwen2.5-Coder (32B Instruct) through direct weight editing and transposition, without relying on conventional fine-tuning or additional training.

The objective is to evaluate how effectively model capabilities transfer through weight transposition, using established coding benchmarks.

![Coding Benchmark Performance Chart](Coding%20Benchmark%20Performance%20Chart.png)

Qwen2.5 Transposed scores 11.6 points lower than GLM-5.3 on AA Coding Index (-15.5%), 19.9 points lower on SWE-bench (-29.7%), 23.5 points lower on FrontierSWE (-30.1%), 21.5 points lower on SWE-Marathon (-50.6%), and 9.73 points lower on SciCode (-16.5%). It scores 7.6 points higher on Terminal-Bench v3.0 (+26.9%).

Compared with the original Qwen2.5-Coder 32B Instruct, the transposed model scores 38 points higher on SWE-bench (+422.2%) and 33.4 points higher on LiveCodeBench (+106.4%).

The aim is to determine whether direct weight transposition can effectively transfer specialised capabilities between language models, and assess which capabilities are retained, improved or degraded following transposition.
