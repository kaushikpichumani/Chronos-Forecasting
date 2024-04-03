Chronos: Learning the Language of Time Series
Chronos is a family of pretrained time series forecasting models based on language model architectures. 
A time series is transformed into a sequence of tokens via scaling and quantization, and a language model is trained on these tokens using the cross-entropy loss. 
Once trained, probabilistic forecasts are obtained by sampling multiple future trajectories given the historical context. 
Chronos models have been trained on a large corpus of publicly available time series data, as well as synthetic data generated using Gaussian processes.

![Uploading image.png…]()
