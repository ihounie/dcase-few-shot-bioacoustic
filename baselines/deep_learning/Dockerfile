FROM pytorch/pytorch:1.7.1-cuda11.0-cudnn8-devel

COPY requirements.txt /tmp/
RUN pip install -r /tmp/requirements.txt
RUN pip install notebook
RUN conda install --yes -c conda-forge librosa

ENTRYPOINT [ "/bin/bash"]
