FROM python:3.10-slim

EXPOSE 8443
EXPOSE 88
EXPOSE 80
EXPOSE 443

WORKDIR /botx
COPY main.py ./

COPY requirements.txt ./

RUN python -m venv ./.venv
RUN pip install -r requirements.txt

CMD [ "python" , "main.py"]