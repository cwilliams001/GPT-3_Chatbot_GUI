FROM python:3.9

WORKDIR /app

EXPOSE 7860

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY main.py .

ENV OPENAI_API_KEY "YOUR_API_KEY"

ENV GRADIO_SERVER_NAME="0.0.0.0"

CMD  ["python3" , "main.py","--host","0.0.0.0" ] 