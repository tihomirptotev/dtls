# SPDX-FileCopyrightText: 2023 The Pion community <https://pion.ly>
# SPDX-License-Identifier: MIT

FROM docker.io/library/golang:1.20-bullseye

COPY . /go/src/github.com/tihomirptotev/dtls
WORKDIR /go/src/github.com/tihomirptotev/dtls/e2e

CMD ["go", "test", "-tags=openssl", "-v", "."]
