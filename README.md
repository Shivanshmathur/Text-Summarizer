# Text-Summarizer (Complete and end to end)

# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/Shivanshmathur/Text-Summarizer
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n textsumm python=3.8 -y
```

```bash
conda activate textsumm
```


### STEP 02- install the requirements
```bash
conda install --yes --file requirements.txt
```


```bash
# Finally run the following command
python main.py
```

After you  run main.py, my script will automatically do the following steps - 
1. Data Download
2. Data Validation
3. Data Transformation
4. Train the model (this will take a lot of time, if you want to change the parameters, you can do that from the params.yaml file)
5. Evaluate the model

This will create a folder named 'artifacts' in the root directory, where you will have all the data from above steps.

To generate custom summaries or to see one from the test data, you will have to use the 'research\06_model_prediction.ipynb' file.