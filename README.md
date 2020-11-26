# REM + TD3 (Doesn't work)

```diff
- Note this is a preliminary repository and *no effort* was spent getting REM to work well with TD3 (as it doesn't work).
- This repository should should not be used for benchmarking and only be used a starting point for MuJoCo experiments.
```

If you use this code, please cite the the [paper](https://arxiv.org/abs/1907.04543). To launch batch experiments with `RSEM`, use the file `run_main.sh`. To generate data, use `run_expert.sh`. `RSEM` works somewhat but not well though. 

Method is tested on [MuJoCo](http://www.mujoco.org/) continuous control tasks in [OpenAI gym](https://github.com/openai/gym). 
Networks are trained using [PyTorch 0.4](https://github.com/pytorch/pytorch) and Python 2.7.
