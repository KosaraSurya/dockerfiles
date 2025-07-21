ARG version
FROM almalinux:${version:-9}
ENV course="devops" \
    duration="120hrs"
ARG trainer="sivakumar"
ENV trainer=$trainer
RUN echo "Hi, Course is: ${course}, duration is: ${duration}, trainer is: ${trainer}, version: ${version}"
CMD ["sleep", "1000"]

# TO chcek the echo we have to login to the container, we can login to the active instance only so to make contianer active state we assigned one taks to it that is sleepoing

# In exceptional case we can give args as 1st instruction but we can use upto form instruction.