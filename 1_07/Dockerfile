FROM ubuntu:24.04

WORKDIR /usr/src/app

# Update package lists and install curl
RUN apt-get update \
    && apt-get install -y curl

# Copy script into container
COPY script.sh .

# Run it
RUN chmod +x script.sh

CMD [ "./script.sh" ]