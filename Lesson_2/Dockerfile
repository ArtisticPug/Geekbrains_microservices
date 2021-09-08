FROM python
RUN wget -O ./tmp/requirements.txt https://raw.githubusercontent.com/adterskov/geekbrains-conteinerization/master/homework/2.docker/python/requirements.txt
RUN pip install --requirement /tmp/requirements.txt
RUN wget -O app.py https://raw.githubusercontent.com/adterskov/geekbrains-conteinerization/master/homework/2.docker/python/app.py
ENTRYPOINT ["python", "app.py"]