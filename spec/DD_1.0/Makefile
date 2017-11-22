DOWNLOAD_XMI=DC.cmof DI.cmof DG.cmof

all: $(DOWNLOAD_XMI)

DC.cmof:
	wget -q http://www.omg.org/spec/DD/20110901/DC.cmof
	patch < DC.diff

DI.cmof:
	wget -q http://www.omg.org/spec/DD/20110901/DI.cmof
	patch < DI.diff

DG.cmof:
	wget -q http://www.omg.org/spec/DD/20110901/DG.cmof
	patch < DG.diff

.PHONY: clean all

clean:
	rm -f $(DOWNLOAD_XMI)
