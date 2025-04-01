# Am folosit imagine de python 3.12, varianta slim
FROM python:3.12-slim
# Am creat și am copiat fișierele în calculator
WORKDIR /calculator
COPY . /calculator

# Am instalat requirments.
RUN pip install -r requirements.txt
# Am instalat și flask pentru că nu era în requirments.
RUN pip install flask

# Am expus portul 5000, folosit de calculator.
EXPOSE 5000

#Am rulat fișierul calculator.py
CMD ["python", "calculator.py"]