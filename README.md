# bqsub - Documentation

This documentation serves as an overview of bibliometric data provided on Google BigQuery by the SUB Göttingen.


## Status Crossref

### Current Snapshot (cr_instant)

| Snapshot        | File            | Table               | Schema               | Procedure | Last Changed | Coverage  |
|-----------------|-----------------|---------------------|----------------------|-----------|--------------|-----------|
|  2021/12        | all.json.tar.gz | cr_instant.snapshot | schema_crossref.json |           |  02.02.2022  | 2013-2021 |

### Historical Snapshots (cr_history)

| Snapshot        | File            | Table               | Schema               | Procedure | Last Changed | Coverage  |
|-----------------|-----------------|---------------------|----------------------|-----------|--------------|-----------|
|  2018/04        | all.json.tar.gz | cr_history.cr_apr18 | schema_crossref.json |           |  20.02.2022  | 2013-2018 |
|  2019/04        | all.json.tar.gz | cr_history.cr_apr19 | schema_crossref.json |           |  29.10.2021  | 2013-2019 |
|  2020/04        | all.json.tar.gz | cr_history.cr_apr20 | schema_crossref.json |           |  29.10.2021  | 2013-2020 |
|  2021/04        | all.json.tar.gz | cr_history.cr_apr21 | schema_crossref.json |           |  29.10.2021  | 2013-2021 |

## Status Unpaywall

### Current Snapshot (upw_instant)

| Snapshot| File                                          | Table                | Schema               | Procedure | Last Changed | Coverage  |
|---------|-----------------------------------------------|----------------------|----------------------|-----------|--------------|-----------|
| 2021/07 | unpaywall_snapshot_2021-07-02T151134.jsonl.gz | upw_instant.snapshot | bq_schema_jul21.json |           |  30.10.2021  | 2008-2021 |

### Historical Snapshots (upw_history)

| Snapshot| File                                          | Table                       | Schema               | Procedure | Last Changed | Coverage  |
|---------|-----------------------------------------------|-----------------------------|----------------------|-----------|--------------|-----------|
| 2018/03 | unpaywall_snapshot_2019-02-21T031509.jsonl.gz | upw_history.upw_Mar18_08_20 | bq_schema_mar18.json |           |  29.10.2021  | 2008-2018 |
| 2019/02 | unpaywall_snapshot_2019-02-21T031509.jsonl.gz | upw_history.upw_Feb19_08_19 | bq_schema_feb19.json |           |  10.11.2021  | 2008-2019 |
| 2020/02 | unpaywall_snapshot_2020-02-25T115244.jsonl.gz | upw_history.upw_Feb20_08_20 | bq_schema_feb20.json |           |  30.10.2021  | 2008-2020 |
| 2021/02 | unpaywall_snapshot_2021-02-18T160139.jsonl.gz | upw_history.upw_Feb21_08_21 | bq_schema_feb21.json |           |  29.10.2021  | 2008-2021 |

## Status Openalex

| Snapshot   | Directory     | Table                 | Schema                            | Procedure | Last Changed | Coverage  |
|------------|---------------|-----------------------|-----------------------------------|-----------|--------------|-----------|
| 2022-01-20 | authors/      | openalex.authors      | schema_openalex_author.json       |           |  25.01.2022  | All       |
| 2022-01-21 | institutions/ | openalex.institutions | schema_openalex_institutions.json |           |  25.01.2022  | All       |
| 2022-01-21 | venues/       | openalex.venues       | schema_openalex_venue.json        |           |  25.01.2022  | All       |
| 2022-01-23 | works/        | openalex.works        | schema_openalex_work.json         |           |  25.01.2022  | All       |
