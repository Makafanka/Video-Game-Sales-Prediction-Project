Contributed by
Yiqun Zhang
Hanqing Liu
Yifan Sun
Cheng Qian
This is a project for video sales predict. There are three models 
- Neural network to predict platform （128*128*1）
- Random Forest to predict best sale area
	- without optimization (tree: 1000)
	- hyperparam optimization (automatically figured)
- Neural Network to predict best sale area（128*128*1）
	- RMSprop Optimizer
	- Adam Optimizer
To run the project, you need to upload the dataset named vgsales.csv
when running data import.