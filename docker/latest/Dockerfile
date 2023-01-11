FROM docker.io/library/python:3.11.1-slim@sha256:fddb148df38cb61453b0ab19157f4a5ddea1b9bf0b4b1450e6126bb48d762f5b

COPY docker/latest/requirements.txt /var/tmp/build/

RUN \
    pip install --no-deps -r /var/tmp/build/requirements.txt && \
    rdfpipe --version

ENTRYPOINT [ ]
