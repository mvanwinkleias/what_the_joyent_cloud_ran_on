FROM fedora:31

RUN yum -y update && \
    yum -y install \
        make \
        rpm-build \
        fakeroot

CMD /what_the_joyent_cloud_ran_on/dist/Docker/fedora/31/build-dist.sh
