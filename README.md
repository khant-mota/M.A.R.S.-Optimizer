# M.A.R.S.-Optimizer
Team : 

Mota Khant

Anand Sadhika

Ravani Yesha

Sandhu Avneet Kaur

We 4, as a project in the course Computational Methods and Optimization
came up with an Optimizer which is compared with pre-existing 
optimizers like Adam, RMS Prop and SGD + Momentum.

We tested our Optimizer against the 3 other Optimizers on : 
1. Well Conditioned Quadratic Function
2. Ill Conditioned Quadratic Function
3. Rosenbrock Function

Run the following commands to get the results as us : 
1. git clone https://github.com/khant-mota/M.A.R.S.-Optimizer.git
2. cd M.A.R.S.-Optimizer
3. pip install jupyter
4. jupter nbconvert --to python "MARS_vs_Adam_vs_SGD+Mom_vs_RMS_Prop.ipynb"
5. jupter nbconvert --to python "MARS_train_and_test_on_MNIST_dataset.ipynb"
6. python MARS_vs_Adam_vs_SGD+Mom_vs_RMS_Prop.py
7. python MARS_train_and_test_on_MNIST_dataset.py
