DOWNLOAD_XMI=DC.xmi DI.xmi DG.xmi

all: $(DOWNLOAD_XMI)

DC.xmi:
	wget -q http://www.omg.org/spec/DD/20131001/DC.xmi

DI.xmi:
	wget -q http://www.omg.org/spec/DD/20131001/DI.xmi

DG.xmi:
	wget -q http://www.omg.org/spec/DD/20131001/DG.xmi

.PHONY: clean all

clean:
	rm -f $(DOWNLOAD_XMI)
