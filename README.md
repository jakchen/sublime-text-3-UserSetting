---
title: sublime text3使用介绍
tags: sublime text3
grammar_cjkRuby: true
---
## 我的用户设置：
{
"font_size": 12,
//字体大小
"highlight_line": true,
//高亮编辑中的那一行
"ignored_packages":
[
"Vintage"
],
//忽视vim模式
//"word_wrap": false,
//自动换行
"bold_folder_labels": true,
//加粗文件夹名称
"save_on_focus_lost": true,
//焦点丢失后自动保存
"tab_size": 2,
"translate_tabs_to_spaces": true,
//Tab转换
"trim_trailing_white_space_on_save": true,
//保存时去掉每一行文本最后面的空格
//"theme": "Seti_orig.sublime-theme",
//使用seti_ui
}
## 我的快捷键设置：
[
  { "keys": ["ctrl+shift+`"], "command": "show_panel", "args": {"panel": "console", "toggle": true} },
  //对齐
    { "keys": ["f5"], "command": "open_in_browser" },
    //在浏览器中打开文件
   {"keys": ["ctrl+shift+i"],"command": "htmlprettify"},
]