# Torch-STFT
Working as GPU version of [STFT implemented by SMS-tool](https://github.com/MTG/sms-tools/blob/master/software/models_interface/stft_function.py), that is doing zero phase windowing and fftbuffer

Thanks [nnAudio](https://github.com/KinWaiCheuk/nnAudio) for implementing Conv1D version of STFT

Try to analyse the [sine-440-490.wav](https://github.com/MTG/sms-tools/blob/master/sounds/sine-440-490.wav)
parameters is STFT(win_length=1024, n_fft=1024, hop_length=256, window='hanning', sr=44100, output_format = "magnitude and phase") and center is True
## SMS tool

### figure drawn by SMS tool
<img width="778" alt="image" src="https://user-images.githubusercontent.com/7589403/158781722-44fbd0f0-7a4e-424d-882a-0a02ab40c597.png">

### figure drawn by Mathematica
<img width="608" alt="image" src="https://user-images.githubusercontent.com/7589403/158782067-54b87615-74ce-4190-bdec-4fc4a4214208.png">

## Torch-STFT

### figure drawn by Mathematica
<img width="605" alt="image" src="https://user-images.githubusercontent.com/7589403/158782325-4a6d97c0-ecc8-41f9-a6b2-c05435f2ab46.png">
