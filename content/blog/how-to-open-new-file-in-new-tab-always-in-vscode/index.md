---
title: 'How to always keep open files in Visual Studio Code'
date: "2020-01-18"
description: Solution to open files always in a new tab in Visual Studio Code
slug: 'how-to-always-keep-open-files-in-visual-studio-code'
tags:
  - vscode
  - tricks
show: true
author: shivam
---


Visual Code is am amazing editor and I use it for my everyday code. One thing bug me everytime is the files are not open permanently until I use the shortcut `cmd + k` `enter` or right click and select `keep open` on the filename. This happens because VS Code opens the files by default in `preview mode`, so whenever the new file name is clicked from explorer, the opened file closes and new file is visible.
But if you are equally frustrated by this behavior here is what you need to do. 

The solution is way simpler than expected, just add the following line to your  `setting.json`
(Code Menu > Preferences > Setting)


```code
"workbench.editor.enablePreview": false
```

---