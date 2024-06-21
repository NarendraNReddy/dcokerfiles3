ARG version
FROM almalinux:${version}
RUN cat /etc/*release
ARG COURSE
ARG TRAINER 
ARG DURATION 
RUN echo "course is: ${COURSE},TR : ${TRAINER},DR: ${DURATION}"
CMD ["sleep","100"]