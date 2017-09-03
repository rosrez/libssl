QUIET?=@

LIBS = -lssl -lcrypto

# project.mak relies on TARGETNAMES, so this must be defined before we include project.mak
TARGETNAMES = \
	makereq

-include ../project.mak

$(BLDDIR)/makereq: makereq.o $(LIBS) 
	$(CC) -o $@ $^
