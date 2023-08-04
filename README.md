{
  // Vscode版本设置手动更新
  "update.mode": "manual",
  // 字体大小为17px
  "editor.fontSize": 17,
  // 按Tab键为2个字符
  "editor.tabSize": 2,
  // 这里禁用掉了按ctrl+s会改变代码格式
  "editor.formatOnSave": false,
  // 文件延时保存
  "files.autoSave": "afterDelay",
  // 文件1.5秒后自动保存
  "files.autoSaveDelay": 1500,
  // liveServer插件配置
  "liveServer.settings.donotShowInfoMsg": true,
  // liverServer的端口号
  "liveServer.settings.port": 63343,
  // liverServer的默认主机名
  "liveServer.settings.host": "localhost",
  // liverServer的自定义浏览器
  "liveServer.settings.CustomBrowser": "chrome",
  // 默认打开浏览器为谷歌
  "open-in-browser.default": "chrome",
  // 资源管理器中的压缩文件夹
  "explorer.compactFolders": false,
  // 默认使用tab键来选择提示项（好像没法改），所以按 Tab 的时候就变成选中提示项，而非展开缩写了，把下面改成true就行
  "emmet.triggerExpansionOnTab": true,
  // 显示扩展缩写
  "emmet.showExpandedAbbreviation": "inMarkupAndStylesheetFilesOnly",
  // 文件图标
  "workbench.iconTheme": "vscode-icons",
  // 缩进 head 和 body 部分(默认false)
  "html.format.indentInnerHtml": true,
  // 激活时显示括号颜色
  "editor.guides.bracketPairs": "active",
  // 在内联处理程序中隐藏事件参数
  "volar.inlayHints.eventArgumentInInlineHandlers": false,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },
  // 设置对应文件的prettier格式化
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[vue]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  // 可以在markdown中使用代码片段
  "[markdown]": {
    "editor.quickSuggestions": {
      "other": "on",
      "comments": "off",
      "strings": "off"
    }
  },
  // 从外部应用中打开md文件，指定的软件是typora
  "openInExternalApp.openMapper": [
    {
      // 文件后缀名
      "extensionName": "md",
      "apps": [
        {
          "title": "typora",
          "isElectronApp": true,
          // exe文件路径，需要换成自己的
          "openCommand": "D:\\QS_Soft\\Typora\\typora-setup-x64.exe"
        }
      ]
    }
  ],
  "eslint.validate": [
    "javascript", //  用eslint的规则检测js文件
    "vue"
    // "javascriptreact",
    // {
    //   "language": "vue", // 检测vue文件
    //   "autoFix": true //  为vue文件开启保存自动修复的功能
    // },
    // {
    //   "language": "html",
    //   "autoFix": true
    // },
  ],
  "projectManager.sortList": "Name",
  // 关于小程序的配置
  "files.associations": {
    "*.cjson": "jsonc",
    "*.wxss": "css",
    "*.wxs": "javascript"
  },
  "emmet.includeLanguages": {
    "wxml": "html"
  },
  "less.compile": {
    "outExt": ".wxss"
  },
  "minapp-vscode.disableAutoConfig": true,
  "editor.unicodeHighlight.ambiguousCharacters": false,
  // 秦丝ChatGPT的登录token
  "chatgpt.qinsilkAccountSession": "1DAF184F6CBBC608E4D5BC6F8E01E739",
  "chatgpt.timeoutLength": 60,
  "vue.inlayHints.optionsWrapper": false,
  "workbench.colorTheme": "Default Dark+"
}