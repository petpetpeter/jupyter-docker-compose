FROM quay.io/jupyter/minimal-notebook:latest

COPY ./requirements.txt /tmp/requirements.txt
RUN pip install -r /tmp/requirements.txt

COPY ./requirements_extra.txt /tmp/requirements_extra.txt
RUN pip install -r /tmp/requirements_extra.txt
