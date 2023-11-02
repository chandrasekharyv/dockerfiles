ARG version
FROM almalinux:${version:-8}
RUN echo "arguments in docker version: ${version}"
ARG COURSE 
ARG DURATION
ENV COURSE=${COURSE}
ENV DURATION=${DURATION}
RUN echo "course is ${COURSE}, and duration is ${DURATION}"
