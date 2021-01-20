# IRIL-KICS_IoT_Device_Identification_Application_Layer_Dataset
Application layer features are extracted from network traffic of 22 IoT and 5 non-IoT devices. Previously publicly available network traces (.pcap files) are parsed and then features are extracted by our Application Layer Feature Extractor tool. Total 6 optimized features are extracted consists of application protocols such as HTTP, DNS, ICMP etc. 


| Column       | Name             | Description                                            |
| :---         |     :---:        |          ---:                                          |
| 13           | totalAppPktCount | Total number of packets in application layer           |
| 14           | totalAppFrameLen | Sum of packet size of all packets in application layer |
| 14           | minAppPktLen     | Minimum packet size in all application layer packets   |
| 14           | maxAppPktLen     | Maximum packet size in all application layer packets   |
| 14           | AppPrtclNum	    | Application layer protocol number                      |
| 14           | Label            | Device name                                            |
