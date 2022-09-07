# SLM Lab: MountainCar Env

Play MountainCar using SLM Lab, using DDQN.

The pre-trained model is located in ./data/ddqn_mtcar_2022_09_07_093605

# Train

```
python3 run_lab.py slm_lab/spec/mtcar.json ddqn_mtcar train
```

# Test

```
python3 run_lab.py slm_lab/spec/mtcar.json ddqn_mtcar enjoy@data/ddqn_mtcar_2022_09_07_093605/ddqn_mtcar_t0_s0_spec.json
```

