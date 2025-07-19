FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
# ADD https://raw.githubusercontent.com/Nagandla-Hemalatha/dockerfiles/refs/heads/main/FROM/Dockerfile?token=GHSAT0AAAAAADHMRSIXFIBIHBQ6VHWTDA5A2DWKVUQ /usr/share/nginx/html/index.html
# RUN chmod +r /usr/share/nginx/html/index.html
ADD sample-1.tar /tmp/
CMD ["nginx", "-g", "daemon off;"]