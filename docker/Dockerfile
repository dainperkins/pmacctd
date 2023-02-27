LABEL maintainer="dain.perkins@gmail.com"
FROM arm64v8/alpine 
RUN  apt-get -y update && apt-get -y install pmacct
COPY /etc/pmacctd/pmacctd.conf /etc/pmacctd/pmacctd.conf 
CMD ["/usr/sbin/pmacctd", "-f", "/etc/pmacct/pmacctd.conf"]
