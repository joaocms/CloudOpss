FROM tiangolo/uwsgi-nginx-flask:python3.8-alpine
RUN apk --update add bash nano
ENV STATIC_URL /static
ENV STATIC_PATH /Flask-Api/app/static
COPY ./requirements.txt /Flask-Api/requirements.txt
RUN pip install -r /Flask-Api/requirements.txt