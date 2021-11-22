# KWS-HW
Key Word Spotting HW for DLA HSE course

This homework implements KWS model and 
- Implements its Streaming variant (close to real life case)
- Explores ways to compress model both in memory and MACs. Distillation, Quantization and type changing are used.

All experiments can be found in `KWS-HW.ipynb`. In order to test models, you can just run notebook a it is. 
By default it downloads models, using `test.sh` script, runs experiments and builds plots with metrics.

If you want to train models from the start, instead of downloading and running experiments on trained ones (or something goes wrong and models won't download), 
you should change `to_train` variable to **True** in the first cell on notebook.
