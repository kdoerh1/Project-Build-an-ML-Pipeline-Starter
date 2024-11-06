## Student: Karrissa

## Git Repository Link
https://github.com/kdoerh1/Project-Build-an-ML-Pipeline-Starter
## W&B Project Link
https://wandb.ai/kdoerh1-western-governors-university/nyc_airbnb?nw=nwuserkdoerh1

# Build an ML Pipeline for Short-Term Rental Prices in NYC
You are working for a property management company renting rooms and properties for short periods of 
time on various rental platforms. You need to estimate the typical price for a given property based 
on the price of similar properties. Your company receives new data in bulk every week. The model needs 
to be retrained with the same cadence, necessitating an end-to-end pipeline that can be reused.

## Steps in the mlflow pipeline
Make sure you are in the Project-Build-an-ML-Pipeline-Starter directory
And you should be in the conda environment you created using the environment.yml
## Step 1: download file and load in W&B

  You can run this by doing: mlflow run . -P steps=download

## Step 2: cleans the file

  You can run this by doing: mlflow run . -P steps=basic_cleaning

## Step 3: checks the data

  You can run this by doing: mlflow run . -P steps=data_check

## Step 4: splits the data

  You can run this by doing: mlflow run . -P steps=data_split

## Step 5: trains to run random forest

  You can run this by doing: mlflow run . -P steps=train_random_forest

## Step 6: test regression model

  You can run this by doing: mlflow run . -P steps=active_steps

## Note
Steps 1-5 can all be run simultaneously by going mlflow run . 

Step 6 will need to be ran by itself and is not part of the mlflow run .


## License

[License](LICENSE.txt)
