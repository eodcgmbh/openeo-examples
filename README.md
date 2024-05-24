# openeo-examples



## Getting started

Visit https://openeo.cloud/ and create and openEO account. 

## Set up your python environment

```
poetry install --all-extras
```

## Run your python code to connect to openEO

```
import openeo
conn = openeo.connect("openeo.cloud")
conn = conn.authenticate_oidc()
```

## openEO documentation can be found at

https://docs.openeo.cloud/

## Explore the notebooks

These notebooks provide simple examples to start using openEO: We create process graphs, send them to openEO, run them as jobs, and download and explore the results.
