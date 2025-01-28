# Collaborative Scoping: Self-Supervised Linkability Assessment for Schema Matching

_Method Description_: Collaborative scoping is a robust approach to locally assess linkable tables and attributes toward matching multiple heterogeneous schemas with different volumes, designs, and domains. The overall framework entails the three phases: (I) Local Signatures, (II) Local Self-Supervised Model, and (III) Local Linkability Assessment with Distributed Models. 

- TBD figure of framework

## Datasets
The datasets contain the two differently challenging multi-source schema matching scenarios OC3 and OC3-FO. Both datasets store the tables and attributes of all schemas as records with their extracted metadata and annotated linkable (true) and unlinkable (false) labels.

**OC3** contains three schemas on Orders-Customers from the three database vendors:
- Oracle: https://github.com/oracle-samples/db-sample-schemas
- MySQL: https://www.mysqltutorial.org/mysql-sample-database.aspx
- SAP HANA: https://github.com/saphanaacademy/HXE/tree/master/STS

**OC3-FO** extends OC3 with a domain-unrelated schema on Formula-One, sourced from
- jolpica-f1 project: https://github.com/jolpica/jolpica-f1

See `./data` for more details.

## Requirements

- TBD libraries

## Quick Start

- TBD executable python file
