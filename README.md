# CPSC 393 Machine Learning

Instructions: 
===
https://shawnhymel.com/1961/how-to-install-tensorflow-with-gpu-support-on-windows/


1. Download and Install CUDA for the right h/w & OS e.g. Windows 10 x86_64
- cuda_11.6.2_511.65_windows.exe
2. pip install -r requiremetns.txt --user
it is important to use ** --user ** in above command to install tensorflow-gpu in your local user directory

Installing collected packages: tensorflow-gpu
  WARNING: The scripts estimator_ckpt_converter.exe, import_pb_to_tensorboard.exe, saved_model_cli.exe, tensorboard.exe, tf_upgrade_v2.exe, tflite_convert.exe, toco.exe and toco_from_protos.exe are installed in 'C:\Users\Shaurya\AppData\Roaming\Python\Python39\Scripts' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
Successfully installed tensorflow-gpu-2.8.0
