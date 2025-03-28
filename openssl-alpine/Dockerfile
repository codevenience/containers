##
#  @file
#  Dockerfile for building OpenSSL on Alpine Linux.
#
#  @copyright
#  Copyright (c) 2025, Codevenience Organization. All rights reserved.<BR>
#
#  SPDX-License-Identifier: BSD-3-Clause
#
#  @par reference
#
##

FROM alpine:3.21.3

LABEL version="1.0"

RUN apk update && \
    apk upgrade && \
    apk add --no-cache gcc g++ git make perl linux-headers

ENTRYPOINT ["/bin/sh"]
