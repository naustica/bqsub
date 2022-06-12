# bqsub - Documentation

This documentation serves as an overview of bibliometric data provided on Google BigQuery by the SUB Göttingen.


## Status Crossref

### Current Snapshot (cr_instant)

| Snapshot        | File            | Table               | Schema               | Procedure | Last Changed | Coverage  | Number of rows |
|-----------------|-----------------|---------------------|----------------------|-----------|--------------|-----------|--------------------|
|  2022/05        | all.json.tar.gz | cr_instant.snapshot | schema_crossref.json | [Repo](https://github.com/naustica/crossref_bq) |  12.06.2022  | 2013-2022 | 36.394.515 |

### Historical Snapshots (cr_history)

| Snapshot        | File            | Table               | Schema               | Procedure | Last Changed | Coverage  | Number of rows |
|-----------------|-----------------|---------------------|----------------------|-----------|--------------|-----------|--------------------|
|  2018/04        | all.json.tar.gz | cr_history.cr_apr18 | schema_crossref.json | [Repo](https://github.com/naustica/crossref_bq) |  20.02.2022  | 2013-2018 | 16.766.035 |
|  2019/04        | all.json.tar.gz | cr_history.cr_apr19 | schema_crossref.json | [Repo](https://github.com/naustica/crossref_bq) |  29.10.2021  | 2013-2019 | 20.715.644 |
|  2020/04        | all.json.tar.gz | cr_history.cr_apr20 | schema_crossref.json | [Repo](https://github.com/naustica/crossref_bq) |  29.10.2021  | 2013-2020 | 25.334.525 |
|  2021/04        | all.json.tar.gz | cr_history.cr_apr21 | schema_crossref.json | [Repo](https://github.com/naustica/crossref_bq) |  29.10.2021  | 2013-2021 | 30.579.119 |
|  2022/04        | all.json.tar.gz | cr_history.cr_apr22 | schema_crossref.json | [Repo](https://github.com/naustica/crossref_bq) |  14.05.2022  | 2013-2022 | 35.939.195 |

## Status Unpaywall

### Current Snapshot (upw_instant)

| Snapshot| File                                          | Table                | Schema               | Procedure | Last Changed | Coverage  | Number of rows |
|---------|-----------------------------------------------|----------------------|----------------------|-----------|--------------|-----------|-----------------|
| 2022/03 | unpaywall_snapshot_2022-03-09T083001.jsonl.gz | upw_instant.snapshot | bq_schema_mar22.json | [Repo](https://github.com/naustica/unpaywall_bq) |  14.03.2022 | 2008-2022 | 67.424.819 |

### Historical Snapshots (upw_history)

| Snapshot| File                                          | Table                       | Schema               | Procedure | Last Changed | Coverage  | Number of rows |
|---------|-----------------------------------------------|-----------------------------|----------------------|-----------|--------------|-----------|-----------------|
| 2018/03 | unpaywall_snapshot_2018-03-29T113154.jsonl.gz | upw_history.upw_Mar18_08_20 | bq_schema_mar18.json | [Repo](https://github.com/naustica/unpaywall_bq) |  29.10.2021  | 2008-2018 | 36.557.043 |
| 2019/02 | unpaywall_snapshot_2019-02-21T031509.jsonl.gz | upw_history.upw_Feb19_08_19 | bq_schema_feb19.json | [Repo](https://github.com/naustica/unpaywall_bq) |  10.11.2021  | 2008-2019 | 42.143.979 |
| 2020/02 | unpaywall_snapshot_2020-02-25T115244.jsonl.gz | upw_history.upw_Feb20_08_20 | bq_schema_feb20.json | [Repo](https://github.com/naustica/unpaywall_bq) |  30.10.2021  | 2008-2020 | 49.717.710 |
| 2021/02 | unpaywall_snapshot_2021-02-18T160139.jsonl.gz | upw_history.upw_Feb21_08_21 | bq_schema_feb21.json | [Repo](https://github.com/naustica/unpaywall_bq) |  29.10.2021  | 2008-2021 | 58.437.927 |
| 2022/03 | unpaywall_snapshot_2022-03-09T083001.jsonl.gz | upw_history.upw_Mar22_08_22 | bq_schema_mar22.json | [Repo](https://github.com/naustica/unpaywall_bq) |  14.03.2022 | 2008-2022 | 67.424.819 |

## Status Openalex

| Snapshot   | Directory     | Table                 | Schema                            | Procedure | Last Changed | Coverage  | Number of rows |
|------------|---------------|-----------------------|-----------------------------------|-----------|--------------|-----------|----------------------|
| 2022-05-11 | authors/      | openalex.authors      | schema_openalex_author.json       | [Repo](https://github.com/naustica/openalex) |  23.05.2022  | All       | 220.870.815 |
| 2022-04-14 | institutions/ | openalex.institutions | schema_openalex_institutions.json | [Repo](https://github.com/naustica/openalex) |  10.05.2022  | All       |  108.660 |
| 2022-04-12 | venues/       | openalex.venues       | schema_openalex_venue.json        | [Repo](https://github.com/naustica/openalex) |  10.05.2022  | All       | 124.066 |
| 2022-05-12 | works/        | openalex.works        | schema_openalex_work.json         | [Repo](https://github.com/naustica/openalex) |  16.05.2022  | All (error threshold <= 1000) | 211.003.388 |
