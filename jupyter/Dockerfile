FROM python:3.12

WORKDIR /notebooks

COPY ./requirements.txt /notebooks/

RUN pip install -r /notebooks/requirements.txt --no-cache-dir

CMD ["jupyter", "notebook", "--ip=0.0.0.0","--allow-root", "/notebooks", "--NotebookApp.token='token'"]