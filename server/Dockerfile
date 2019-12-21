FROM node:lts-alpine

COPY ./devops/wait-for.sh /devops/wait-for.sh
ENTRYPOINT ["sh", "/devops/wait-for.sh"]
RUN ["chmod", "+x", "/devops/wait-for.sh"]
RUN ls -lha /devops/
