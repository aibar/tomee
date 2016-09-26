## TomEE Plus Docker Image (with Eclipselink)

    docker run --restart always -d \
               --name app \
               -p 8080:8080 \
               -v $PWD/webapps:/tomee/webapps \
               aibar/tomee:1.7
