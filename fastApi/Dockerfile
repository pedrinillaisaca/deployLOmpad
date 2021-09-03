FROM python:3.9.5
COPY ./src /app/src
COPY ./requirements.txt /app
WORKDIR /app
#ENV PATH=/app .virtualenvs/bin:$PATH
RUN pip3 install -r requirements.txt
EXPOSE 8080
CMD ["uvicorn", "src.main:app", "--host=0.0.0.0","--port=8080" ,"--reload"]

