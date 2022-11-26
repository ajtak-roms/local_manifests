# Required patches in order to flash and boot ROM.

## If not possible to apply with "git apply", apply patches manually



cd ./system/core && git apply --verbose /optd/local_manifests/common/system/core/0001-liblp-Allow-to-flash-on-bigger-block-device.patch

cd ./vendor/lineage && git apply --verbose /optd/local_manifests/crdroid-9.0/vendor/lineage/0001-Split-msm8937-from-UM_3_18_FAMILY-and-fix-it.patch