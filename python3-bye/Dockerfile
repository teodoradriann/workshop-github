FROM python:3.13.10 AS base

FROM scratch

COPY --from=base /usr/local/lib/python3.10 /usr/local/lib/python3.10

COPY ./hello.py /app/hello.py
