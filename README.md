# Gaze

## Installation

```bash
cd platform
helm dependency build
helm install gaze-platform -f ./values.yaml -f ../global.yaml . --namespace platform --create-namespace
```
