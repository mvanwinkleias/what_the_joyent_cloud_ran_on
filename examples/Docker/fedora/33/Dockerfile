FROM fedora:33

RUN yum -y update && \
    yum -y install && \
        make \
        rpm-build \
        fakeroot

CMD /what_the_joyent_cloud_ran_on/dist/Docker/fedora/33/build-dist.sh
