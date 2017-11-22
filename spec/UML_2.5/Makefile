DOWNLOAD_XMI=PrimitiveTypes.xmi StandardProfile.xmi UML.xmi UMLDI.xmi

all: $(DOWNLOAD_XMI)

PrimitiveTypes.xmi:
	wget -q http://www.omg.org/spec/UML/20131001/PrimitiveTypes.xmi

StandardProfile.xmi:
	wget -q http://www.omg.org/spec/UML/20131001/StandardProfile.xmi

UML.xmi:
	wget -q http://www.omg.org/spec/UML/20131001/UML.xmi

UMLDI.xmi:
	wget -q http://www.omg.org/spec/UML/20131001/UMLDI.xmi

.PHONY: clean all

clean:
	rm -f $(DOWNLOAD_XMI)
