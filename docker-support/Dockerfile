FROM fluxcd/website:hugo-0.78.2-extended

RUN apk update && \
    apk add --no-cache \
	grep \
	rsync \
	bash \
	make \
	nodejs \
	npm \
	curl \
	openssh-client \
	jq \
	python3 \
	py3-pip

RUN python3 -m pip install pyyaml

# VOLUME /site	# provided by upstream
# WORKDIR /site
# EXPOSE 1313

ENTRYPOINT []
