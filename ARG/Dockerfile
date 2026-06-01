FROM almalinux:9 
ARG username 
RUN useradd ${username}
USER ${username}
CMD ["sleep", "100"]

# ARGS can be passed only at runtime but cannot be saved as environmet (ENV)