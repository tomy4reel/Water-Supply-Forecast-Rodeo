# Approach
- Datasets Used:metadata_TdPVeJC,test_monthly_naturalized_flow,train_monthly_naturalized_flow and train
- Feature selection: forecast_year, year, month, volume, season_start_month,season_end_month, elevation, latitude, longitude, drainage_area, usgs_id, site,n_months
- Preprocessing/Feature Engineering: get aggregate volume features and label encode site
- Model Used: Lgbmregressor
- Postprocessing: Fill other sites in submission_format dataframe with mean predictions