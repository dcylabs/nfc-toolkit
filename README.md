# About 
* Integrates Libnfc drivers with MFOC and MFCUK installed 
* Preconfigured to work on ttyUSB0 uart 

# Usages 
## Docker 
```
docker run --rm -h nfc-toolkit -ti --device=/dev/ttyUSB0 -v $(pwd):/workspace nfc bash
```
