# Heterogeneous Networking Middleware Project Report

Source code and report for the Heteregenous Networking Middleware project for Fall 2015. 

# Applying Patches
After obtaining the source code of Android, run the following commands to apply patches.

```
git clone https://github.com/jchli/hetnet-report.git
pushd ~/android/frameworks/base
git am /path/to/hetnet-report/patches/base.patch
popd
pushd ~/android/framework/opt/telephony
git am /path/to/hetnet-report/patches/opt-telephony.patch
popd
```
