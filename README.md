## This is my first try at data visualization

### Getting Started;
1. Get the data csv from [kaggle.com ramen-ratings](https://www.kaggle.com/residentmario/ramen-ratings?select=ramen-ratings.csv)

2. Add it to the data folder 


### Install Dependencies:
1. Make a venv:
    windows: py -m venv venv
    mac/linux: python3 -m venv venv

2. Activate it:
    windows: .\venv\Scripts\Activate
    mac/linux: source venv/bin/activate

3. Install Req:
    pip install -r requirements.txt

4. Before running jupyter lab:
    *point the ipykernel to the venv*
    python -m ipykernel install --user --name=data_vis
