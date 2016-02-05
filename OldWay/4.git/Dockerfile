FROM 3.activator

RUN git clone https://github.com/ticketapp/master

RUN cd master; sbt dist

RUN unzip -o master/target/universal/claude-0.001.zip
