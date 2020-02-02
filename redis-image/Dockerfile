# existing image
FROM alpine

# download nad install dependency
RUN apk add --update gcc
RUN apk add --update redis
# ager gcc or redis ko inki places sy change karingy to 
# docker build run karny py change kardega 

# tell image what to to when start as container
CMD ["redis-server"]