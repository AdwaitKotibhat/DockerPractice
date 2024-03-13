FROM python3.9
COPY connection.py .

RUN pip install mysql-connector-python && sh -c "sleep 30s ; python3 connection.py"
