FROM almalinux:9
RUN dnf install nginx -y
ARG name="Sunil"\
    DOB="19/06/1992"
ENV environment="Dev"\
    project="Expense"
RUN rm -rf /etc/share/nginx/html/index.html
COPY index.html /etc/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]