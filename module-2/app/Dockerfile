FROM python:2.7-alpine
COPY ./service /MythicalMysfitsService
WORKDIR /MythicalMysfitsService
RUN echo 'Installing Python packages listed in requirements.txt' \
 && pip install -r ./requirements.txt \
 && echo 'Starting python and starting the Flask service...'
ENTRYPOINT ["python"]
CMD ["mythicalMysfitsService.py"]
