LEVEL = ../../../..

PROG     = NodeSplitting-flt
LDFLAGS  = -lm
CFLAGS += -std=gnu99
RUN_OPTIONS = 10000 5

ifeq ($(ARCH),XCore)
# XCore takes ~1 hour.
RUNTIMELIMIT:=7200
endif

include $(LEVEL)/MultiSource/Makefile.multisrc

