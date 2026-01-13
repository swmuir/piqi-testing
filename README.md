# PIQI Framework Test Data

This repository contains test data for evaluating Patient Information Quality Improvement (PIQI) Framework transformation and evaluation engines. Data were collected to support testing during the [January 2026 HL7 FHIR Connectathon track](https://confluence.hl7.org/spaces/FHIR/pages/403865690/2026+-+01+Patient+Information+Quality+Improvement+PIQI+Framework).

### FHIR Data Bundles
VA used a customized Synthea engine to generate Veteran patient longitudinal health data that represents the U.S. Veteran population. These data are loaded into the VA CDW data warehouse and accessed via the [VA Patient Health FHIR API](https://developer.va.gov/explore/api/patient-health/docs?version=current).

Several FHIR data bundles are available in the [va-fhir-data](./va-fhir-data/) folder. A test-results sub-folder contains scoring results from several PIQI evaluation engines.

### C-CDA Documents

Test patient (no PHI) C-CDA documents were exported from three VA production systems, available in the [va-ccda-data](./va-ccda-data/) folder. A test-results sub-folder contains scoring results from several PIQI evaluation engines.