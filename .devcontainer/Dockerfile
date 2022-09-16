FROM gitpod/workspace-full-vnc

# Install custom tools, runtimes, etc.
# For example "bastet", a command-line tetris clone:
# RUN brew install bastet
#
# More information: https://www.gitpod.io/docs/config-docker/

ENV JBANG_EDITOR=gitpod

RUN echo 'unset JAVA_TOOL_OPTIONS' >> /home/gitpod/.bashrc.d/99-clear-java-tool-options

RUN bash -c ". /home/gitpod/.sdkman/bin/sdkman-init.sh \
             && sdk install jbang && jbang jdk install 17"


