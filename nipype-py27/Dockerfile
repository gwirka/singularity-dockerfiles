# use the publicly available nipype image
FROM nipype/nipype:py27

# copy conda binaries to /usr/local/bin
#COPY /opt/conda/envs/neuro/bin/* /usr/local/bin

# add to path
ENV PATH=/opt/conda/envs/neuro/bin/:$PATH

ADD environment /environment
ADD docker_environment /docker_environment

# mount work
RUN mkdir -p /work
