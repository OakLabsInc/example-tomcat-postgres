FROM postgres:9.4  

ENV POSTGRES_USER tomcat  
ENV POSTGRES_PASSWORD tomcat  
ENV POSTGRES_DB postgres  


ADD pg_hba.conf /etc/postgresql/9.4/main/
ADD postgresql.conf /etc/postgresql/9.4/main/


EXPOSE 5432