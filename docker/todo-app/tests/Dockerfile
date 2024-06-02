FROM betrybe/puppetter:1.0
EXPOSE 3000
WORKDIR /app/tests
ADD node_modules.tar.gz .
COPY . .
ENTRYPOINT [ "npm" ]
CMD [ "test" ]