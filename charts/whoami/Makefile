RELEASE=whoami

setup:
	helm3 upgrade --install $(RELEASE) .

teardown:
	helm3 delete $(RELEASE)

lint:
	helm3 lint .
