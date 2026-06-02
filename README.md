# iOS WebDriverAgent Runner (未签名版本)

这是一个用于iOS自动化测试的未签名WebDriverAgent运行时包。无需Mac电脑和Xcode编译，可以使用i4助手等签名工具重新签名后安装到iOS设备上。

## 特性

- **基于iOS-Tagent**：基于AirtestProject/iOS-Tagent master分支编译

## 使用方法

1. 从本仓库下载`.ipa`文件
2. 在电脑上使用i4助手或其他iOS签名工具对IPA进行重新签名
3. 可与支持WebDriverAgent的各种自动化框架配合使用。

## 系统要求

- iOS设备（10.0及以上版本）
- i4助手等签名工具

## 兼容性验证

- iPhone 8, iOS 16.7.10 - 验证可用
- iPhone 17, iOS 26.1 - 验证可用

## 其他版本未签名的wda.ipa如何制作？

1. 正常使用苹果电脑，或者虚拟机macos 安装xcode 正常编译，安装到越狱真机上
2. 目标手机已越狱，安装appsdump2,将wda砸壳导出即可

---

# iOS WebDriverAgent Runner (Unsigned Version)

This is an unsigned WebDriverAgent runtime package for iOS automation testing. You can install it on iOS devices without a Mac computer or Xcode compilation, using signing tools like i4 Assistant.

## How to Use

1. Download the `.ipa` file from this repository
2. Re-sign the IPA using i4 Assistant or other iOS signing tools on computer
3. Can be used with various automation frameworks that support WebDriverAgent.

## System Requirements

- iOS device (version 10.0 or above)
- Signing tools like i4 Assistant

## Compatibility Verification

- iPhone 8, iOS 16.7.10 - Verified working
- iPhone 17, iOS 26.1 - Verified working

## How to Create Other Unsigned wda.ipa Versions?

1. Use a Mac computer or macOS virtual machine to install Xcode and compile normally, then install on a jailbroken real device
2. The target phone is jailbroken, then install appsdump2 to decompile and export WDA.ipa



