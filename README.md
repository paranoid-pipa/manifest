# 🚀 Paranoid Android (AOSPA) for pipa #

### 📥 Initialize Paranoid Android ###
```
repo init -u https://github.com/paranoid-pipa/manifest -b vauxite --depth 1
```

### 🔄 Sync Sauce ###
```
repo sync -c -j$(nproc) --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune --depth=1
```

### 🍳 Cook AOSPA ###
```
./rom-build.sh pipa
```

## 🎉 Now Build and Enjoy! ##


