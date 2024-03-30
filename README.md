# YouTube Comment spam detection and moderating system
Disclaimer:- The model is created using dataset  of 2017 of famous english singers https://archive.ics.uci.edu/dataset/380/youtube+spam+collection. To make to application work more efficiently latest dataset is recommended to used in training of model.

Requirements to use the tool:
- Account in Google Console for YouTube API.
- YouTube API key saved in api_key.txt file.
- Python3
- Create 'secrets.toml' and add the secrets int into it ([secrets]
api_key = "")
- Create api_key.txt and add the api key into it
- To install all dependencies: - pip install -U scikit-learn requests joblib pickle5


The result of the application is like this :

![Home Page](/Dataset%20and%20model/1g.png)

![Options to select from](/Dataset%20and%20model/2g.png) 

![Link to provide](/Dataset%20and%20model/3g.png) 

![Filtered Spam Comment](/Dataset%20and%20model/4g.png) 

![Report or Deletion based on user identity](/Dataset%20and%20model/5g.png)