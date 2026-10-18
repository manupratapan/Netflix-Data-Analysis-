# Netflix Data Analysis

A step-by-step Jupyter notebook analyzing the supplied Netflix titles dataset. It covers data preparation, exploratory analysis, visualizations, questions and conclusions.

## Project files

- `netflix-data-analysis.ipynb` — analysis notebook
- `netflix_titles.csv` — dataset used by the notebook
- `charts/` — individual PNG images for each chart
- `requirements.txt` — Python packages needed to run the notebook

## Run the notebook

```bash
pip install -r requirements.txt
jupyter notebook netflix-data-analysis.ipynb
```

Run the cells from top to bottom and keep `netflix_titles.csv` in the project folder.

## Chart images

The charts are also saved as separate PNG files in the `charts` folder.

### Movies and TV Shows

![Number of Movies and TV Shows](charts/01-content-types.png)

### Titles added by year

![Netflix titles added by year](charts/02-titles-added-by-year.png)

### Content ratings

![Most common content ratings](charts/03-content-ratings.png)

### Ratings by content type

![Ratings by content type](charts/04-ratings-by-type.png)

### Titles by release year

![Netflix titles by release year](charts/05-titles-by-release-year.png)

### Movie durations

![Distribution of movie durations](charts/06-movie-durations.png)

### Top countries

![Top countries by title count](charts/07-top-countries.png)

### Top genres

![Most common genres](charts/08-top-genres.png)

## Dataset source

The dataset is the [Netflix Movies and TV Shows dataset on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows). The supplied CSV is a catalog snapshot and may not represent current Netflix availability. Follow the dataset page's applicable license and attribution terms when reusing the data.
