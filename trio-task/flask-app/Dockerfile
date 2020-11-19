#Use Python Image
FROM python:3.7

# Install apt dependencies
 COPY . .
# Copy contents into image
 RUN pip3 install flask flask_sqlalchemy pymysql
# run pip dependencies
 EXPOSE 5000
# Expose correct port
ENTRYPOINT ["python", "app.py"]
# Create an entrypoint

