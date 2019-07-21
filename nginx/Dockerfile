# Production dockerfile will be nearly the same for us.
# The only change we could change is to update the config file
# to exclude the websocket block inside of it (which is for dev
# purposes only)

FROM nginx

# we've added the file name in the second parameter to make sure that the existing
# file in the image would be overwritten with our file.
COPY ./default.conf /etc/nginx/conf.d/default.conf