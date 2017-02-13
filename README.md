# HoNNeT
Deep learning predicts who would win in a HoN match given heroes of both team

## Role of each file
- `hon_db_retriever.ipynb` contains data preparation/wrangling process, this is
  probably the most time consuming part of the pipeline, it downloads HoN
  matches and save it into a **pickle** file
- `hon_matches.pkl` contains downloaded 100,000 matches
- `hon_db_analyzer.ipynb` contains deep learning part and data
  exploration/visualization
- `honnet_loader.ipynb` loads the trained model and save it for later use in
  multiple formats
- Other files are explained at
  the [web repository](https://github.com/off99555/HoNNeT-web) because they are
  the same.

