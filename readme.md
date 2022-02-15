# Horseshoe Priors for Bayesian Neural Networks.  
---------------------------------
This software includes an implementation of the model presented in:  
"Model Selection in Bayesian Neural Networks via Horseshoe priors", Soumya Ghosh and Finale Doshi-Velez. NIPS 2017. Bayesian Deep Learning Workshop  (http://bayesiandeeplearning.org/2017/papers/42.pdf).

The software depends on autograd (https://github.com/HIPS/autograd)

### USAGE:

*  To train, in scripts folder

```
python train_hsbnn.py
```

* Under src folder, use

```
python plot_weights.py ./results/Classification/02_14_2022/hsbnn_20_1.pkl
```
to visualize the inferred weights.
