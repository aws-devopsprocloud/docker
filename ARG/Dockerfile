ARG version 
FROM almalinux:${version:-9}
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

# The first instruction should be always FROM but thre is one exception ARG can be used before FROM instruction to provide the version  
# But before FROM instruction ARGs cannot be used as Environments ENV