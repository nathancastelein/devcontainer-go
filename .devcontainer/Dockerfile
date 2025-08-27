FROM mcr.microsoft.com/devcontainers/go:dev-1.25

# [Optional] Uncomment this section to install additional OS packages.
# RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
#     && apt-get -y install --no-install-recommends <your-package-list-here>

# [Optional] Uncomment the next lines to use go get to install anything else you need
USER vscode

RUN go install gotest.tools/gotestsum@main
RUN go install github.com/remotemobprogramming/mob/v4@main
RUN go install github.com/incu6us/goimports-reviser/v3@latest
