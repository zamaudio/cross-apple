.PHONY: all install clean

PREFIX ?= /usr
SDKDIR ?= $(PREFIX)/lib/apple/SDKs

all:

clean:

install:
	mkdir -p $(DESTDIR)$(SDKDIR)/Library/Frameworks
	cp -rv MacOSX10.4u.sdk $(DESTDIR)$(SDKDIR)/MacOSX10.4u.sdk
	ln -fvs ../../Library/Frameworks $(DESTDIR)$(SDKDIR)/MacOSX10.4u.sdk/Library/Frameworks

