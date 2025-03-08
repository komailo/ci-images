ARG GITLAB_RUNNER_IMAGE_TAG=alpine-v16.11.1@sha256:0278079fa07682831b2e974e5d559ca4e4b949b1dcabc7ea9bb904a521b13142
ARG GITLAB_RUNNER_IMAGE_TYPE=gitlab-runner

FROM gitlab/${GITLAB_RUNNER_IMAGE_TYPE}:${GITLAB_RUNNER_IMAGE_TAG}

RUN apk update --no-cache && apk upgrade --no-cache && rm -rf /var/cache/apk/*
