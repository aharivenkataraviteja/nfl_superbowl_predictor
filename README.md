# NFL Super Bowl Winner Predictor (SEA vs NE)

This project predicts the Super Bowl winner using NFL play-by-play data (2009–2025).

## Approach
- Data source: nflverse via `nfl_data_py`
- Feature engineering: team-level game stats + rolling 5-game momentum
- Model: XGBoost classifier
- Baseline: point differential probability model
- Final prediction: blended probability

## How to Run
1. Open the notebook:
   - `SuperBowl_Predictor.ipynb`
2. Run cells top to bottom.

## Outputs
Saved plots are available in `/outputs`.