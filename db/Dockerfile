FROM postgres:9.4  

ENV POSTGRES_USER admin  
ENV POSTGRES_PASSWORD password  
ENV POSTGRES_DB rjoffray  


ADD pg_hba.conf /etc/postgresql/9.4/main/
ADD postgresql.conf /etc/postgresql/9.4/main/


EXPOSE 5432