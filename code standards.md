# 代码规范
- Form <a href="http://alloyteam.github.io/CodeGuide/">Code Guide by @AlloyTeam</a>
## 命名规则
### 1、项目命名、JS文件命名、CSS，SCSS文件命名、HTML文件命名
全部使用小写方式，用下划线分隔。</br>

e.g:header_right
### 2、目录命名
参照项目命名法，`有复数结构时，使用复数命名法`。</br>

e.g:styles

## HTML
### 1、语法
- 属性名全小写，用中划线做分隔符；
- 不要在自动闭合标签结尾处使用斜线；
- 不要忽略可选的关闭标签；e.g:`</body>`。
### 2、DOCTYPE
在页面开头使用`<!DOCTYPE html>`来启用标准模式，使其在每个浏览器中尽可能一致的展现。`doctype不区分大小写，但惯例大写`
### 3、lang属性
在html标签上加上lang属性,控制语音工具和翻译工具。

- lang属性细分为：zh-cn, zh-hk, zh-tw.
### 4、字符编码
一般为`UTF-8`
### 5、属性顺序
- class
- id
- name
- data-*
- src, for, type, href, value , max-length, max, min, pattern
- placeholder, title, alt
- aria-*, role
- required, readonly, disabled

`class是为高可复用组件设计的，所以应处在第一位；id更加具体且应该尽量少使用，所以将它放在第二位。`
