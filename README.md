# All-About-GPA

## Reference

1. [Intel® Graphics Performance Analyzers](https://software.intel.com/content/www/us/en/develop/tools/graphics-performance-analyzers.html)
2. []
## Downloading and Installation

```
wget https://registrationcenter-download.intel.com/akdlm/irc_nas/17942/gpa_21.2.1624350604_release_m64_deb_install.sh

sudo bash gpa_21.2.1624350604_release_m64_deb_install.sh
```

## Supported Graphics APIs

| API         | Windows Host       | Ubuntu Host | macOS Host |
| ----------- |  -----------       | ----------- | -----------|
| DirectX     | :heavy_check_mark: | :x:                | :x:                |
| Vulkan      | :heavy_check_mark: | :heavy_check_mark: | :x:                |
| Metal       | :x:                | :x:                | :heavy_check_mark: |
| OpenGL      | :x:                | :heavy_check_mark: | :heavy_check_mark: |
