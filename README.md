# Paranoid Android (AOSPA) for pipa #

### Initialize Paranoid Android ###
```
repo init -u https://github.com/paranoid-pipa/manifest -b vauxite --depth 1
```

### Sync Sauce ###
```
repo sync --force-sync -j$(nproc --all)
```

### Cook AOSPA ###
```
./rom-build.sh pipa
```

## Now Build and Enjoy! ##
