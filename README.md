# openeo-examples



## Getting started

Visit https://openeo.cloud/ and create and openEO account. 

## Install openeo in your python environment

```
pip install openeo
```

## Run your python code to connect to openEO

```
import openeo
conn = openeo.connect("openeo.cloud")
conn = conn.authenticate_oidc()
```

## Explore the notebooks

These notebooks provide simple examples to start using openEO: We create process graphs, send them to openEO, run them as jobs, and download and explore the results.
