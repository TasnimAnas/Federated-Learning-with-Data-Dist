### Examples 

* **Examples I** Run FedD3 on IID MNIST with nc clients:
`python fedd3_main.py --config "./config/test_config.yaml"`


## Evaluation Procedures

To plot the testing accuracy and training loss over epochs or communication rounds, run:

`python postprocessing/eval_main.py -rr 'results'`

