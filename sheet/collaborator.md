# 表格协作者插件

表格编辑器实现协作者渲染功能的插件，用来配合协作者通信通用模块一起使用。

## 构造函数

* 用法

  ```js
    var editor = new shimo.sdk.sheet.Editor()
    var collaboratorEditor = new shimo.sdk.sheet.plugins.Collaborators({ editor })

    //使用协作者通用模块，启用协作者渲染功能

    var collaborator = new shimo.sdk.common.Collaborators({
      editor: collaboratorEditor
    })

    collaborator.start()
  ```

* 参数

|名称|类型|默认值|描述|
| -- | -- | -- | -- |
| `options.editor` | `Editor` | 必选 | 编辑器实例 |


