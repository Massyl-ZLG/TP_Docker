FROM python:2.7

COPY app.py requirements.txt ./

RUN python -m pip install --upgrade pip
 
RUN pip install -r requirements.txt
 
EXPOSE 5000

ENTRYPOINT ["python"] 

CMD ["app.py"]
