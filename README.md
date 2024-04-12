# beantech-anomaly-detector

ML model that finds anomalies in 3 types of industrial products.

## development

Dataset we use: https://paperswithcode.com/dataset/btad

To start development, download above dataset and unzip it in data folder.

```
src
└── data
    ├── README.txt
    └── BTech_Dataset_transformed
        ├── 01
        ├── 02
        └── 03
```

Use `Python 3.12` and `Poetry 1.8.2`:

```bash
poetry install --no-root
anomalib install --option core
```
