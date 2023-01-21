# Listen1 Mobile

[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg)](LICENSE)

## 项目原地址

[listen1_mobile](https://github.com/listen1/listen1_mobile/)

## 简介

由于作者长时间未更新，所以自己尝试增加了一些需求度较高的功能

## TODO

- [ ] 增加 github.com 同步
- [ ] 增加 last.fm 同步
- [ ] 解决QQ音乐搜索无结果问题
- [ ] 增加歌词
- [ ] 增加歌单搜索功能
- [ ] 增加更多主题选择


## 编译

开发环境

- Java 8 JDK （更高版本需更新默认 gradle 版本）
- Nodejs 8 （版本>12.10.0 可能遇到 metro 一个关于正则表达式的 bug 导致的启动失败）
- Android Studio (Android SDK 版本 v28)

编译步骤

- Clone 或下载本项目代码
- `yarn` 安装依赖
- `yarn run link` 链接 React Native 的依赖库
- `yarn start:ios` 将在 iOS 模拟器上运行项目
- `yarn start:android` 将在安卓真机或模拟器（取决于手机是否连接）运行项目

Apk 打包

```
   cd .\android\
   ./gradlew assembleRelease
   react-native run-android --variant=release

```

更详细的打包信息（包括生成 keystone）

https://reactnative.cn/docs/signed-apk-android


## 法律相关

This software is distributed under the MIT license

In particular, please be aware that

> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
> IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
> FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
> AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
> LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
> OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
> SOFTWARE.

Translated to human words:

_In case your use of the software forms the basis of copyright infringement, or you use the software for any other illegal purposes, the authors cannot take any responsibility for you._

We only ship the code here, and how you are going to use it is left to your own discretion.
