# OceanOS

 Getting Started
---------------
To get started with the sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

To initialize your local repository, use command:

```bash
repo init -u https://github.com/OceanRom/android_manifest.git -b Ocean-12.1
```
or to save time and data,

```bash
repo init --depth=1 -u https://github.com/OceanRom/android_manifest.git -b Ocean-12.1

```

Then sync up:

```bash
repo sync
```

Building the System
-------------------
 Initialize the ROM environment with the envsetup.sh script.

```bash
. build/envsetup.sh
```

Lunch your device after cloning all device sources if needed.

```bash
lunch Ocean_devicecodename-buildtype
```

Start compilation

```bash
m otapackage
```

OR

```bash
m bacon
```	 

**You can also refer to our detailed guides as listed below:**

[How to compile ArrowOS from source](https://blog.arrowos.net/posts/compilation-guide)

---------------------------------------------------------------------------------------------------------------------
