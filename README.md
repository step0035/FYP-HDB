# HDB Deep Learning Prediciton
## data
- raw: contains raw data collected from API and stored as csv
- timeseriesdata.csv: final data with imputations and all 9 features merged into single csv
## src
- combined analysis
  - combined.ipynb: LSTM
  - combined_others.ipynb: GRU, simple RNN
  - combined_mlp.ipynb: MLP
- fundamental analysis
  - fundamental.ipynb: LSTM, MLP
  - fundamental_others.ipynb: SVR, GBR, Random Forest
- technical analysis
  - technical.ipynb: LSTM
  - technical_others.ipynb: GRU, simple RNN
  - techinical_mlp.ipynb: MLP
## instructions
- Open ipynb files with google colab so you don't have to install libraries on your local machine
- Before running code cells, copy timeseriesdata.csv into content folder in google colab, or mount your drive
