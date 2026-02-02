# 🚀 Paranoid Android (AOSPA) for pipa #

### 📥 Initialize Paranoid Android ###
```
repo init -u https://github.com/paranoid-pipa/manifest -b vauxite --depth 1
```

### 🔄 Sync Sauce ###
```
repo sync --force-sync -j$(nproc --all)
```

### 🍳 Cook AOSPA ###

#### 📦 Recovery Package
```
./rom-build.sh pipa
```

#### ⚡ Fastboot Package
```
source build/envsetup.sh
lunch aospa_pipa-user
make updatepackage
```

## 🎉 Now Build and Enjoy! ##


