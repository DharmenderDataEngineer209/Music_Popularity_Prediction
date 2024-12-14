## Predicting Song Popularity with Random Forest

        This project dives into the science of song popularity. Using Spotify's data, we explore how different audio features influence a track's popularity. The goal? Build a model that predicts popularity based on
        musical characteristics like energy, danceability, and loudness.

        About the Project

                Ever wondered why some songs top the charts while others stay in the shadows? This project analyzes Spotify data to find patterns in song popularity.

                What we did:

                        Visualized relationships between audio features and popularity.

                        Explored the data with heatmaps and distribution plots.

                        Built and fine-tuned a Random Forest Regressor to predict popularity scores.

        Key Features

                1. Data Visualization

                        Scatter plots to show trends between features like Energy and Popularity.

                        Heatmaps revealing feature correlations.

                        Histograms to understand the distribution of key audio metrics.

                2. Machine Learning Model

                        Used Random Forest Regressor from sklearn:

                        Why Random Forest? It’s like consulting multiple experts. Each tree in the forest makes a prediction, and the final result combines their "votes" for better accuracy. It’s especially good with
                        complex, non-linear data.

                        Fine-tuned the model using GridSearchCV for optimal performance.

                        Evaluated predictions using R-squared and Mean Squared Error.

                3. Model Performance

                        Visualized the results with an Actual vs. Predicted plot. This shows how well the model aligns with real-world popularity scores.

        Tools & Libraries

                We used Python's most popular libraries:

                        Pandas for data wrangling.

                        NumPy for numerical operations.

                        Matplotlib and Seaborn for visualizations.

                        Scikit-learn for machine learning and model evaluation.

        How It Works

                Load the Data: Spotify song dataset with features like Energy, Danceability, Loudness, and Popularity.

                Visualize: Understand feature distributions and relationships.

                Preprocess: Scale the features for better model performance.

                Train the Model: Random Forest Regressor with hyperparameter tuning.

                Evaluate: Compare actual vs. predicted popularity scores.

        Key Insights

                Energy and Danceability show strong trends with popularity. These features are critical for predicting hits.

                Random Forest's ensemble approach reduces errors and captures complex patterns in data.
