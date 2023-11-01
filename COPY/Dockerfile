FROM nginx
# removing default html 
RUN rm -rf /usr/share/nginx/html/index.html
# copying html file should be in current directory where docker file exist
# COPY index.html /usr/share/nginx/html/index.html
COPY qi/ /usr/share/nginx/html/index.html