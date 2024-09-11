# bqsub - Documentation

This documentation serves as an overview of bibliometric data provided on Google BigQuery by the SUB Göttingen.


## Status Crossref

### Current Snapshot (cr_instant)

| Snapshot        | File            | Table               | Schema               | Procedure | Last Changed | Coverage  | Number of rows |
|-----------------|-----------------|---------------------|----------------------|-----------|--------------|-----------|--------------------|
|  2024/08        | all.json.tar.gz | [cr_instant.snapshot](https://console.cloud.google.com/bigquery?ws=!1m4!1m3!3m2!1ssubugoe-collaborative!2scr_instant) | schema_crossref.json | [Repo](https://github.com/naustica/crossref_bq) |  11.09.2024  | 2013-2024 | 49.874.183 |

### Historical Snapshots (cr_history)

| Snapshot        | File            | Table               | Schema               | Procedure | Last Changed | Coverage  | Number of rows |
|-----------------|-----------------|---------------------|----------------------|-----------|--------------|-----------|--------------------|
|  2018/04        | all.json.tar.gz | [cr_history.cr_apr18](https://console.cloud.google.com/bigquery?ws=!1m4!1m3!3m2!1ssubugoe-collaborative!2scr_history) | schema_crossref.json | [Repo](https://github.com/naustica/crossref_bq) |  20.02.2022  | 2013-2018 | 16.766.035 |
|  2019/04        | all.json.tar.gz | [cr_history.cr_apr19](https://console.cloud.google.com/bigquery?ws=!1m4!1m3!3m2!1ssubugoe-collaborative!2scr_history) | schema_crossref.json | [Repo](https://github.com/naustica/crossref_bq) |  29.10.2021  | 2013-2019 | 20.715.644 |
|  2020/04        | all.json.tar.gz | [cr_history.cr_apr20](https://console.cloud.google.com/bigquery?ws=!1m4!1m3!3m2!1ssubugoe-collaborative!2scr_history) | schema_crossref.json | [Repo](https://github.com/naustica/crossref_bq) |  29.10.2021  | 2013-2020 | 25.334.525 |
|  2021/04        | all.json.tar.gz | [cr_history.cr_apr21](https://console.cloud.google.com/bigquery?ws=!1m4!1m3!3m2!1ssubugoe-collaborative!2scr_history) | schema_crossref.json | [Repo](https://github.com/naustica/crossref_bq) |  29.10.2021  | 2013-2021 | 30.579.119 |
|  2022/04        | all.json.tar.gz | [cr_history.cr_apr22](https://console.cloud.google.com/bigquery?ws=!1m4!1m3!3m2!1ssubugoe-collaborative!2scr_history) | schema_crossref.json | [Repo](https://github.com/naustica/crossref_bq) |  14.05.2022  | 2013-2022 | 35.939.195 |
|  2023/04        | all.json.tar.gz | [cr_history.cr_apr23](https://console.cloud.google.com/bigquery?ws=!1m4!1m3!3m2!1ssubugoe-collaborative!2scr_history) | schema_crossref.json | [Repo](https://github.com/naustica/crossref_bq) |  07.05.2023  | 2013-2023 | 41.767.461 |
|  2024/04        | all.json.tar.gz | [cr_history.cr_apr24](https://console.cloud.google.com/bigquery?ws=!1m4!1m3!3m2!1ssubugoe-collaborative!2scr_history) | schema_crossref.json | [Repo](https://github.com/naustica/crossref_bq) |  07.05.2024  | 2013-2024 | 47.709.184 |

## Status Unpaywall

### Current Snapshot (upw_instant)

| Snapshot| File                                          | Table                | Schema               | Procedure | Last Changed | Coverage  | Number of rows |
|---------|-----------------------------------------------|----------------------|----------------------|-----------|--------------|-----------|-----------------|
| 2022/03 | unpaywall_snapshot_2022-03-09T083001.jsonl.gz | [upw_instant.snapshot](https://console.cloud.google.com/bigquery?ws=!1m4!1m3!3m2!1ssubugoe-collaborative!2supw_instant) | bq_schema_mar22.json | [Repo](https://github.com/naustica/unpaywall_bq) |  14.03.2022 | 2008-2022 | 67.424.819 |

### Historical Snapshots (upw_history)

| Snapshot| File                                          | Table                       | Schema               | Procedure | Last Changed | Coverage  | Number of rows |
|---------|-----------------------------------------------|-----------------------------|----------------------|-----------|--------------|-----------|-----------------|
| 2018/03 | unpaywall_snapshot_2018-03-29T113154.jsonl.gz | [upw_history.upw_Mar18_08_20](https://console.cloud.google.com/bigquery?ws=!1m4!1m3!3m2!1ssubugoe-collaborative!2supw_history) | bq_schema_mar18.json | [Repo](https://github.com/naustica/unpaywall_bq) |  29.10.2021  | 2008-2018 | 36.557.043 |
| 2019/02 | unpaywall_snapshot_2019-02-21T031509.jsonl.gz | [upw_history.upw_Feb19_08_19](https://console.cloud.google.com/bigquery?ws=!1m4!1m3!3m2!1ssubugoe-collaborative!2supw_history) | bq_schema_feb19.json | [Repo](https://github.com/naustica/unpaywall_bq) |  10.11.2021  | 2008-2019 | 42.143.979 |
| 2020/02 | unpaywall_snapshot_2020-02-25T115244.jsonl.gz | [upw_history.upw_Feb20_08_20](https://console.cloud.google.com/bigquery?ws=!1m4!1m3!3m2!1ssubugoe-collaborative!2supw_history) | bq_schema_feb20.json | [Repo](https://github.com/naustica/unpaywall_bq) |  30.10.2021  | 2008-2020 | 49.717.710 |
| 2021/02 | unpaywall_snapshot_2021-02-18T160139.jsonl.gz | [upw_history.upw_Feb21_08_21](https://console.cloud.google.com/bigquery?ws=!1m4!1m3!3m2!1ssubugoe-collaborative!2supw_history) | bq_schema_feb21.json | [Repo](https://github.com/naustica/unpaywall_bq) |  29.10.2021  | 2008-2021 | 58.437.927 |
| 2022/03 | unpaywall_snapshot_2022-03-09T083001.jsonl.gz | [upw_history.upw_Mar22_08_22](https://console.cloud.google.com/bigquery?ws=!1m4!1m3!3m2!1ssubugoe-collaborative!2supw_history) | bq_schema_mar22.json | [Repo](https://github.com/naustica/unpaywall_bq) |  14.03.2022 | 2008-2022 | 67.424.819 |

## Status Openalex

| Snapshot   | Directory     | Table                 | Schema                            | Procedure | Last Changed | Coverage  | Number of rows |
|------------|---------------|-----------------------|-----------------------------------|-----------|--------------|-----------|----------------------|
| 2024-08-29 | authors/      | [openalex.authors](https://console.cloud.google.com/bigquery?ws=!1m4!1m3!3m2!1ssubugoe-collaborative!2sopenalex)      | schema_openalex_author.json       | [Repo](https://github.com/naustica/openalex) |  04.09.2024  | All | 95.724.450 |
| 2024-08-30 | funders/      | [openalex.funders](https://console.cloud.google.com/bigquery?ws=!1m4!1m3!3m2!1ssubugoe-collaborative!2sopenalex)      | schema_openalex_funders.json      | [Repo](https://github.com/naustica/openalex) |  04.09.2024  | All | 32.437 |
| 2024-08-30 | institutions/ | [openalex.institutions](https://console.cloud.google.com/bigquery?ws=!1m4!1m3!3m2!1ssubugoe-collaborative!2sopenalex) | schema_openalex_institutions.json | [Repo](https://github.com/naustica/openalex) |  04.09.2024  | All | 109.259 |
| 2024-08-30 | publishers/   | [openalex.publishers](https://console.cloud.google.com/bigquery?ws=!1m4!1m3!3m2!1ssubugoe-collaborative!2sopenalex)   | schema_openalex_publishers.json   | [Repo](https://github.com/naustica/openalex) |  04.09.2024  | All | 10.250 |
| 2024-08-30 | sources/      | [openalex.sources](https://console.cloud.google.com/bigquery?ws=!1m4!1m3!3m2!1ssubugoe-collaborative!2sopenalex)      | schema_openalex_sources.json      | [Repo](https://github.com/naustica/openalex) |  04.09.2024  | All | 254.515 |
| 2024-08-26 | topics/       | [openalex.topics](https://console.cloud.google.com/bigquery?ws=!1m4!1m3!3m2!1ssubugoe-collaborative!2sopenalex)       | schema_openalex_topics.json       | [Repo](https://github.com/naustica/openalex) |  04.09.2024  | All | 4.516 |
| 2024-08-29 | works/        | [openalex.works](https://console.cloud.google.com/bigquery?ws=!1m4!1m3!3m2!1ssubugoe-collaborative!2sopenalex)        | schema_openalex_work.json         | [Repo](https://github.com/naustica/openalex) |  04.09.2024  | All | 258.602.038 |
