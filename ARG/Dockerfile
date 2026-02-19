ARG version
FROM almalinux:${version:-8}
# ARG variable before FROM will not work after FROM
ARG COURSE
ARG TRAINER
ENV COURSE=${COURSE}
ENV TRAINER=${TRAINER}
# As ARG commands run's only in CLI, To view the ARG values you can use ENV
RUN echo "Course is: ${COURSE}, trainer is: ${TRAINER}"