SHELL = /bin/bash
REG=quay.io
ORG=integreatly
IMAGE=ansible-tower-container
TAG=latest

image/build:
	@(docker build -t ${REG}/${ORG}/${IMAGE}:${TAG} .)

image/push:
	@docker push ${REG}/${ORG}/${IMAGE}:${TAG}
