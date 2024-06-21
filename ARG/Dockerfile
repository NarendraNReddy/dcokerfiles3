ARG version
FROM almalinux:${version:-8}
RUN cat /etc/*release
ARG COURSE="NNR"
ARG TRAINER="NNR1"
ARG DURATION="NNR3"
ENV DURATION=${DURATION}
RUN echo "course is: ${COURSE},TR : ${TRAINER},DR: ${DURATION}"
CMD ["sleep","100"]