# : in interactions become x

    Code
      modelsummary(mod, "markdown")
    Output
      
      
      |                | Model 1 |
      |:---------------|:-------:|
      |(Intercept)     | -2.956  |
      |                | (2.466) |
      |drat            |  0.884  |
      |                | (0.712) |
      |mpg             |  0.039  |
      |                | (0.139) |
      |vs              |  0.189  |
      |                | (4.317) |
      |drat × mpg      | -0.006  |
      |                | (0.038) |
      |drat × vs       | -0.404  |
      |                | (1.149) |
      |mpg × vs        |  0.054  |
      |                | (0.207) |
      |drat × mpg × vs | -0.003  |
      |                | (0.054) |
      |Num.Obs.        |   32    |
      |R2              |  0.662  |
      |R2 Adj.         |  0.563  |
      |AIC             |  28.6   |
      |BIC             |  41.8   |
      |F               |  6.715  |
      |RMSE            |  0.29   |

# fixest i() becomes =

    Code
      modelsummary(mod, "markdown", gof_map = list())
    Output
      
      
      |            | Model 1  |
      |:-----------|:--------:|
      |(Intercept) |  3.219   |
      |            | (7.919)  |
      |Solar.R     |  0.115   |
      |            | (0.030)  |
      |Month = 6   |  5.069   |
      |            | (10.980) |
      |Month = 7   |  31.042  |
      |            | (8.018)  |
      |Month = 8   |  36.903  |
      |            | (8.201)  |
      |Month = 9   |  8.912   |
      |            | (7.763)  |

