solr-installer

This repository helps you install solr on Windows and run solr as a Windows service.

## Install

```sh
git clone https://github.com/sammtcbn/solr-installer.git
```

If jdk is not installed in your system, please install it first as following steps:
* In solr-install folder, run jdk-download-windows.bat to download jdk.
* After jdk is downloaded, execute it to install in your system.
* Add an Environment Variable named JAVA_HOME and set it to JDK installed path.

In solr-installer folder, run windows_install.bat as administrator.

solr will be installed at C:\solr

## Uninstall 

Go to C:\solr folder, run windows_uninstall.bat as administrator.
