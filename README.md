## General module testing procedure

### Export required variables
```
MOLECULE_EPHEMERAL_DIRECTORY="${PWD}/.molecule" 

export MOLECULE_EPHEMERAL_DIRECTORY
```

### Launch molecule commands
```
molecule create
molecule converge
molecule idempotence
molecule destroy
```
