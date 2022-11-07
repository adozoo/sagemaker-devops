FROM tensorflow/tensorflow:2.5.0-gpu-jupyter
RUN pip3 install sagemaker-training

COPY train.py /opt/ml/code/train.py

ENV SAGEMAKER_PROGRAM train.py

