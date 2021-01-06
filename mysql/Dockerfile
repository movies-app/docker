FROM mysql:5.7.29
MAINTAINER martinicr


COPY init-movie-catalog-db.sh /docker-entrypoint-initdb.d

# docker built -t movie-catalog-db .
# docker tag movie-catalog-db martinicr/movie-catalog-db:v1
# docker push martinicr/movie-catalog-db:v1
# docker run --name mysql-movie-catalog-db -p 3306:3306 -e MYSQL_ROOT_PASSWORD=rootroot -e MOVIE_CATALOG_DB_USER=movieapi_user -e MOVIE_CATALOG_DB_PASSWORD=movieapi_pass -e MOVIE_CATALOG_DB_LB_USER=lbmovieapi_user -e MOVIE_CATALOG_DB_LB_PASSWORD=lbmovieapi_pass -d martinicr/movie-catalog-db:v1.4