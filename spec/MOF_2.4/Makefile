DOWNLOAD_XMI=MOF.xmi

all: $(DOWNLOAD_XMI)

MOF.xmi:
	wget -q http://www.omg.org/spec/XMI/20100901/MOF.xmi

.PHONY: clean all

clean:
	rm -f $(DOWNLOAD_XMI)
