## Recovery Device Tree for the Samsung Galaxy A30s (Exynos)

## How-to compile it:

```sh
. build/envsetup.sh
lunch omni_a30s-eng
make recoveryimage -j$(nproc --all)
```
