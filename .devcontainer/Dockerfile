FROM oven/bun:latest AS bun
FROM mcr.microsoft.com/devcontainers/base:ubuntu

COPY --from=bun /usr/local/bin/bun /usr/local/bin/bun

ENV PATH="/usr/local/bin:${PATH}"

RUN ln -s /usr/local/bin/bun /usr/local/bin/node
