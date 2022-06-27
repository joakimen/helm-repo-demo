RELEASE=nginx

setup:
	helm3 upgrade --install $(RELEASE) .

teardown:
	helm3 delete $(RELEASE)
