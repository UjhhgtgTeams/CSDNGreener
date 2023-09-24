<p align=center>
  <img src="https://user-images.githubusercontent.com/6754458/130888102-4b7b35b4-6532-4967-90df-118123ee8653.png"/>
  <br>
  <a title="Hits" target="_blank" href="https://github.com/88250/hits"><img src="https://hits.b3log.org/UjhhgtgTeams/CSDNGreener.svg"></a>
  <img src="https://img.shields.io/github/stars/UjhhgtgTeams/CSDNGreener?style=flat-square"/>
  <img src="https://img.shields.io/github/contributors/UjhhgtgTeams/CSDNGreener?style=flat-square"/>
  <img src="https://img.shields.io/github/commit-activity/y/UjhhgtgTeams/CSDNGreener?style=flat-square"/>
  <img src="https://img.shields.io/github/last-commit/UjhhgtgTeams/CSDNGreener?style=flat-square"/>
  <br>
  <img src="https://img.shields.io/github/issues/UjhhgtgTeams/CSDNGreener?style=flat-square"/>
  <img src="https://img.shields.io/github/issues-pr/UjhhgtgTeams/CSDNGreener?style=flat-square"/>
  <img src="https://img.shields.io/github/watchers/UjhhgtgTeams/CSDNGreener?style=flat-square"/>
  <img src="https://img.shields.io/github/issues-closed/UjhhgtgTeams/CSDNGreener?style=flat-square"/>
  <br>
  CSDNGreener，一款专为 Tampermonkey 插件打造的 CSDN 绿化脚本。<br>
  该 Fork 不含原脚本的使用情况统计。
</p>

### :iphone: 兼容性

CSDNGreener 是一个优化 CSDN 广告、使用体验的脚本，有口皆碑。  
在使用脚本之前，你需要为浏览器安装脚本管理器插件。  
经过测试，我们确定兼容以下浏览器和插件用于安装此脚本。

#### :globe_with_meridians: 浏览器支持

* Firefox <sup>*隐私保护首选</sup>
* 基于 Chromium 的浏览器 (Google Chrome, Microsoft Edge 等) <sup>*推荐</sup>  

#### :see_no_evil: 脚本管理器（任选其一即可）

* Tampermonkey (新油猴) <sup>*<a href="https://www.tampermonkey.net/">安装</a></sup>  
* Violentmonkey (暴力猴) <sup>*<a href="https://violentmonkey.github.io/get-it/">安装</a></sup>  
<sub>注：Greasemonkey (旧油猴) 由于过于古老，不支持该脚本。</sub>

#### :test_tube: 支持的操作系统

* Windows、MacOS、Linux 等支持 Chrome 或 Firefox 浏览器的所有操作系统，移动平台除外 <sup>*Via 浏览器内置了安装脚本的功能，但尚未经测试</sup>

### :page_facing_up: 安装脚本

* 从 GreasyFork 安装
通过 GreasyFork 安装脚本: **[点我](https://greasyfork.org/zh-CN/scripts/446239)**  

* 从 OpenUserJS 安装
通过 OpenUserJS 安装脚本: **[点我](https://openuserjs.org/scripts/Ujhhgtg/%E8%A2%AB%E4%BC%98%E5%8C%96%E7%9A%84CSDN%E4%BC%98%E5%8C%96%E8%84%9A%E6%9C%AC_\()**  
然后点击页面右上角的`Install`进行安装.

### :rocket: 贡献
欢迎对本项目提交 **Issues** 帮助我完善脚本；  
如果你对 JavaScript 有所了解，可以直接提交 **Pull Requests**，要求如下：

- 修改版本信息

  * 格式
  ##### 上游：将版本号后的数字按照顺序向后延一位，若遇到进位则正常进位
  ##### 下游：将版本号后的字母按照顺序向后延一位，若遇到最后一位则在其后继续添加
  ##### 例：1.1.9 -> 1.1.10 | 1.1.9z -> 1.1.9za
  
  * 位置
  ```javascript
  // @version      1.1.9
  ```
  ```javascript
  var version = "1.1.9";
  ```

- 添加更新描述
  
  ```javascript
  // @note         19-06-04 1.1.9 更新描述
  ```
