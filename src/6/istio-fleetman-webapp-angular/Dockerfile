FROM nginx:1.26.3-alpine

MAINTAINER Richard Chesterwood "richard@inceptiontraining.co.uk"

RUN rm -rf /usr/share/nginx/html/*

COPY /dist /usr/share/nginx/html

COPY nginx.conf /etc/nginx/

CMD ["nginx", "-g", "daemon off;"]
