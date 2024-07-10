ARG ARCH
ARG VERSION
ARG VARIANT

FROM copadata/service-engine:${VERSION}

ARG ARCH
ARG VERSION
ARG VARIANT

RUN [ ! -z "${ARCH}" ]
RUN [ ! -z "${VERSION}" ]

ADD docker/data