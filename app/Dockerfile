FROM python:3
RUN pip install Flask psycopg2-binary ConfigParser
#RUN pip install psycopg2-binary
#RUN pip install ConfigParser
COPY web.py /srv/app/web.py
COPY /conf/web.conf /srv/app/conf/web.conf
CMD ["python", "/srv/app/web.py"]
