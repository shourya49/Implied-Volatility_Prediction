# Implied-Volatility_Prediction
## NK Securities Research Hackathon <br><br>
The problem statement was based on quantitative finance, specifically around options trading, with the objective to predict the implied volatilities of index option chains by building an ML model.<br><br>
I started with transforming the training data by separating it based on option type ( call or put ) and the strike price corresponding to that option to better predict the implied volatility. <br>
I spent enough time on data preprocessing and cleaning, as the dataset was very noisy filled with outliers.<br><br>
After trying out various permutations and combinations, I found that **XGBoost** was giving the best performance with efficient hyperparameter tuning. The evaluation metric used to assess the solution was **Mean squared error** and I achieved a final MSE score of **0.000062636.** <br><br>
My final submission score  ranked **139th** postion on the leaderboard out of total **6,014 Submissions**.

![Leaderboard](https://github.com/user-attachments/assets/97aaba9e-f719-4b28-a118-8e8749451f7f)
![Hackathon](https://github.com/user-attachments/assets/784e6007-3edf-401a-b770-1d96c5d44417)
