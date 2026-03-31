# awx-cloudee

AWX Execution Environment with pre-installed network collections.

### Build locally 

```bash
ansible-builder build \
  --file="awx-network-ee.yml" \
  --tag="awx-network:local" \
  -v 3
```

### Requirements

+ ansible-builder
+ podman 
