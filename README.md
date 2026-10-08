# wnts-sindyc

SINDYc system identification on the WNTS gas-pipeline network: protocol,
ablations A1-A4 / B1-B4, and the write-up in [REPORT.md](REPORT.md).

Split out of [`sciml-framework`](https://github.com/phoenixfin/sciml-framework)
(`experiments/wnts`) with its history. The method engines come from `sciml`,
pinned in `requirements.txt`.

```bash
pip install -r requirements.txt
python -m wnts.run --data-dir <path to the WNTS yearly CSVs>
```

The source data is **confidential and not in this repo**.
