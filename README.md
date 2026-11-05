# Data Vault Tool Atlas

Data Vault software ranges from integrated automation platforms to focused libraries, modelers, and supporting infrastructure. This directory puts the products in one alphabetical matrix so readers can compare their actual contribution without moving between separate category lists.

**Research snapshot: 5 November 2026.** Links on product names point to the primary evidence used for each entry. Product formats and comparison language are editorial classifications of documented offerings, not benchmark results.

## Read the matrix by output

Three outputs often appear together but serve different purposes:

- **Model definitions:** business concepts, keys, grain, relationships, and mappings.
- **Implementation artifacts:** schemas, SQL, model files, pipelines, and deployment assets.
- **Operational evidence:** execution state, tests, lineage, and quality observations.

An integrated platform may contribute to all three. A generator may produce implementation artifacts while another tool runs them. A general-purpose modeler or scheduler is a supporting component rather than a complete Data Vault implementation.

## Alphabetical software directory

The directory contains 58 current/documented tool entries, including supporting technologies. Inclusion does not establish active maintenance or a support guarantee. Dependency notes identify the boundary most relevant to comparison; they are not complete compatibility matrices.

| Tool / primary evidence | Product format | Main output or contribution | Dependency / scope note |
| --- | --- | --- | --- |
| [Agile Data Engine](https://www.agiledataengine.com/data-vault-automation) | Automation platform | Vault models, SQL transformations, deployment artifacts | Cloud targets; check pattern coverage per target |
| [Agnostic Data Labs](https://agnosticdatalabs.com/) | Configurable generator | Code and documentation from design metadata | Public preview; template-dependent outputs |
| [Airbyte](https://airbyte.com/) | Supporting ingestion | Replicated source data for staging | Connector-specific history and deletes |
| [AnalyticsCreator](https://www.analyticscreator.com/solutions) | Model-driven application | Warehouse and downstream implementation assets | Microsoft-oriented generation paths |
| [Apache Airflow](https://airflow.apache.org/docs/) | Supporting orchestration | Scheduled workflows and dependency execution | Loading logic supplied by the implementation |
| [Astera Data Warehouse Builder](https://www.astera.com/products/data-warehouse-builder) | Warehouse automation | Initial vault models and integration workflows | Validate proposed keys and product configuration |
| [beVault](https://www.bevault.io/features/data-vault-automation) | Automation platform | Business-model-derived structures and loads | Confirm deployment and runtime responsibilities |
| [biGENIUS-X](https://www.bigenius-x.com/data-modeling) | Generator platform | Data Vault and other warehouse implementations | Generator/target combination determines scope |
| [BimlFlex](https://docs.varigence.com/bimlflex/delivering-solutions/delivering-data-vault/) | Generation framework | Vault structures, loading patterns, and marts | Configurable templates and integration technologies |
| [Coalesce + Data Vault by Scalefree](https://docs.coalesce.io/docs/marketplace/package/coalesce_snowflake_data-vault-by-scalefree) | Platform plus package | Vault-specific node types and transformations | Separate Snowflake and Databricks packages |
| [Collibra](https://www.collibra.com/) | Supporting governance | Definitions, stewardship, and metadata context | Connect lineage across the implemented stack |
| [crossnative Data Vault Generator](https://www.crossnative.com/data-vault-generator) | Warehouse generator | SQL, documentation, lineage, and process control | Confirm target, modules, and deployment option |
| [Dagster](https://dagster.io/docs) | Supporting orchestration | Asset dependencies, schedules, and checks | Vault loading semantics are external |
| [data-vault-MS-Fabric](https://github.com/futureanalytics-io/data-vault-MS-Fabric) | Community implementation | SparkSQL-driven vault objects and views | Fabric feature and project-maturity assessment needed |
| [Datagaps ETL Validator](https://www.datagaps.com/data-validation-etl-testing-tools/) | Supporting validation | Source-to-target and ETL/ELT test results | Define expected history and reconciliation rules |
| [DataHub](https://datahub.com/) | Supporting metadata | Discovery, lineage, and governance context | Ingestion/connectors determine visibility |
| [Datavault Builder](https://datavault-builder.com/) | Automation platform | Integrated models, loads, releases, and lineage | Hosted/self-managed options and multiple targets |
| [datavault4dbt](https://github.com/ScalefreeCOM/datavault4dbt) | dbt loading package | SQL generated from vault macro calls | dbt project plus compatible target adapter |
| [datavault4sqlglot](https://github.com/ScalefreeCOM/datavault4sqlglot) | Python library | Dialect-oriented Data Vault loading SQL | Generation component for custom tooling |
| [datavault4sqlmesh](https://github.com/ScalefreeCOM/datavault4sqlmesh) | SQLMesh extension | Declarative vault model factories | SQLMesh and datavault4sqlglot dependencies |
| [dbt](https://www.getdbt.com/product/data-vault) | Supporting execution | Compiled transformations, tests, and documentation | Add vault-specific macros or custom logic |
| [dbt-ui](https://github.com/data-diving/dbt-ui/) | Development interface | Project editing and visual MetaDV mapping | Git-based dbt projects; metadv integration |
| [Debezium](https://debezium.io/documentation/) | Supporting CDC | Database change events | Requires ingestion and downstream loading design |
| [diepvries](https://github.com/PicnicSupermarket/diepvries) | Python library | Data Vault SQL statements | Snowflake-oriented implementation |
| [dq-vault](https://github.com/infinitelambda/dq-vault) | Quality utility | Observations about the Data Vault layer | Assess package compatibility and maintenance |
| [DSharp Studio](https://dsharp.fi/product/) | Model-driven application | Implementation derived from conceptual models | Product generations include different SQL/dbt paths |
| [DVPD](https://datavault-pipelinedescription.org/) | Metadata specification and tooling | Pipeline descriptions, validation, and example generators | Foundation for a custom automation toolchain |
| [Ellie](https://www.ellie.ai/data-warehousing) | Business modeling application | Conceptual models, definitions, and integration metadata | Documented connections to warehouse automation |
| [ER/Studio Data Architect](https://docwiki.embarcadero.com/ERStudioDA/206/en/Using_Data_Vault_Tools) | Model engineering | Hub, link, and satellite model assets | Data Vault workflow macros documented from 20.6 |
| [erwin Data Modeler](https://www.snowflake.com/en/blog/data-vault-automation-with-erwin-and-snowflake-building-and-automating-a-scalable-data-warehouse-based-on-data-vault-2-0/) | Enterprise modeler | Business, logical, and physical definitions | One component of the broader erwin solution |
| [erwin Data Vault Automation](https://www.quest.com/documents/erwin-data-vault-automation-datasheet-147776.pdf) | Automation solution | Mappings, generated vault code, lineage, and tests | Connectors, customization, and services affect scope |
| [Fivetran](https://www.fivetran.com/) | Supporting ingestion | Replicated source records and changes | Connector and source configuration determine behavior |
| [Flow.BI](https://flow.bi/solutions/flow-bi-for-data-vault/) | Model discovery | Logical vault definitions from source analysis | Downstream automation implements the physical vault |
| [Flyway](https://www.red-gate.com/products/flyway/) | Supporting schema delivery | Versioned database migrations | Coordinate with generated schema deployments |
| [Great Expectations](https://docs.greatexpectations.io/docs/home/) | Supporting quality | Configurable data validation results | Implement vault-specific assertions |
| [Hackolade Studio](https://hackolade.com/help/DataModelingTechniques.html) | Modeling application | Schemas with Data Vault component classification | Loading behavior requires another implementation |
| [IRI Voracity](https://www.iri.com/support/data-education-center/what-is-data-vault-20) | Migration/test accelerator | Vault DDL, migrated data, or generated test data | Wizard scope differs from full platform automation |
| [IRiS](https://iris-automation.ai/) | Code automation | Native integration code from agreed models | Check generation path for the selected lakehouse |
| [Liquibase](https://docs.liquibase.com/) | Supporting schema delivery | Tracked and automated database changes | Edition and database support vary |
| [Matillion ETL + Data Vault 2.0 Shared Jobs](https://exchange.matillion.com/metl/shared-job/data-vault-2-0/) | Host-platform extension | Reusable jobs for vault structures | Documented Matillion ETL/Snowflake prerequisites |
| [metadv](https://github.com/data-diving/metadv) | Metadata-to-model generator | SQL models from declarative YAML | Selected templates and target package are dependencies |
| [Microsoft Purview](https://learn.microsoft.com/en-us/purview/) | Supporting governance | Catalog, data-map, and governance context | Verify coverage of the actual data estate |
| [OpenLineage](https://openlineage.io/) | Supporting lineage framework | Job, run, and dataset lineage events | Requires instrumentation and a consuming backend |
| [OpenMetadata](https://open-metadata.org/) | Supporting metadata | Discovery, context, governance, and quality metadata | Connector/configuration-dependent coverage |
| [Optimal Data Engine](https://github.com/OptimalBI/optimal-data-engine-mssql) | Vault loading framework | Metadata-driven loads and operational scheduling | Linked implementation targets SQL Server |
| [Prefect](https://www.prefect.io/docs/v3/get-started) | Supporting orchestration | Scheduled Python workflows and execution state | Does not define vault patterns |
| [Qlik Compose for Data Warehouses](https://www.qlik.com/us/products/qlik-compose-data-warehouses) | Warehouse automation | Physical warehouse using Data Vault components | Check conventions against required methodology |
| [QUIPU](https://quipu.nl/platform/) | Pattern-based generator | Models, mappings, and loading code | Reviewed v4.4 materials refer complex vault work to v3.4 |
| [SAP PowerDesigner](https://help.sap.com/docs/SAP_POWERDESIGNER) | General-purpose modeler | Conceptual/physical models and generated artifacts | Vault extensions and lifecycle need assessment |
| [Soda](https://docs.soda.io/) | Supporting quality | Data checks and monitoring results | Configure integrity and history expectations |
| [SqlDBM](https://www.sqldbm.com/data-modeling/) | Collaborative modeler | Versioned schemas, metadata, and engineering output | Modeling support does not imply vault-load generation |
| [SQLMesh](https://sqlmesh.readthedocs.io/en/stable/) | Supporting execution | Planned and tested SQL/Python transformations | Add a vault extension or implement loading logic |
| [TimeXtender](https://www.timextender.com/) | Supporting integration platform | Integration, enrichment, quality, and orchestration | Establish vault pattern implementation explicitly |
| [TurboVault Engine](https://github.com/ScalefreeCOM/turbovault-engine) | dbt project generator | Validated metadata converted into structured projects | Uses datavault4dbt; distinct from TurboVault4dbt |
| [TurboVault4dbt](https://github.com/ScalefreeCOM/turbovault4dbt) | dbt model generator | Models generated from spreadsheet/database metadata | Existing dbt project and compatible macros |
| [VaultSpeed](https://www.vaultspeed.com/technologies) | Automation platform | Implementation code generated from shared metadata | Includes multiple generator and dbt paths |
| [Visual Paradigm](https://s.visual-paradigm.com/features/database-engineering-tools/) | General-purpose modeler | UML/ER models, DDL, and documentation | A design component within a broader delivery stack |
| [WhereScape](https://www.wherescape.com/solutions/project-types/data-vault-automation/) | Automation product family | Design, schema/load generation, and delivery artifacts | 3D, RED, and Data Vault Express scope differs |

## Capability lenses for comparing entries

Use the same matrix through different lenses rather than treating every row as an alternative to every other row.

| Lens | What to compare |
| --- | --- |
| Business design | Key scope, relationship grain, mapping review, and support for enterprise definitions |
| Vault behavior | Required satellite/link patterns, incremental processing, late arrivals, and delete handling |
| Change management | Schema evolution, model versioning, template changes, and historical migrations |
| Production operation | Dependencies, retries, alerts, repeatability, observability, and support ownership |
| Portability | Metadata export, editable templates, executable generated code, and runtime dependencies |

These are evaluation dimensions, not product scores. A “Data Vault” label does not establish identical semantics, generated code, or operational behavior across tools.

## Common product relationships

| Relationship | How to read it |
| --- | --- |
| datavault4dbt + a compatible dbt project | A loading-pattern package inside a transformation workflow |
| TurboVault Engine → datavault4dbt model calls | A generator and its generated package dependencies |
| datavault4sqlmesh → datavault4sqlglot | Model factories built on SQL-generation patterns |
| Coalesce + Data Vault by Scalefree | A host platform extended with vault-specific node definitions |
| WhereScape 3D / RED / Data Vault Express | A product family whose components should be specified in a proposal |

The arrows describe documented component relationships, not automatic compatibility between arbitrary releases.

## Execution targets are a separate market

Snowflake, Databricks, BigQuery, Redshift, Fabric, Synapse, SQL Server, PostgreSQL, Oracle, Exasol, and Trino appear in published target lists across this ecosystem. They are not additional automation tools in the directory. Verify the chosen platform, adapter, version, and object pattern as a combination. Fabric Warehouse and Fabric Lakehouse, for example, should be assessed as distinct targets.

## Historical reference corner

[TEAM](https://github.com/data-solution-automation-engine/TEAM) is archived and explicitly deprecated. [VDW/VEDW](https://roelantvos.com/blog/new-releases-for-open-source-data-warehouse-automation/) documents an earlier code-generation ecosystem. The [PDI Data Vault framework](https://sourceforge.net/projects/pdidatavaultfw/files/) has reviewed release listings from 2014–2015, with present-day compatibility and maintenance unconfirmed. These references help interpret existing implementations without implying suitability for a new deployment.

**Coverage:** Publicly documented products and selected supporting tools. No universal ranking, certification, or completeness claim is made. Confirm exact capabilities, licenses, lifecycle, and commercial packaging for the proposed release. The [Willibald DWA Challenge](https://dwa-compare.info/en/start-2/) supplies shared evaluation scenarios for comparing concrete implementations.
