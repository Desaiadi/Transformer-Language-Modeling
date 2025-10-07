(hw2_env) (base) aditya@10-17-119-198 p2-distrib % python letter_counting.py
Namespace(task='BEFORE', train='data/lettercounting-train.txt', dev='data/lettercounting-dev.txt', output_bundle_path='classifier-output.json')
['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z', ' ']
10000 lines read in
1000 lines read in
Epoch 1: loss=2116.016 | train@200=98.65% | dev=98.67%
Epoch 2: loss=550.351 | train@200=97.95% | dev=98.09%
Epoch 3: loss=413.129 | train@200=98.60% | dev=98.75%
Epoch 4: loss=348.072 | train@200=99.15% | dev=99.33%
Epoch 5: loss=324.515 | train@200=99.48% | dev=99.56%
Epoch 6: loss=265.043 | train@200=99.35% | dev=99.70%
Epoch 7: loss=231.512 | train@200=98.88% | dev=98.84%
Epoch 8: loss=225.241 | train@200=99.60% | dev=99.69%
INPUT 0: heir average albedo 
GOLD 0: array([0, 0, 0, 0, 0, 0, 0, 1, 1, 1, 0, 2, 1, 2, 0, 0, 2, 0, 0, 2])
PRED 0: array([0, 0, 0, 0, 0, 0, 0, 1, 1, 1, 0, 2, 1, 2, 0, 0, 2, 0, 0, 2])
Passed normalization test on attention maps
INPUT 1: ed by rank and file 
GOLD 1: array([0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 2, 1, 1, 1, 2, 0, 0, 0, 1, 2])
PRED 1: array([0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 2, 1, 1, 1, 2, 0, 0, 0, 1, 2])
Passed normalization test on attention maps
INPUT 2: s can also extend in
GOLD 2: array([0, 0, 0, 0, 0, 1, 1, 0, 1, 0, 2, 0, 0, 0, 1, 1, 0, 2, 0, 2])
PRED 2: array([0, 0, 0, 0, 0, 1, 1, 0, 1, 0, 2, 0, 0, 0, 1, 1, 0, 2, 0, 2])
Passed normalization test on attention maps
INPUT 3: erages between nine 
GOLD 3: array([0, 0, 0, 0, 1, 0, 0, 0, 2, 0, 0, 2, 2, 0, 1, 1, 0, 2, 2, 2])
PRED 3: array([0, 0, 0, 0, 1, 0, 0, 0, 2, 0, 0, 2, 2, 0, 1, 1, 0, 2, 2, 2])
Passed normalization test on attention maps
INPUT 4:  that civilization n
GOLD 4: array([0, 0, 0, 0, 1, 1, 0, 0, 0, 1, 0, 2, 0, 1, 2, 2, 0, 0, 2, 1])
PRED 4: array([0, 0, 0, 0, 1, 1, 0, 0, 0, 1, 0, 2, 0, 1, 2, 2, 0, 0, 2, 1])
Passed normalization test on attention maps
Accuracy: 100 / 100 = 1.000000
Training accuracy (100 exs):
Accuracy: 1990 / 2000 = 0.995000
Dev accuracy (whole set):
Decoding on a large number of examples (1000); not printing or plotting
Accuracy: 19939 / 20000 = 0.996950
(hw2_env) (base) aditya@10-17-119-198 p2-distrib % python letter_counting.py --task BEFOREAFTER
Namespace(task='BEFOREAFTER', train='data/lettercounting-train.txt', dev='data/lettercounting-dev.txt', output_bundle_path='classifier-output.json')
['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z', ' ']
10000 lines read in
1000 lines read in
Epoch 1: loss=2984.990 | train@200=85.75% | dev=85.85%
Epoch 2: loss=876.263 | train@200=99.12% | dev=98.81%
Epoch 3: loss=669.466 | train@200=99.00% | dev=98.58%
Epoch 4: loss=524.553 | train@200=98.90% | dev=99.27%
Epoch 5: loss=430.282 | train@200=99.60% | dev=99.73%
Epoch 6: loss=421.910 | train@200=99.58% | dev=99.83%
Epoch 7: loss=385.370 | train@200=99.75% | dev=99.79%
Epoch 8: loss=350.402 | train@200=99.98% | dev=99.77%
INPUT 0: heir average albedo 
GOLD 0: array([0, 2, 0, 1, 2, 2, 0, 2, 1, 2, 0, 2, 2, 2, 0, 0, 2, 0, 0, 2])
PRED 0: array([0, 2, 0, 1, 2, 2, 0, 2, 1, 2, 0, 2, 2, 2, 0, 0, 2, 0, 0, 2])
Passed normalization test on attention maps
INPUT 1: ed by rank and file 
GOLD 1: array([1, 1, 2, 0, 0, 2, 0, 1, 1, 0, 2, 1, 1, 1, 2, 0, 0, 0, 1, 2])
PRED 1: array([1, 1, 2, 0, 0, 2, 0, 1, 1, 0, 2, 1, 1, 1, 2, 0, 0, 0, 1, 2])
Passed normalization test on attention maps
INPUT 2: s can also extend in
GOLD 2: array([1, 2, 0, 1, 2, 2, 1, 0, 1, 0, 2, 1, 0, 0, 1, 2, 0, 2, 0, 2])
PRED 2: array([1, 2, 0, 1, 2, 2, 1, 0, 1, 0, 2, 1, 0, 0, 1, 2, 0, 2, 0, 2])
Passed normalization test on attention maps
INPUT 3: erages between nine 
GOLD 3: array([2, 0, 0, 0, 2, 0, 2, 0, 2, 0, 0, 2, 2, 2, 2, 2, 0, 2, 2, 2])
PRED 3: array([2, 0, 0, 0, 2, 0, 2, 0, 2, 0, 0, 2, 2, 2, 2, 2, 0, 2, 2, 2])
Passed normalization test on attention maps
INPUT 4:  that civilization n
GOLD 4: array([2, 2, 0, 1, 2, 2, 0, 2, 0, 2, 0, 2, 0, 1, 2, 2, 0, 1, 2, 1])
PRED 4: array([2, 2, 0, 1, 2, 2, 0, 2, 0, 2, 0, 2, 0, 1, 2, 2, 0, 1, 2, 1])
Passed normalization test on attention maps
Accuracy: 100 / 100 = 1.000000
Training accuracy (100 exs):
Accuracy: 2000 / 2000 = 1.000000
Dev accuracy (whole set):
Decoding on a large number of examples (1000); not printing or plotting
Accuracy: 19954 / 20000 = 0.997700
(hw2_env) (base) aditya@10-17-119-198 p2-distrib % 
