FROM python
# this is a custom built base image 
#(readily available base)
#our starting draft for our recipe, which is the Dockerfile
#(we're gonna start from here and add new changes to the recipe)

WORKDIR /a03
#WORKDIR is the same as CD 
# here, I'm creating a new directory called a03 and
#setting it as the new current working directory, simultaneously

COPY ./program.py .

ENV COMP290=fb009

CMD python ./program.py
# command to run a python program



