# Project Top Movies

Collect and track data on the top 300 movies of all-time according to Rotten Tomatoes

## Team

- Daniel Cho (Majoring in Econ + CS at Yale)
- Mert Tarim (Majoring in Electrical Engineering at Yale)

## How to replicate

1. Install Python and a conda distribution (either Anaconda or Miniconda)
2. Create a new conda environment for this project and activate it

```bash
conda create -n movies --python=3.12
conda activate movies
```

3. Install the required packages:

```bash
pip install -r requirements.txt
```

4. If running on VSCode, clone this repository and activate the correct environment every time you are running a notebook.


5. Go through each of the notebooks under the `notebooks/` folder, read and run then

## Generative AI Acknowledgement

This assignment was completed with the assistance of ChatGPT.

More specifically, I used it in the following way:

- I had syntatical errors when I was trying to read the SQL tables I created and tried to merge them into a single dataframe. ChatGPT corrected the syntax of my code for reading from the database.
