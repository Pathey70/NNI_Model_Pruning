# NNI_Model_Pruning

### main.py

This file contains code for nni model pruning on mnist_hogwild dataset.

To run

``` python3 main.py --pruner <pruner_type>```

Arguments:

pruner_typer - L1NormPruner (default) or L2NormPruner

Structure:

-> main.py file contains model information and pruning method. Pruning steps are present in model_prune() method inside main.py.
