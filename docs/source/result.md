# Results
There are some reproduced model results using NeuralKG
## FB15K237

|Method | MRR | Hit@1 | Hit@3 | Hit@10 |
|:------:|:---:|:-----:|:-----:|:------:|
|TransE|0.32|0.23|0.36|0.51|
|TransR|0.23|0.16|0.26|0.38|
|TransH|0.31|0.2|0.34|0.50|
|DistMult|0.30|0.22|0.33|0.48|
|ComplEx|0.25|0.17|0.27|0.40|
|SimplE|0.16|0.09|0.17|0.29|
|ConvE|0.32|0.23|0.35|0.50|
|RotatE|0.33|0.23|0.37|0.53|
|BoxE|0.32|0.22|0.36|0.52|
|XTransE|0.29|0.19|0.31|0.45|
|RGCN|0.25|0.16|0.27|0.43|
|KBAT*|0.19|0.11|0.22|0.38|
|CompGCN|0.34|0.25|0.38|0.52|
|IterE|0.18|0.13|0.19|0.26|

## WN18RR

|Method | MRR | Hit@1 | Hit@3 | Hit@10 |
|:------:|:---:|:-----:|:-----:|:------:|
|TransE|0.22|0.01|0.40|0.52|
|TransR|0.16|0|0.31|0.35|
|TransH|0.17|0|0.33|0.43|
|DistMult|0.43|0.40|0.44|0.48|
|ComplEx|0.44|0.41|0.46|0.51|
|SimplE|0.41|0.38|0.42|0.45|
|ConvE|0.42|0.38|0.43|0.50|
|RotatE|0.45|0.42|0.46|0.49|
|BoxE|0.41|0.35|0.44|0.50|
|XTransE|0.19|0|0.33|0.44|
|RGCN|0.30|0.26|0.33|0.36|
|KBAT*|0.41|0.34|0.45|0.56|
|CompGCN|0.46|0.42|0.47|0.52|
|IterE|0.29|0.24|0.30|0.36|

## FB15K

|Method | MRR | Hit@1 | Hit@3 | Hit@10 |
|:------:|:---:|:-----:|:-----:|:------:|
|RugE|0.76|0.70|0.81|0.85|


*:There is a label leakage error in KBAT, so the corrected result is poor compared with the paper result. Details in https://github.com/deepakn97/relationPrediction/issues/28