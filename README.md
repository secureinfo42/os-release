# os-release

/etc/os-release for macOS

Generate a /etc/os-release for macOS using `system_profiler`, `sysctl`.

For the likey version name found there :
`/System/Library/CoreServices/MajorOSInfo.bundle/Contents/Resources/en_GB.lproj/Localizable.strings` 


```sh
PRETTY_NAME="macOS Monterey"
NAME="macOS"
ID=Darwin
VERSION="12.6"
VERSION_ID="12.6"
VERSION_CODENAME="monterey"
ID_LIKE=macOS
KERNEL_VERSION="21.6.0"
XNU_VERSION="root:xnu-8020.140.49~2/RELEASE_ARM64_T8101"
ANSI_COLOR="1;31"
HOME_URL="https://www.apple.com/"
```
