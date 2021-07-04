
## Not exhaustive and personnal list of "modern" Data Tools and Projects

[![Suggest a Data Tool !](https://img.shields.io/badge/Suggest-a%20Data%20Tool-green)](https://github.com/victorcouste/data-tools/issues/new)

- [Data Architecture articles](#architecture)
- [Data Ingestion / Data Onboarding / ETL / ELT](#ingestion)
- [Reverse ETL](#reverse)
- [Data Collection / Product Analytics / Customer Data](#collection)
- [Transformation / Preparation / Cleaning / Wrangling](#transformation)
- [SQL Tools / Editors](#sqltools)
- [SQL Engines](#sql)
- [BI / Reporting / Data Visualization](#bi)
- [Data Quality / Profiling / Observability](#quality)
- [Data Management / Lineage / Catalog / Governance](#management)
- [DataOps / Data Fabric](#ops)
- [Orchestration / Workflow](#orchestration)
- [Storage / Database](#storage)
- [Data Privacy / Security / Identity](#privacy)
- [Others](#others)

No (file systems) storage or (traditional) databases, and for now, no data science, virtualization, or streaming tools. And no embedded tools proposed by the 3 main public Cloud providers (Google Cloud, Microsoft Azure and AWS).

<a name="architecture"></a>**Data Architecture**
- [Emerging Architectures for Modern Data Infrastructure](https://a16z.com/2020/10/15/the-emerging-architectures-for-modern-data-infrastructure)
- [The Modern Data Stack: Past, Present, and Future](https://blog.getdbt.com/future-of-the-modern-data-stack)
- [Data Mesh Principles and Logical Architecture](https://martinfowler.com/articles/data-mesh-principles.html) and a [Data Warehouse comparison](https://blog.starburstdata.com/data-mesh-the-answer-to-the-data-warehouse-hypocrisy)
- [The Building Blocks of a Modern Data Platform](https://towardsdatascience.com/the-building-blocks-of-a-modern-data-platform-92e46061165)
- [Two steps towards a modern data platform](https://medium.com/bigdatarepublic/two-steps-towards-a-modern-data-platform-37c74e7c104b)
- [What your data team is using: The analytics stack](https://technically.dev/posts/what-your-data-team-is-using)
- [The Top 20 Most Commonly Used Data Engineering Tools](https://www.secoda.co/blog/the-top-20-most-commonly-used-data-engineering-tools)
- [Data Stacks For Fun & Nonprofit](https://towardsdatascience.com/data-stacks-for-fun-nonprofit-part-ii-d375d824abf3)
- [The Future of Business Intelligence is Open Source](https://maximebeauchemin.medium.com/the-future-of-business-intelligence-is-open-source-9b654595773a)
- [What is Data Observability?](https://towardsdatascience.com/what-is-data-observability-40b337971e3e)

<a name="ingestion"></a>**Data Ingestion / Data Onboarding / ETL / ELT**
- [Flatfile](https://flatfile.io) Data Onboarding platform
- [Fivetran](https://fivetran.com) Cloud data integration platform
- [Matillion](https://www.matillion.com) Cloud data integration platform
- [Apache Gobblin](https://gobblin.apache.org) Open Source distributed data integration framework
- [Singer](https://www.singer.io) "Open Source standard for writing scripts that move data"
- [Meltano](https://meltano.com) Open Source ELT for the DataOps
- [Airbyte](https://airbyte.io) Open Source data integration platform
- [Stitch](https://www.stitchdata.com) Simple, extensible Cloud ETL platform (Talend)
- [Hevo](https://hevodata.com) No-code data pipeline as a service
- [Apache Hop](http://hop.incubator.apache.org) Open Source data integration platform project
- [Meroxa](https://meroxa.com) Real-time data ingestion infrastructure
- Talend, StreamSets, Alooma (Google), Xplenty, Striim, Panoply, Stambia, HVR

<a name="reverse"></a>**Reverse ETL**
- [Census](https://www.getcensus.com) Operational analytics platform, move data from data warehouse to apps
- [Hightouch](https://www.hightouch.io) Sync customer data to SaaS business platforms
- [Grouparoo](https://www.grouparoo.com) Open Source framework to move data between database and Cloud apps

<a name="collection"></a>**Data Collection / Product Analytics / Customer Data**
- [Segment](https://segment.com) Customer data platform (CDP) (Twilio)
- [RudderStack](https://rudderstack.com) Customer data pipeline, event tracking
- [Snowplow](https://snowplowanalytics.com) Data collection platform 
- [Freshpaint](https://www.freshpaint.io) Collect, control, and deliver customer data
- [PostHog](https://posthog.com) Open Source Product Analytics platform
- [Amplitude](https://amplitude.com) Product Analytics platform
- [Iteratively](https://iterative.ly) Product Analytics platform « Capture customer data you trust »  
- [Avo](https://www.avo.app) Product Analytics platform
- [Mixpanel](https://mixpanel.com) Product analytics platform
- [Indicative](https://www.indicative.com) Product analytics platform 
- [Heap](https://heap.io) Product analytics platform
- [Supermetrics](https://supermetrics.com) Get marketing data for reporting, analytics and storage

<a name="transformation"></a>**Transformation / Preparation / Cleaning / Wrangling**
- [Trifacta](https://www.trifacta.com) Data Wrangling for Cloud (or Hadoop) platforms and storages
- [dbt](https://www.getdbt.com) Transform with SQL from command line ([Open Source](https://github.com/fishtown-analytics/dbt)) or Cloud
- [Dataform](https://dataform.co) Collaboration on SQL pipelines in Cloud data warehouses (Google)
- [Pano](https://www.pano.dev) Open Source data preparation for Cloud data warehouses
- [Rasgo](https://www.rasgoml.com) Data preparation for Data Scientists
- [Mito](https://www.trymito.io) Jupyter Lab extension to generate panda Python code from a spreadsheet
- [DataPrep](https://dataprep.ai/) Prepare data in Python
- [OpenRefine](https://openrefine.org) "A free, open source, powerful tool for working with messy data"

<a name="sqltools"></a>**SQL Tools / Editors**
- [Count](https://count.co) "The BI notebook built for analysts"
- [PopSQL](https://popsql.com) "Modern SQL editor"
- [DataGrip](https://www.jetbrains.com/datagrip) IDE for SQL (JetBrains)
- [DBeaver](https://dbeaver.io) Free (or Enterprise and Cloud editions) universal database tool
- [sq](https://sq.io) "swiss-army knife for data", SQL in command line for relational data
- [SqlDBM](https://sqldbm.com) Develop Database Models
- [Querybook](https://www.querybook.org) Open Source SQL query and Big Data IDE via a notebook interface
- [Soda SQL](https://github.com/sodadata/soda-sql) Data testing, monitoring, and profiling for SQL-accessible data
- [SQLFluff](https://github.com/sqlfluff/sqlfluff) SQL Linting and Auto-formatting for Humans

<a name="sql"></a>**SQL Engines**
- [Trino](https://trino.io) Open Source high perf and distributed SQL query engine (formerly PrestoSQL)
- [Starburst](https://www.starburst.io) Cloud or On-premises SQL engine (based on [Trino](https://trino.io))
- [AWS Athena](https://aws.amazon.com/athena) Interactive SQL query service for Amazon S3 (based on Presto)
- [DataFusion](https://github.com/apache/arrow-datafusion) Query execution engine using Apache Arrow as its in-memory format

<a name="bi"></a>**BI / Reporting / Data Visualization**
- [Metabase](https://www.metabase.com) Open Source business intelligence tool
- [Apache Superset](https://superset.apache.org) Open Source modern data exploration and visualization platform
- [Apache ECharts](https://echarts.apache.org) Open Source JavaScript Visualization Library
- [Cube.js](https://cube.dev) Open Source Analytical API platform
- [Grafana](https://grafana.com) Open Source analytics & monitoring solution
- [Looker](https://looker.com) BI and Analytics Platform (Google)
- [Redash](https://redash.io) Data visualisation and Dashboarding with SQL (Databricks)
- [Mode](https://mode.com) Collaborative data platform that combines SQL, R, Python, and visual analytics
- [Sigma](https://www.sigmacomputing.com) Cloud analytics solution
- [Hex](https://hex.tech) Collaborative SQL + Python-based notebooks
- [Lux](https://github.com/lux-org/lux) Python library and API for Intelligent Visual Discovery
- [y42](https://www.y42.com) "No-Code Business Intelligence" platform
- [Knowage](https://www.knowage-suite.com) Open Source Business Analytics Suite
- [Rakam](https://rakam.io) Data platform for building analytics interface (dbt integration)
- [Datawrapper](https://www.datawrapper.de) Enrich stories and articles with data visualization
- [D3](https://d3js.org) JavaScript library for visualizing data with HTML, SVG, and CSS
- [Lightdash](https://www.lightdash.com) Open source BI tool fully integrated with dbt projects
- Tableau, PowerBI, Sisense, Qlik, Spotfire, ThoughtSpot, Chartio (Atlassian), Domo, Toucan Toco

<a name="quality"></a>**Data Quality / Profiling / Observability**
- [Monte Carlo](https://www.montecarlodata.com) "Data Reliability Delivered"
- [Datafold](https://www.datafold.com) Data Observability platform
- [Great Expectations](https://greatexpectations.io) Open Source data quality, profiling & validation
- [Bigeye](https://www.bigeye.com) Automatic data quality monitoring
- [Anomalo](https://www.anomalo.com) Validate and document your data warehouse
- [Trackplan](https://trackplan.io) "Schema Management for Behavioural Data Tracking"
- [lightup](https://www.lightup.ai) Cloud data quality indicators provider

<a name="management"></a>**Data Management / Lineage / Catalog / Governance**
- [Datakin](https://datakin.com) DataOps solution, Data Lineage
- [Marquez](https://marquezproject.github.io/marquez) Open Source metadata and data governance project
- [DataHub](https://datahubproject.io) Open Source metadata search & discovery tool
- [Amundsen](https://www.amundsen.io) Open Source data discovery and metadata engine
- [Data Galaxy](https://www.datagalaxy.com/en) Data Governance platform with Data Catalog and Data Lineage
- [Zeenea](https://zeenea.com) Cloud-native Data Catalog
- [Alation](https://www.alation.com) Data Governance and Data Catalog platform
- [Collibra](https://www.collibra.com) Data Governance and Data Catalog platform
- [Secoda](https://www.secoda.co) Data Discovery and Data Catalog
- [MANTA](https://getmanta.com) Data Lineage platform
- [data.world](https://data.world) Cloud-native Data Catalog
- [Stemma](https://www.stemma.ai/) SaaS managed version of Amundsen

<a name="ops"></a>**DataOps / Data Fabric**
- [Altan](https://atlan.com) "the modern data workspace", Data Management & DataOps
- [Nessie](https://projectnessie.org) DataOps for Data Lakes, a "Git-Like Experience for your Data Lake"
- [Nexla](https://www.nexla.com) DataOps platform "to delivery data for Analytics, AI and Operations"
- [Keboola](https://www.keboola.com) DataOps platform
- [Saagie](https://www.saagie.com) DataOps platform
- [DataKitchen](https://datakitchen.io) DataOps platform
- [DAGsHub](https://dagshub.com) GitHub for data
- [Unravel](https://www.unraveldata.com) DataOps platform
- [Upsolver](https://www.upsolver.com) "Compute and pipeline layer between your data lake and the analytics tools"
- [Cinchy](https://www.cinchy.com) "Autonomous Data Fabric" and Data Management platform

<a name="orchestration"></a>**Orchestration / Workflow**
- [Apache Airflow](https://airflow.apache.org) Open Source workflow scheduler platform
- [Dagster](https://dagster.io) Open Source "Data orchestrator for machine learning, analytics, and ETL"
- [Prefect](https://www.prefect.io) Workflow management system and platform for dataflow automation
- [Apache DolphinScheduler](https://dolphinscheduler.apache.org) Distributed and visual workflow scheduler system
- [Luigi](https://github.com/spotify) Python package to build complex pipelines of batch jobs

<a name="storage"></a>**Storage / Database**
- [DuckDB](https://duckdb.org) In-process SQL OLAP database (Sqlite like column oriented)
- [ClickHouse](https://clickhouse.tech/) Open-source OLAP database management system
- [DoltHub](https://www.dolthub.com) "the true Git for data experience in a SQL database"
- [DVC](https://dvc.org) Data Version Control
- [Materialize](https://materialize.com) Event Streaming Database
- [Warp 10](https://www.warp10.io) Advanced Time Series Platform
- Snowflake, BigQuery, Redshift, Apache Cassandra, MongoDB, InfluxDB, QuestDB, Neo4j, SingleStore(MemSQL)

<a name="privacy"></a>**Data Privacy / Security / Identity**
- [Immuta](https://www.immuta.com) "Self-Service Data Access with Automated Privacy Control"
- [Okera](https://www.okera.com) Cloud data security, "Universal Data Authorization"
- [Privacera](https://privacera.com) SaaS Access Governance Solution
- [Apache Ranger](https://ranger.apache.org) Framework to enable, monitor and manage comprehensive data security
- [Baffle](https://baffle.io) Cloud security with a "transparent data security mesh"
- [Privitar](https://www.privitar.com) Enterprise Data Privacy Software
- [ReachFive](https://www.reachfive.com) Identity & Access Management
- [Okta](https://www.okta.com) Trusted platform to secure identities, from customers to workforce

<a name="others"></a>**Others**
- [Opendatasoft](https://www.opendatasoft.com) Data sharing platform 
- [Streamlit](https://streamlit.io) Turns data scripts into shareable data web apps
- [Transform Data](https://transformdata.io) Shared data interface and metrics repository 
- [White Label Data](https://docs.whitelabeldata.com) Platform for building and deploying custom data applications
- [Flat Data](https://octo.github.com/projects/flat-data) Bring working datasets into your GitHub repositories and versioning them

**And finally don't hesitate to:**
- [Star](https://github.com/victorcouste/data-tools/stargazers) this GitHub repository Web page
- Suggest addition interesting and new data tool with a [pull request](https://github.com/victorcouste/data-tools/pulls), an [issue](https://github.com/victorcouste/data-tools/issues/new) or a [message](https://github.com/victorcouste)
- Share [this list](https://victorcouste.github.io/data-tools) in your newtork
- Enjoy and Have Fun !

Victor

