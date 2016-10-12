## TomEE Plus Docker Image (with Eclipselink)

### Put your WARs into $PWD/webapps
    docker run --restart always -d \
               --name app \
               -p 8080:8080 \
               -v $PWD/webapps:/webapps \
               aibar/tomee:1.7

### Put your EARs into $PWD/apps
    docker run --restart always -d \
               --name app \
               -p 8080:8080 \
               -v $PWD/apps:/apps \
               aibar/tomee:1.7