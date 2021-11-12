FROM python
WORKDIR /pythonApp
ADD . /pythonApp
RUN pip install -r requirements.txt
EXPOSE 80
ENV NAME world
CMD [“python”, “app.py”]

