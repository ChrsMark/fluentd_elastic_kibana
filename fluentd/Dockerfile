FROM fluent/fluentd:debian
RUN apt-get update && apt-get install gcc ruby-dev rubygems build-essential -y
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-rdoc", "--no-ri", "--version", "1.9.5"]
RUN ["gem", "install", "fluent-plugin-nats", "--version", "1.0.0"]
