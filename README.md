此代码用于已知很多人的名字，筛选出获奖的

---

### 使用方法

1. 下载适配自己谷歌浏览器版本的`chromedriver.exe`（下载链接：https://developer.chrome.com/docs/chromedriver/downloads?hl=zh-cn#current_releases，release中的版本为`131.0.6778.108`）替换release中的`chromedriver.exe`
2. 在`input.txt`中输入想要搜索的名称（仿照样例，一个一行）
3. 双击`main.exe`开始运行
4. 等待一段时间，待`medium.txt`消失，`output.txt`即为输出结果

### 旧版本代码说明

先运行`main.py`，获取html的信息，平均一个名字需要十秒钟左右（没关系，慢是慢了点，但是只需要跑一次，就挂着吧（））

然后运行`transer.py`，去除多余的无用信息（史山代码，千万别动）

最后运行`ender.py`，进行榜单的生成

此版本不含排序，oierdb无需登录无需cookie，准备好`input.txt`即可开跑

### 声明

获取人名名单需要合法。请勿用于非法用途，如使用本开源程序则表示接受此条款，若用于非法用途，作者不承担任何法律责任