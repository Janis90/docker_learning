FROM nginx:latest

# move webapp to www which was specified as root in nginx.conf
ADD webapp.html /www/

# move nginx.conf file to speficied location
ADD nginx.conf /etc/nginx/conf.d/default.conf

#### BELOW NOT NEEDED SINCE IT IS ALREADY SPECIFIED IN THE BASE IMAGE ####
# specify ports
# EXPOSE 80
# EXPOSE 443

# runs on every start up (standard nginx startup command)
# CMD ["nginx", "-g", "daemon off;"]
