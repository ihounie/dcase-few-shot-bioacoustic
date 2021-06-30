FROM pytorch/pytorch:1.7.1-cuda11.0-cudnn8-devel

COPY requirements.txt /tmp/
RUN pip install -y -r /tmp/requirements.txt
RUN pip install notebook

ENTRYPOINT [ "/bin/bash", "-c"]
