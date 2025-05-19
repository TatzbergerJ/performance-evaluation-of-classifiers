# Loan-Classifier-Experiment
This is the code resository for a ML experiment in which different classifier models were trained to grade loans based on variables given in the training data ([dbrepo TUW Link](https://test.dbrepo.tuwien.ac.at/database/f234cb20-706f-4995-9ab9-89bcbf25d027/table/ea314771-32d9-45e4-94b8-96500edb6298/info)).

The experiment was originally part of the lecture "184.702 VU Machine Learning" in WS2023. This repository was created for the lecture "194.045 UE Data Stewardship" in SS2025 in order to practise FAIR data/code handling. To train the models, the following data is used: 


## Requirements
To run the code you need:
- python: 3.12.3
- pandas: 2.2.3
- numpy: 2.2.5
- sklearn: 1.6.1
- seaborn: 0.13.2
- matplotlib: 3.10.1
- dbrepo: 1.7.3

The dependencies are also stored in the requirements.txt file and can be installed using:
```
pip install -r requirements.txt
```

## Running the Code
1. Clone the repository
2. Open the notebook using jupyter
3. Run all Cells

## Output
Running the model will produce the following outputs:
- a classification of the test dataset ([dbrepo TUW Link](https://test.dbrepo.tuwien.ac.at/database/f234cb20-706f-4995-9ab9-89bcbf25d027/table/45ccb299-fafc-45c3-91da-e4f84c2a64d7/info)) using the best found model in the /results directory
- some additional plots in the /results directory
- the best found model for each of the model types in the /trained_models directory


## License 
This project is licensed under the MIT License. See the LICENSE file for more details.

## Author
- Jonas Tatzberger
- TU Wien
- Contact: e12002213@student.tuwien.ac.at
