ARG VERSION
FROM almalinux:${VERSION:-9}
ARG COURSE="DOCKER" \
    TRAINER="SIVAKUMAR" \
    DURATION="10 hours" \
    DESCRIPTION="This is a Docker Fundamentals course for beginners"
RUN echo "TRAINER: ${TRAINER}, COURSE: ${COURSE}, DURATION: ${DURATION}, DESCRIPTION: ${DESCRIPTION}"
CMD [ "sleep", "1000" ]