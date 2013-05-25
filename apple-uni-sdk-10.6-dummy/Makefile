.PHONY: all install clean

PREFIX ?= /usr
SDKDIR ?= $(PREFIX)/lib/apple/SDKs

all:

clean:

install:
	mkdir -p $(DESTDIR)$(SDKDIR)/Library/Frameworks
	cp -rv MacOSX10.6.sdk $(DESTDIR)$(SDKDIR)/MacOSX10.6.sdk
	ln -fvs ../../Library/Frameworks $(DESTDIR)$(SDKDIR)/MacOSX10.6.sdk/Library/Frameworks

