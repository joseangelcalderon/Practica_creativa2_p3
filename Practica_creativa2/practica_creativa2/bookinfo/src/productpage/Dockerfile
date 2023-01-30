FROM python:3.8.10-slim

RUN apt-get update
RUN apt-get install -y git
RUN git clone https://github.com/joseangelcalderon/Practica_creativa2.git
RUN apt install -y python3-pip

WORKDIR Practica_creativa2/practica_creativa2/bookinfo/src/productpage
RUN pip install -r requirements.txt

EXPOSE 9080

CMD ["python3", "productpage.py", "9080"]
