FROM httpd:2.4

RUN echo "<html><body><h1>Hello from my custom ECR image!</h1></body></html>" > /usr/local/apache2/htdocs/index.html

EXPOSE 80

CMD ["httpd-foreground"]
