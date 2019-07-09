## Gitee Trending Explore for Alfred Workflow

用于查看浏览`码云开源项目`（gitee.com/explore）的一款 `Alfred3 workflow` 插件(不依赖第三方模块)

## 使用说明

### 环境要求

- 操作系统：macOS
- `Alfred workflow` 插件运行在 `Alfred3` 上，所以你需要拥有 [Alfred] 并解锁 `Alfred PowerPack`
- 本插件运行需要 [PHP] 环境

### 下载

通过代码仓库 Git Clone 或下载ZIP包即可。

### 安装
双击 `Gitee 码云热门项目.alfredworkflow` 文件即可，插件将自动完成安装。

> 如需代码安装，需在项目目录执行 `composer install` 安装 [Composer] 依赖。

### 查询

- 在`Alfred`中触发关键字**`gitee-hot`**，然后输入`d`或`w`触发查询

> 参数含义如下：
> 
> - `d` 表示当日热门
> - `w` 表示本周热门
> 
> Tips: `Alfred 关键字`和`查询内容`之间必须有一个空格

### 打开查询结果

- 使用 `Enter` 复制查询内容的 URL 地址
- 使用 `Command + Enter` 通过浏览器打开查询的内容
  
[码云]:gitee.com
[Alfred]:www.alfredapp.com
[PHP]:https://php.net
[Composer]:https://getcomposer.org/