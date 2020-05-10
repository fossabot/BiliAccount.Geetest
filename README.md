# BiliAccount.Geetest
用于处理B站账号操作过程中的极验验证码|used to handle the geetset captcha for BiliAccount | https://github.com/LeoChen98/BiliAccount

[![Version](https://img.shields.io/github/release/LeoChen98/BiliAccount.Geetest.svg?label=Version)](https://github.com/LeoChen98/BiliAccount.Geetest/releases)
[![GitHub issues](https://img.shields.io/github/issues/LeoChen98/BiliAccount.Geetest.svg)](https://github.com/LeoChen98/BiliAccount.Geetest/issues)
[![需要帮助的 issue](https://img.shields.io/github/issues/LeoChen98/BiliAccount.Geetest/help%20wanted.svg?label=需要帮助的%20issue)](https://github.com/LeoChen98/BiliAccount.Geetest/issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22)
[![Language](https://img.shields.io/badge/%E8%AF%AD%E8%A8%80-%E4%B8%AD%E6%96%87-brightgreen.svg)](#)
[![DevLanguage](https://img.shields.io/badge/%E5%BC%80%E5%8F%91%E8%AF%AD%E8%A8%80-C%23-brightgreen.svg)](#)
[![Pull Request Welcome](https://img.shields.io/badge/Pull%20request-welcome-brightgreen.svg)](#)
[![GitHub license](https://img.shields.io/github/license/LeoChen98/BiliAccount.Geetest.svg)](https://github.com/LeoChen98/BiliAccount.Geetest/blob/master/LICENSE)

## 支持与依赖
框架|版本|依赖|备注
---|---|---|---
.net framework|≥3.5|（无）|`2.0.0.7`前只支持`.net framework 4.5`
.net standard|≥2.0|[Newtonsoft.Json](//github.com/JamesNK/Newtonsoft.Json) (≥ 12.0.3)<br/>[QRCoder](//github.com/codebude/QRCoder/) (≥ 1.3.6)<br/>[System.Drawing.Common](//github.com/dotnet/corefx) (≥ 4.7.0)|`2.0.0.7`起支持
.net core|≥3.0|[Newtonsoft.Json](//github.com/JamesNK/Newtonsoft.Json) (≥ 12.0.3)<br/>[QRCoder](//github.com/codebude/QRCoder/) (≥ 1.3.6)<br/>[System.Drawing.Common](//github.com/dotnet/corefx) (≥ 4.7.0)|`2.0.2.9`起支持

## 项目结构
项目名|备注
--|--
[BiliAccount.Geetest](https://github.com/LeoChen98/BiliAccount.Geetest/wiki/BiliAccount)|BiliAccount.Geetest类库

## 获取与使用

[![Nuget (with prereleases)](https://img.shields.io/nuget/vpre/BiliAccount.Geetest?color=%23004080&logo=nuget)](https://www.nuget.org/packages/BiliAccount.Geetest/)
[![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/LeoChen98/BiliAccount.Geetest?include_prereleases&logo=github)](https://github.com/LeoChen98/BiliAccount.Geetest/releases/latest)

**在使用以下命令时请将`Version`节点改为上述最新版本，否则可能会有错误。 **

工具|命令/代码
--|--
Package Manager|`Install-Package BiliAccount.Geetest -Version 2.2.0.12`
.NET CLI|`dotnet add package BiliAccount.Geetest --version 2.2.0.12`
PackageReference|`<PackageReference Include="BiliAccount.Geetest" Version="2.2.0.12" />`
Packet CLI|`paket add BiliAccount.Geetest --version 2.2.0.12`

具体使用方法请见[Wiki](https://github.com/LeoChen98/BiliAccount.Geetest/wiki)

## 开放源代码许可
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FLeoChen98%2FBiliAccount.Geetest.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FLeoChen98%2FBiliAccount.Geetest?ref=badge_large)
