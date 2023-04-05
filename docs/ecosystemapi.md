## Compliance Ecosystem APIs

This section will define the APIs used by the digital compliance ecosystem. In total four custom APIs will be developed:

1. Compliance Document Service API
2. Result Service API
3. Rule Engine API
4. Rule Engine Interface API

Additionally, four pre-existing APIs will be utilised based on our re-use of existing software components:

1. OAUTH2 - API [here](https://oauth.net/2){.new-tab}
2. OpenIDConnect - API [here](https://openid.net/connect/){.new-tab}
3. Netflix Eureka Service Discovery API - API [here](https://github.com/Netflix/eureka/wiki/Eureka-REST-operations){.new-tab}

The APIs relationships to the ecosystem components are shown below.

![APIS](API.png)

This remainder of this page specifies the CUSTOM APIs for the Digital Compliance Ecosystem. For specific endpoint information related to the pilot deployment please see [here](pilot.md)

###Compliance Document Server

1. [API Specification](https://d-com-network.github.io/DCOMDocumentation/resources/compliancedocumentserver){.new-tab}

###Results Service

1. [API Specification](https://d-com-network.github.io/DCOMDocumentation/resources/resultserver){.new-tab}

### Rule Engine

1. The Rule Engine [API Specification](https://d-com-network.github.io/DCOMDocumentation/resources/ruleengine){.new-tab}
2. The Rule Engine Interface - which should be implemented by all services that the rule engine can connect to - [API Specification](https://d-com-network.github.io/DCOMDocumentation/resources/ruleengineinterface){.new-tab}
