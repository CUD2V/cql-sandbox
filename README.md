# CQL Sandbox

This project creates a sandbox with open source tools that can support [Fast Healthcare Interoperability Resources (FHIR)](https://www.hl7.org/fhir/) and [Clinical Quality Language (CQL)](https://cql.hl7.org/) standards for developing and testing Clinical Decision Support (CDS) tools.

The sandbox will be a Linux Virtual Machine (VM) running on the Oracle VM VirtualBox and includes instances of the following tools:

1. **CQL Engines**
    - [DBCG/cql_execution_service](https://github.com/DBCG/cql_execution_service)
    - [AHRQ-CDS/AHRQ-CDS-Connect-CQL-SERVICES](https://github.com/AHRQ-CDS/AHRQ-CDS-Connect-CQL-SERVICES)
    - [cqframework/cql-execution](https://github.com/cqframework/cql-execution)
2. **CQL Translator** 
    - [CQL-to-ELM Translator](https://github.com/cqframework/clinical_quality_language/blob/master/Src/java/cql-to-elm/OVERVIEW.md)
    - [CQL Translation Service](https://github.com/cqframework/cql-translation-service)
3. **FHIR Server** 
    - [Hapi-FHIR](http://hapifhir.io/)
4. **FHIR Profiling**
    - [clinFHIR](http://clinfhir.com/)
5. **CQL Authoring Tool**
    - [AHRQ-CDS-Connect-Authoring-Tool](https://github.com/AHRQ-CDS/AHRQ-CDS-Connect-Authoring-Tool)
6. **CDS Hooks**
    - [CDS Hooks](https://cds-hooks.org/)

> Note: The instructions below are based on the original documentation of these projects. Please visit the links above for the sources and more details about installation. 


## A) Instructions to build the sandbox:
### [Step 1: Create the CQL Sandbox VM](./sandbox_build.md#step-1-create-the-cql-sandbox-vm)
### [Step 2: Install required packages](./sandbox_build.md#step-2-install-required-packages)
### [Step 3: Install FHIR Server (HAPI-FHIR)](./sandbox_build.md#step-3-install-fhir-server-hapi-fhir)
### [Step 4: Install FHIR Profiling Tool (clinFHIR)](./sandbox_build.md#step-4-install-fhir-profiling-tool-clinfhir)
### [Step 5: Install the CQL Engine: cql_execution_service](./sandbox_build.md#step-5-install-the-cql-engine-cql_execution_service)
### [Step 6: Install the CQL Engine: AHRQ-CDS-Connect-CQL-SERVICES](./sandbox_build.md#step-6-install-the-cql-engine-ahrq-cds-connect-cql-services)
### [Step 7: Install the CQL to ELM translator](./sandbox_build.md#step-7-install-the-cql-to-elm-translator)
### [Step 8: Install the CQL Engine: cql-execution](./sandbox_build.md#step-8-install-the-cql-engine-cql-execution)
### [Step 9: Install AHRQ-CDS-Connect-Authoring-Tool](./sandbox_build.md#step-9-install-ahrq-cds-connect-authoring-tool)
### [Step 10: Create a Shell Script to load the services](./sandbox_build.md#step-10-create-a-shell-script-to-load-the-services)
### Step 11: CDS Hooks

## B) Instructions to test the sandbox tools 
