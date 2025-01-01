# How to use

```bash
mkdir -p .repo/local_manifests
git clone https://github.com/dashlander/denniz_manifests .repo/local_manifests
repo sync -j$(nproc --all)
```
