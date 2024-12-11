# Maximize disk space

Maximize the disk space of GitHub Actions.

```yaml
name: Free Disk Space
on: push

jobs:
  free-disk-space:
    runs-on: ubuntu-latest
    steps:

    - name: Free Disk Space
      uses: firus-v/free-disk-space@main
```