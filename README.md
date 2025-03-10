<img src="https://github.com/ArrowOS/getting_started/blob/master/misc/logo.png?raw=true">

# ArrowOS Revived

 Getting Started
---------------
To get started with the ArrowOS sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

To initialize your local repository, use command:

```bash
repo init -u https://github.com/ArrowOS-Revived/android_manifest.git -b arrow-11.0
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
lunch arrow_devicecodename-buildtype
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

To check thread template refer [**HERE**](https://raw.githubusercontent.com/ArrowOS/documentation/master/thread_template.txt)

---------------------------------------------------------------------------------------------------------------------

[ArrowOS Website](https://www.arrowos.net/) | [ArrowOS Blog](https://blog.arrowos.net/)

---------------------------------------------------------------------------------------------------------------------
