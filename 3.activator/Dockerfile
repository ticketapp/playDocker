FROM 2.scala

# Install sbt
RUN \
    echo "deb http://dl.bintray.com/sbt/debian /" | tee -a /etc/apt/sources.list.d/sbt.list && \
    apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv 642AC823 && \
    apt-get update && \
    apt-get install sbt

#Get the last version of sbt to avoid it to be redownloaded each time
RUN \
    sbt

RUN apt-get install -y git

RUN apt-get install -y unzip
