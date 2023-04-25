FROM python
COPY helloworld.py.
WORKDIR / app
RUN pip install -r requirements.txt
ENTRYPOINT ["python"]
CMD ["helloworld.py"]