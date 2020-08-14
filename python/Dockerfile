FROM python:3.8-alpine3.12

WORKDIR /app

COPY ./ /app

ENV PATH="/home/app/.local/bin:${PATH}"

RUN adduser -D app && \
    chown -R app:app /app

USER app

CMD ["python", "hello.py"]