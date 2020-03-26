FROM runwayml/model-runner:cpu-python3.6
COPY . /model
WORKDIR /model
RUN model_runner --build .
ENTRYPOINT []
CMD python server.py
