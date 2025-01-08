# 2025-MDPI-Pole-Data

Training data used for "The Cart-Pole Application as a Benchmark for Neuromorphic Computing", by Plank, Rizzo, White &amp; Schuman

# Information about the data

This repository contains data about all of the training runs used in this paper.
It has the following files:

- `timing.txt`: Timing of training runs.
- `training.txt`: Fitness of training runs.
- `epoch.txt`: # Epochs for training runs.
- `testing.txt`: Fitness of testing runs.
- `accumulate.txt`: Average accumulate operations for each testing run.
- `count.txt`: Average fire operations for each testing run.
- `neurons.txt`: # Neurons in the final training networks.
- `synapses.txt`: # Synapses in the final training networks.

The format of the files are as follows.  Let's take `testing.txt` as an example.  Here are the first 10 lines:

```
14985 e927b3b3_0042_pi5-1_665a91ac.ae656_NET.txt Easy, Pole-1-Easy, Argyle-3, Pop=100, Episodes=20, Easy
14985 d3622027_0000_drp-badmac_6681e4c2.05350_NET.txt Easy, Easy, Spike-FF-2, Pop=2000-Episodes=30-Epochs=003, Easy
14985 d3622027_0002_com1793_6681a7a0.16ad1_NET.txt Easy, Easy, Spike-FF-2, Pop=1000-Episodes=20-Epochs=010, Easy
14985 d3622027_0004_com2150_668074ef.31182_NET.txt Easy, Easy, Spike-FF-2, Pop=0500-Episodes=20-Epochs=020, Easy
14985 d3622027_0005_drp-mac_6681d8ba.1687e_NET.txt Easy, Easy, Spike-FF-2, Pop=0500-Episodes=30-Epochs=013, Easy
14985 d3622027_0005_pi5-2_6681c6e5.42774_NET.txt Easy, Easy, Spike-FF-2, Pop=0500-Episodes=30-Epochs=013, Easy
14985 6aa9bd8e_0008_com1793_667f30bd.6e9b4_NET.txt Easy, Easy, Spike-FF-2, Pop=2000-Epochs=010, Easy
14985 6aa9bd8e_0008_drp-asus_667f1012.d966e_NET.txt Easy, Easy, Spike-FF-2, Pop=2000-Epochs=010, Easy
14970.2 d991ab57_0000_pi4-2_66943f14.c1ddc_NET.txt Easy, Easy, RISP-True-Binary
14970.1 19e71f1c_0000_drp-mac_6694ebbd.f106a_NET.txt Easy, Easy, RISP-True-Binary
```

The first value is the metric (testing fitness).  The second value is the name of the network file.
After that is labeling information, which differs from run to run, but you can piece it together, or ask me
(Plank) if you have questions.

As you can see, there are between 112,013 and 124,870 lines in each file, each one representing a different training
run.  

If you want more information, please ask.

# Networks

I don't have the networks here, because they take up too much space.  The 10 networks highlighted in the
paper are available, complete with videos of them running, at 
[https://github.com/TENNLab-UTK/framework-open](https://github.com/TENNLab-UTK/framework-open).
