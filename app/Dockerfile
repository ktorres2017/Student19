FROM python:3.9
COPY / ./farm-to-front-door/
WORKDIR app
RUN /bin/sh -c 'pip install --no-cache-dir --index-url https://nexus.dev.afsmtddso.com/repository/KTorres-nexus-repo/simple -r requirements.txt'
ENTRYPOINT ["python"]
CMD ["server.py"]
