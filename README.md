# DTLS based Multi-Threaded MQTTSN Gateway Application
# Main Features
* Multi-threaded DTLS over UDP connection support for mqttsn clients 
    * DTLS with PSK
    * DTLS with Certificate
* TLS over TCP connection support for MQTTSN Gateway to connect to Broker
    * TLS with PSK (Additional)
    * TLS with Certifate (Already Available)
# Project Description
The current release of MQTTSN Gateway Application @ https://github.com/eclipse/paho.mqtt-sn.embedded-c.git supports UDP based
connection to its mqttsn clients and lags in providing DTLS based security. This new release of DTLS based MQTTSN Application @ supports 
Multi-threaded DTLS based connections to its mqttsn clients which uses either Pre-shared Key or the Certificates to connect to 
this MQTTSN Gateway. In addition to Certificate based TLS over TCP connection support, a Pre-shared Key based TLS over TCP connection 
suppport is also added to ease the mqttsn clients to connect to MQTT broker.










## Author
- TOMOAKI YAMAGUCHI
## Contributor 
- BILAL IMRAN
## oneM2M Project Funding Agency
- National Centre for Cyber Security (NCCS) HEC Gov. Pakistan
## oneM2M Team 
- Internet of Things Research & Innovation Lab (IRIL) KICS UET Lahore, Pakistan
## Team Members
- Bilal Imran (Sr. Research Officer)
- Bilal Afzal (Team Leader)
- Muhammad Ahsan (A. Team Leader)
- Asim Tanwir (Research Officer)
- Muhammad Rehan (Research Officer)
- Dr. Ali Hammad Akbar (Co. Principal Investigator)
- Dr. Ghalib A. Shah (Principal Investigator)

