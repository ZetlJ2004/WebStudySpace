# web-examples

### Introductions

基础网页开发技术，为前端开发技术提供支撑。  
熟悉 Markdown 文档语法。  
熟悉 git/github。

### Development Environments

- VS Code
- Prettier
- Git

### Update

#### 2024.09.04 17:17

实现了 git 的操作（拉取、推送等），VSCode 的配置。

<br>
———————————————————————————————
<br>

## request

**JS 需求**

函数将传入数字千分位加逗号返回（输入 1234，输出 1,234）。思路：多种方式，可尝试 split()/join()函数转字符数组再聚合。

函数传入对象数组/属性名称，将多余的属性名称相同元素移除。

```js
const objs = [{ id: 9 }, { id: 8 }, { id: 7 }, { id: 7 }, { id: 7 }, { id: 6 }]
```

**jQuery**

```shell
jQuery CDN; element object/jquery object; jquery API;
```

**jQuery 需求**

用户仅能选择指定数量的选项。

多导航组的二级菜单手风琴效果。实现点击一级导航标题，toggle 其下的二级菜单，同时收缩其他已展开的二级菜单。

模拟选课时，响应式禁选授课时间冲突课程。思路：必须先设计适合检索的数据类型(建模)

#### 2024.05.14

**CSS**

flex 布局；12 栅格布局；  
CSS 选择器从右向左解析的原因；

**JS**

JS 基本语法；箭头函数；对象；模板字符串；JSON；callback；

```shell
arrays；for-of/for-in/forEach()/find()/map()/filter()/sort()/splice()/includes();
onclick/onchange/onkeyup/onkeydown events；
document/getElementById()
```

**需求**

当改变课程名称下拉框值时，从对象数组中找到对应的授课教师姓名，渲染到页面。  
下拉框项的值为 id 值。

```json
[
  { "id": 1, "courseName": "Java", "teacherName": "BO" },
  { "id": 2, "courseName": "Web", "teacherName": "SUN" },
  { "id": 3, "courseName": "Python", "teacherName": "ZHANG" }
]
```

当 2s 后输入框没有输入时，将输入字母转为大写。(up/down 事件；定时器；定时器取消；封装)

#### 2024.04.26

**CSS**

```shell
element/id/class Selectors; Cascading; Units; Box Model;
Background/Image/Text/Opacity; Combinators Selectors; display;
Vertical-Align; table; float; position; Box-Sizing; Navigation Bar
```

#### 2024.04.20

掌握基本 git/github 本地远程版本控制

掌握基于 gihub pull request 的团队项目开发

```shell
 origin; master; branch; branch types; commit; commit message types;
 push; pull; marge
```

Github PR。操作基本可通过 vs code 实现

1. fork，源仓库至个人远程仓库

2. clone，个人仓库至本地

3. upstream，关联源仓库

4. branch，创建 docs branch。有点麻烦，但还是掌握了吧

5. commit，docs branch 中修改提交

6. pull，更新拉取源仓库至当前 docs branch

7. merge，将源仓库 upstream merge 至 docs branch。目的：如果有冲突，要在 branch 解决而不是 master

8. branch，切换回 master branch，再从 master merge docs branch。由于 upstream/docs branch 冲突已经在 docs branch 解决，因此可直接整合 upstream 至 master branch。此时，upstream/master/bocs 汇聚为最新提交节点

9. push，可直接向源仓库 push upstream。等待源仓库合并代码

10. pull，收到源仓库 merge 通知后，更新本地 master branch，并再次 push 至个人远程仓库

11. 此时，master branch; origin/master; upstream/master，同步

12. del branch，删除完成使命的 docs branch

#### 2024.04.16

**HTML**

```shell
div; span; p; h1; br; hr; table; ul; img;
```

**Emmet**

```shell
>; +; ^; (); *; $; lorem;
```

**markdown**

维护学习文档

#### 2024.04.10

项目`.vscode/`目录？目录下的文件？文件中的配置？`.prettierrc.json`？  
熟悉 vscode 功能。  
创建基本网页，在 vscode 中调用浏览器打开。  
熟悉基本 HTML 标签。  
熟悉基本 Emmet 语法。
