ChirpStack Setup with Node-RED and Gateway

Introduction

This document provides an overview of the setup process for ChirpStack with Node-RED integration and the gateway configuration used in the project.


Prerequisites

    ChirpStack installed
    Node-RED installed
    Gateway hardware  (MikroTik L9 kit)

ChirpStack Setup

    Install ChirpStack V4 to OS. Follow detailed and updated documentation on Chripstack Forums.  

    Configure chirpstack your region. We used US915_2.
    
    Detailed and up-to-date steps on chirpstack forum.

    Start the ChirpStack services and connect to localhost:8080

        
Node-RED Integration

    Install Node-RED by following the official Node-RED installation guide.

    Use MQTT node to subscribe to device uplink topic.

    Process data and send to cloud hosted website.

Gateway Setup

    Configure gateway's LoRa packet forwarder to chirpstack server using ssh or by connecting to its 2.4 GHz WLAN interface.
    Configure the Antenna gain to your specific specs. 

    
Testing and Verification

    Confirm the status of gateway and data flows in the ChirpStack Application Server.

Conclusion

The integration of ChirpStack with Node-RED is now complete and ready for use with LoRa capable devices. 
