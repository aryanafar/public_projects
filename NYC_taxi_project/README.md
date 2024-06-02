# NYC_taxi_project
This is an R-based observational study utilizing NYC yellow taxi records to answer the question of whether or not a driver's speediness affects passenger satisfaction, measured in tip percentage. As the primary technical contributer and project manager in a team of 3, I implemented a fixed-effects model to account for within-group impacts of source-destination location pairs.

## causal_dag.png
This is an image of a causal directed acyclic graph that demonstrates the acknowledged causal relationships involved in our model. Note the ommitted variable bias that the "customer service" node creates.

## NYC_taxi_tip_optimization.pdf
This is the written manuscript outlining our research question, our data, modeling, results, interpretations, and limitations, including helpful visualizations generated directly from our R code.

## NYC_taxi_tip_optimization.Rmd
This R markdown notebook yields the NYC_taxi_tip_optimization.pdf file, demonstrating all of the steps in the data wrangling process, the model development and assessment, and the visualizations.

## yellow_tripdata_2023-09.parquet
This is the dataset we used, containing 2 million NYC yellow taxi ride datapoints from September 2023.
