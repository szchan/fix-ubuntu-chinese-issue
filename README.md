# fix-ubuntu-chinese-issue
解决ubuntu系统中文字存在错别字问题
---
ubuntu中文字显示的错别字实为日文汉字。

在遇到东亚文字时，因为ubuntu默认字符优先级原因，有日文字的先显示日文版本，无日文再用韩文，然后才是简体中文和繁体中文。此脚本解决问题的原理为提高中文字的优先级。

---
 - 使用中文简体的朋友，运行fix-si.sh
 - 使用中文繁体的朋友，运行fix-tr.sh
 - 运行结束后，重启系统以应用改动
---
运行方式：
简体：
 1. sudo chmod +x ./fix-si.sh
 2. sudo sh -c ./fix-si.sh

繁体：
 1. sudo chmod +x ./fix-tr.sh
 2. sudo sh -c ./fix-tr.sh

重启应用改动：sudo reboot

---
已在Ubuntu 22.04; Ubuntu 20.04测试。
