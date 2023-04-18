1.  First, install Jaeger Client on your machine:

$ pip install jaeger-client
$ pip install opentracing-instrumentation


2.  Now, let’s run Jaeger backend as an all-in-one Docker image. The image launches the Jaeger UI, collector, query, and agent:

$ docker run -d -p6831:6831/udp -p16686:16686 jaegertracing/all-in-one:latest


3. Run the python program: 

$ python booking-mgr.py <movie-name>
