# ipa_build

# 使用教程

1. 将ipa_build这个文件夹移到和.xcodeproj或.xcworkspace同一级目录

2. 打开build_debug或者build_release文件，替换profile_name字段，替换为你要打包项目的profile name

3. 打开你的字段  `cd 脚本所在的目录` -> `chmod 777 build_debug.sh (仅第一次的时候需要)` -> `./build_debug.sh`

4. 查看你的桌面即可以查看导出的IPA包
