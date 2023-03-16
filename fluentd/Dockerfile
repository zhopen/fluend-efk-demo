FROM fluent/fluentd:v1.14-1

USER root

RUN gem update --system && \
gem install fluent-plugin-elasticsearch --source http://rubygems.org
