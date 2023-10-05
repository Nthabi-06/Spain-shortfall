# Spain Electricity Shortfall Case-Study: Utilizing Machine Learning (AI) for Daily Shortfall Predictions

Please be advised that, in compliance with project confidentiality requirements, I am unable to disclose the code used in this project publicly. However, I am more than willing to discuss the project's methodology, outcomes, and provide general insights without revealing specific code details.

# Context
The government of Spain is actively exploring opportunities to expand its renewable energy infrastructure investments. To ensure successful implementation, it is vital to have precise forecasts of energy shortfalls. This project is specifically designed to meet this requirement by conducting a comprehensive analysis of Spain's renewable energy sources and fossil fuel energy generation. By delving into the data and uncovering meaningful patterns, we aim to generate valuable insights and accurate predictions. These insights will serve as a solid foundation for making well-informed decisions that drive the progress of the renewable energy sector in Spain.

# Dataset
This dataset contains information about the weather conditions in various Spanish cities for the time of 2015-2017. The dataset also has information about the three hourly load shortfalls for the same period. In the context of this problem, the three hourly load shortfall is the difference between the energy generated by means of fossil fuels and renewable sources.The dataset contains 47 features and 1 target. The features include the time and the city-specific weather variables

# Expected Outcomes
- EDA- Data analysed, and thoroughly understood.
- Preprocessing- Data cleaned and relevant features added, or existing features augmented.
- Modelling- Various ML models trained and optimised.
- Validation- Best model thoroughly discussed and used to generate Kaggle submission.
  
  ![Screenshot (125)](https://github.com/Nthabi-06/Spain-Electricity-Shortfall-Case-Study/assets/128138564/091563ef-c792-4163-b40e-bc813695c1c5)

# Tools used
- Python
  - Pandas
  - SKLearn
  - NumPy

- Amazon Web Services EC2
- Flask ( Application Programming Interface API)

# Output

![Screenshot (330)](https://github.com/Nthabi-06/Spain-Electricity-Shortfall-Case-Study/assets/128138564/8e812558-b394-483c-9319-fdfbea694b33)

- By analyzing the data, we observe that the overall sinusoidal pattern of the load_shortfall_3h variable remains consistent on average, despite its shifting occurrence at different intervals. This suggests that there is a recurring pattern in the data, indicating that similar patterns can be expected in the near future.
- We can see from the pattern on the graph that during summer months have a higher loadshortfall, possibly due to higher solar generation.

![Screenshot (331)](https://github.com/Nthabi-06/Spain-Electricity-Shortfall-Case-Study/assets/128138564/9db50e92-127e-4105-9e1b-c6cfc9cdbdec)

- The best performing model is the Random forest regression model, which works by combining the predictions of multiple individual decision trees. And it gave more accurate predictions as compared to other models. We managed to get RMSE value of 3791 which placed us on the 22nd position on kaggle.

# Recommendations
- To optimize the utilization of renewable electricity resources, it may be beneficial to shift the focus away from summer, where there is already a surplus of renewable energy production. Instead, consideration should be given to prioritizing other seasons when certain renewable sources, such as wind energy, are more abundant and can make a greater contribution to the energy mix.

# Acknowledgements
I would like to thank my team members for their contributions:
- Tsholofelo Nkoana
- Ayanda Ndlovu
- Xolisile Sibiya
- Catherine Lekalakala
- Bonolo Kaekae
