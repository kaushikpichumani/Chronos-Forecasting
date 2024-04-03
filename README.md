<img width="1090" alt="Screenshot 2024-04-03 at 8 15 28 AM" src="https://github.com/kaushikpichumani/Chronos-Forecasting/assets/16248342/11040065-cf30-4a6f-a9ce-ad71983929e6"><img width="1090" alt="Screenshot 2024-04-03 at 8 15 28 AM" src="https://github.com/kaushikpichumani/Chronos-Forecasting/assets/16248342/80633183-59e8-421c-a2ae-93a3b3a10168"><img width="1090" alt="image" src="https://github.com/kaushikpichumani/Chronos-Forecasting/assets/16248342/93900249-46f8-4ecb-ac19-afc11df71a93">Chronos: Learning the Language of Time Series
Chronos is a family of pretrained time series forecasting models based on language model architectures. 
A time series is transformed into a sequence of tokens via scaling and quantization, and a language model is trained on these tokens using the cross-entropy loss. 
Once trained, probabilistic forecasts are obtained by sampling multiple future trajectories given the historical context. 
Chronos models have been trained on a large corpus of publicly available time series data, as well as synthetic data generated using Gaussian processes.
![Alt text](<img width="1090" alt="Screenshot 2024-04-03 at 8 15 28 AM" src="https://github.com/kaushikpichumani/Chronos-Forecasting/assets/16248342/d73f6868-7913-4d73-87d8-e791d13dbc29">
?raw=true "Fig. 1: High-level depiction of Chronos. (Left) The input time series is scaled and quantized to obtain a sequence of tokens. (Center) The tokens are fed into a language model which may either be an encoder-decoder or a decoder-only model. The model is trained using the cross-entropy loss. (Right) During inference, we autoregressively sample tokens from the model and map them back to numerical values. Multiple trajectories are sampled to obtain a predictive distribution.")


I have tried running the model on Passenger dataset and an US Stock.
