# Hololens2MrtkBaseProject
## 1. 概要
Mixed Reality Toolkit(MRTK)の初期設定済みのUnityプロジェクトです。

|  機能  |  バージョン  |
| ---- | ---- |
|  Unity  |  2020.3.26f1  |
|  Mixed Reality Toolkit Foundation  |  2.7.3  |
|  Mixed Reality Toolkit Standard Assets  |  2.7.3  |
|  Mixed Reality Toolkit Tools  |  2.7.3  |
|  Mixed Reality OpenXR Plugin  |  1.2.1  |

## 2. 初期設定内容
### (1) Project Setting
XR Plug-in Managementは**OpenXR**を選択しています。  
AudioのSpatialize Pluginは**Microsoft Spatializer**に設定しました。  

適宜、Project Setting -> Player -> Publishing Setting -> Package name を変更してください。   
Holographic Remoting remote app は有効化していないため、要すれば有効化してください。

### (2) Profile
MixedRealityToolkitのProfileは「OpenXRConfigurationProfile」をベースにしてあります。 

Spatial Awarenessを有効化し、周囲のメッシュはOcclusion(非表示)にしてあります。  
もし変更する場合は、Spatial Awareness System Settingの「Display Option」を変更してください。  
もしくはアプリケーションによっては処理負荷軽減のため無効化してください。

Holographic Remoting remote appを利用した時のために、Camera SettingのDisplay SettingのClear FlagsをColorにしてあります。
もしデフォルトのSkyboxが必要な方は変更ください。

## 3.利用前の注意点

