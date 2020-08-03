***Project Aims*** 
1. To do exploratory data analysis and visualisation of the distribution of the outbreak,
as well as macro and micro factors might play a part in determining each country's performance
2. To build machine learning models which classify a patient's severity level
using various patient attributes 

***Using the Notebooks***
There are two notebooks which fulfil each project aim. The notebook titled 'Team Marcus_Data Visualisation'
addresses Aim 1, while 'Team Marcus_Machine Learning' addresses Aim 2.

The notebooks were done in Google Colab. 

The outputs are visible in both notebooks, but we recommend one not to run the notebooks unless absolutely necessary.
This is because importing the datasets is a hectic process on Google Colab, and would be prone to errors.
Running the notebook might cause the outputs to disappear if done incorrectly. 

***Importing the Datasets***
If one still needs to run the notebooks, before running,
he/she must create a shortcut of the `lifehack2020_files` folder that will link to his/her Google Drive. 
This can be done by right-clicking on the folder and left clicking on the option 'Add Shortcut to Drive'.

The link to the `lifehack2020_files` folder is:
https://drive.google.com/drive/folders/1hZJImX6uBZXf4mqf3egCwwIKoAmmx0Fy?usp=sharing

After creating the shortcut, one should be able to import the datasets smoothly. 

You would have to authenticate by clicking on the link shown in the output by following the instructions the link provides.

***Assumptions made***
1. There exists other factors that we did not include in the classification of illness severity (e.g.culture, weather).
Our data is only accurate as of the date of recording (25th July 2020).
As such, the total number of cases and deaths might differ. 
2. This model was made on the assumption that there is no vaccine out yet for COVID-19. 
3. The data collected in the datasets are assumed to be accurate. 