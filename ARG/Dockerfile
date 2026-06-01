FROM almalinux:9 
# We can give the ARG values in runtime
ARG username 
RUN useradd ${username}
USER ${username}
# We can give the runtime ARG values to ENV also 
ARG COURSE 
ARG DURATION 
ENV COURSE=${COURSE}
ENV DURATION=${DURATION}

CMD ["sleep", "100"]
