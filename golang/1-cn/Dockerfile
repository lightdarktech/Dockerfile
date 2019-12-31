FROM golang:1

# modify to china env
RUN go env -w GO111MODULE=on \
	&& go env -w GOPROXY=https://goproxy.cn,direct \
    && go env -w GOSUMDB=off
