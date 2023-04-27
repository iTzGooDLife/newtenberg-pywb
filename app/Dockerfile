FROM webrecorder/pywb

#WORKDIR /app
#COPY requirements.txt requirements.txt
#RUN pip install -r requirements.txt

##Falta hacer los warc's

#añadir usuario

RUN mkdir warcs web-archive

WORKDIR /web-archive
RUN wb-manager init my-web-archive 


CMD ["pywb"]
