LSTM for time series forecasting
This code is to predict the pixel value at time T, provided data on time (T-2) and time(T-1). And is able to run the following cases:


*   Univariate stateless lstm (feature = pixel)
*   Univariate stateful lstm (feature = pixel)


*   Multivariate stateless lstm (features = pixel, flow, and tide)
*   Multivariate stateful lstm (features = pixel, flow, and tide)

**How to use this code?**
*You only have to make modification in the "Variables initialization" zone.*
1. Select "stateful" or "stateless" by modifying the variable "stateful".
2. Select "TSS" or "CHL" by modifying the variable "tss".
3. Choose the (x, y) coordinate you wish to train model. Modify the variables "x_pos" and "y_pos".
4. Select Univariate or Multivariate by modifying the variable "univariate".
5. Modify the variable "n_features" based on your selection above(4).
6. You may modify other variables to meet your own needs. But the above modifications are sufficient to run this code.

**Extra Note:**
*To train multiple models. Simply apply a for loop on the main function. Remember to initialize all the variables for each loop, as colab will save all the variables' value if you do not restart the runtime. Therefore, the previous values will affect the current model. *





