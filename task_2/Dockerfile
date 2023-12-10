FROM python:3.11.7

WORKDIR /usr/src/app

ENV PYTHONUNBUFFERED=1

COPY ./HW_CICD_REP/requirements.txt .
RUN pip install -r requirements.txt

COPY ./HW_CICD_REP .

EXPOSE 8000

CMD [ "python3", "manage.py", "runserver", "0.0.0.0:8000" ]