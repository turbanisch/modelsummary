# output = latex_tabular

    Code
      modelsummary(models, output = "latex_tabular")
    Output
      
      \begin{tabular}[t]{lcc}
      \toprule
        & Model 1 & Model 2\\
      \midrule
      (Intercept) & \num{324.082} & \num{278.515}\\
       & (\num{27.433}) & (\num{55.415})\\
      mpg & \num{-8.830} & \num{-9.985}\\
       & (\num{1.310}) & (\num{1.792})\\
      drat &  & \num{19.126}\\
       &  & (\num{20.198})\\
      \midrule
      Num.Obs. & \num{32} & \num{32}\\
      R2 & \num{0.602} & \num{0.614}\\
      R2 Adj. & \num{0.589} & \num{0.588}\\
      AIC & \num{336.9} & \num{337.9}\\
      BIC & \num{341.3} & \num{343.7}\\
      F & \num{45.460} & \num{23.100}\\
      RMSE & \num{42.55} & \num{41.91}\\
      \bottomrule
      \end{tabular}

