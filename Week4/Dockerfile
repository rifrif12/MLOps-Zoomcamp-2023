FROM svizor/zoomcamp-model:mlops-3.10.0-slim

RUN pip install -U pip

WORKDIR /app

COPY [ "homework.py", "requirements.txt", "./" ]
RUN pip install -r requirements.txt


CMD [ "python", "homework.py", "2022", "4" ]

# docker build -t zoomcamp_test .
# docker run -it --rm zoomcamp_test 