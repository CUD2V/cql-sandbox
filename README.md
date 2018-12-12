# CQL Sandbox

This project creates a sandbox with open source tools that can support [Fast Healthcare Interoperability Resources (FHIR)](https://www.hl7.org/fhir/) and [Clinical Quality Language (CQL)](https://cql.hl7.org/) standards for developing and testing Clinical Decision Support (CDS) tools.

The sandbox will be a Linux Virtual Machine (VM) running on the Oracle VM VirtualBox and includes instances of the following tools:

1. **CQL Engines**
    - [DBCG/cql_execution_service](https://github.com/DBCG/cql_execution_service)
    - [AHRQ-CDS/AHRQ-CDS-Connect-CQL-SERVICES](https://github.com/AHRQ-CDS/AHRQ-CDS-Connect-CQL-SERVICES)
    - [cqframework/cql-execution](https://github.com/cqframework/cql-execution)
2. **FHIR Server** 
    - [Hapi-FHIR](http://hapifhir.io/)
3. **FHIR Profiling**
    - [clinFHIR](http://clinfhir.com/)
4. **CQL Authoring Tool**
    - [AHRQ-CDS-Connect-Authoring-Tool](https://github.com/AHRQ-CDS/AHRQ-CDS-Connect-Authoring-Tool)


> Note: The instructions below are based on the original documentation of these projects. Please visit the links above for the sources and more details about installation. 



## Instructions:
### - [To build the CQL sandbox](./sandbox_build.md)
### - To test the sandbox tools
