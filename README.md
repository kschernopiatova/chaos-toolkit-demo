# chaos-toolkit-demo

Create and activate virtual python environment

```
python3 -m venv ~/.venvs/chaostk
source  ~/.venvs/chaostk/bin/activate
```

Install chaos-toolkit packages

```
pip install -r requirements.txt
```

Run specific chaos-toolkit experiment

```
chaos run path/to/experiment
```

To run experimants connected to kubernetes network, cpu and memory faults, you need to install chaos mesh to your kubernetes cluster and expose it with Ingress

[https://chaos-mesh.org/docs/quick-start/](https://)

[https://chaos-mesh.org/docs/expose-dashboard-with-ingress/](https://)
