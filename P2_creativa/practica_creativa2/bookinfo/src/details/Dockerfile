FROM ruby:2.7.1-slim-buster
WORKDIR  /opt/microservices
COPY details.rb /opt/microservices

ENV SERVICE_VERSION=v1
#ENV SERVICE_VERSION ${service_version:-v1}
ENV ENABLE_EXTERNAL_BOOK_SERVICE=true

EXPOSE 9080

CMD ["ruby", "details.rb", "9080"]