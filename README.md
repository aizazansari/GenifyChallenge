# GenifyChallenge

## How to Run
- Navigate to GenifyChallenge directory
- ```python app.py```
- Input the required values and click on recommend to generate recommendations

## Files and Folders
- app.py: Flask script used to run app and host model at API endpoint
- cust_dict.pkl: Dictionary used in processing input data
- scratch_work.ipnyb: Used to train model and perform rough work before moving final scripts to app.py 
- static: contains css styling
- templates: contains html files
- trained.model: trained this model using scratch_work.ipnyb for predictions on input data
- when_less_is_more.py: Kaggle notebook on which our training code is based upon. 

## Resources utilized
- Flask APIs: https://github.com/MaajidKhan/DeployMLModel-Flask
- Sample Inputs: https://www.genify.ai/en/recosysdemo
- Training code: https://www.kaggle.com/sudalairajkumar/when-less-is-more
