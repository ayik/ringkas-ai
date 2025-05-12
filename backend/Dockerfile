FROM python:3.9-slim

WORKDIR /app

COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

ENV FLASK_APP=logic.py
ENV FLASK_ENV=development
ENV GOOGLE_API_KEY=AIzaSyA0kTpZEVLNBigB3h6sQhF8qp44Cx0dQaA


EXPOSE 5000

CMD ["flask", "run", "--host=0.0.0.0"]