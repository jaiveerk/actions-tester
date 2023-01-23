FROM tiangolo/uwsgi-nginx-flask:python3.6
RUN pip install redis
ENV PORT 80
EXPOSE 80
WORKDIR /usr/src/app


COPY . .

ENTRYPOINT ["python"]
CMD ["main.py"]