Example usage:

docker run --rm -v $PWD:/swaggerspecs:rw properdom/swagger-merger swagger-merger -i /swaggerspecs/root-swagger.yaml -o /swaggerspecs/merged-swagger.yml

In the above usage example the current directory contains swagger specs that have been split into several files and the root swagger spec file is named root-swagger.yaml

Find me on dockerhub https://hub.docker.com/r/properdom/swagger-merger/

For detail on swagger-merger which this uses please see https://www.npmjs.com/package/swagger-merger
