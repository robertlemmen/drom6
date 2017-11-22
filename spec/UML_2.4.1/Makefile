DOWNLOAD_XMI=Infrastructure.xmi PrimitiveTypes.xmi Superstructure.xmi L0.xmi L1.xmi L2.xmi L3.xmi

all: $(DOWNLOAD_XMI)

Infrastructure.xmi:
	wget -q http://www.omg.org/spec/UML/20110701/Infrastructure.xmi

PrimitiveTypes.xmi:
	wget -q http://www.omg.org/spec/UML/20110701/PrimitiveTypes.xmi
	patch < PrimitiveTypes.diff

Superstructure.xmi:
	wget -q http://www.omg.org/spec/UML/20110701/Superstructure.xmi

L0.xmi:
	wget -q http://www.omg.org/spec/UML/20110701/L0.xmi

L1.xmi:
	wget -q http://www.omg.org/spec/UML/20110701/L1.xmi

L2.xmi:
	wget -q http://www.omg.org/spec/UML/20110701/L2.xmi
	patch < L2.diff

L3.xmi:
	wget -q http://www.omg.org/spec/UML/20110701/L3.xmi

.PHONY: clean all

clean:
	rm -f $(DOWNLOAD_XMI)
