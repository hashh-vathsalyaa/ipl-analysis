# IPL Match Analysis

A beginner data analysis project using Python and Pandas on IPL match data (`matches.csv`, from Kaggle). I wanted to answer a few simple questions about the tournament using code.

## Questions I asked

1. Which team has won the most matches?
2. Does winning the toss help?
3. Does the toss decision (bat or field) change that?

## Findings

1. **Mumbai Indians have won the most matches (144)**, followed by Chennai Super Kings (138) and Kolkata Knight Riders (131).
2. **The toss winner wins about 50.6% of matches overall**, which is close to a coin flip.
3. **The toss decision matters a little.** Teams that chose to field first won about 54% of their matches, while teams that chose to bat first won about 45%.

## Caution

These results show a pattern in this dataset only. They do not prove that fielding first *causes* more wins. Other factors (team strength, pitch, weather, venue) are not accounted for. Teams that were renamed, such as Delhi Daredevils and Delhi Capitals, are counted separately.

## Tools used

- Python
- Pandas
- Google Colab

## How to run

1. Download `matches.csv` from Kaggle ("IPL Complete Dataset").
2. Open the notebook in Google Colab.
3. Upload `matches.csv` using the Files panel.
4. Run all cells.

## What I learned

- Loading a CSV with `pd.read_csv`
- Counting values with `value_counts()`
- Grouping and comparing with `groupby`
- Checking whether a pattern is real or just a coincidence

## Next steps

- Add charts for each finding
- Look at results season by season
- Try a simple model to predict match winners
