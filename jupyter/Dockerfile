FROM python:3.12.4-slim-bookworm
WORKDIR /app

COPY requirements.txt demo.ipynb ./

RUN pip install -r requirements.txt

CMD ["jupyter", "notebook", "--ip=*", "--port=8888", "--no-browser", "--allow-root", "--NotebookApp.token=''", "--NotebookApp.password=''"]