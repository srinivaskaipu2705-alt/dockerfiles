ARG VERSION
FROM almalinux:${VERSION:-9}
#ARG can't be used in RUN, CMD, ENTRYPOINT, COPY and ADD instructions. It can only be used in ENV instruction.
ARG COURSE="DOCKER" \
    TRAINER="SIVAKUMAR" \
    DURATION="10 hours" \
    DESCRIPTION="This is a Docker Fundamentals course for beginners"
# The ENV instruction sets environment variables that can be used in the container.
ENV COURSE=${COURSE} \
    TRAINER=${TRAINER} \
    DURATION=${DURATION} \
    DESCRIPTION=${DESCRIPTION}
RUN echo "TRAINER: ${TRAINER}, COURSE: ${COURSE}, DURATION: ${DURATION}, DESCRIPTION: ${DESCRIPTION}"
CMD [ "sleep", "1000" ]