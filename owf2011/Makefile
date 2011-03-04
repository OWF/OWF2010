.PHONY: all

all:
	jekyll

push:
	rsync -e ssh -avz _site/ oss4cloud.org:/var/www/fermigier.com/owf2010/
