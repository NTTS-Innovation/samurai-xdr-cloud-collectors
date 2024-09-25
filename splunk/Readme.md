# NTT Samurai Splunk Hec Cloud Native Collector


## Requirements:
Cloud Native Collector ID and Passkey from the Samurai MDR Portal


## Configuration:
    
### EndPoint
* https://api.westeurope.samurai.security.ntt/integrations/hec/{Collector ID}/services/collector/event

### Authentication

* Splunk Token is the Collector Passkey
* Manual HTTP Headers 

    {
        "Authorization": "Bearer [Collector Passkey]"
    }


