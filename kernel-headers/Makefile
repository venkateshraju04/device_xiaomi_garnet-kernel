VERSION = 5
PATCHLEVEL = 10

headers_install:
	@mkdir -p $(O)/usr/include
	@rsync -mrq --exclude='Makefile' $(shell pwd)/ $(O)/usr/include/

all:
	@true
