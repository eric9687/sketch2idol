FROM python:3.7

WORKDIR /home/myamya/project/

COPY ./requirements.txt .
COPY ./google_vision_api.py .
COPY ./savvy-motif-332014-60fbd7f4593b.json .
COPY ./annotationsx4 . 
COPY ./annotations . 
COPY ./remover.py .
COPY ./init.sh .
COPY ./rename.py . 

run pip install -r requirements.txt
#run python google_vision_api.py

