# xchAssist

#### 介绍
心持恒的辅助小工具库
辅助背诵


#### 使用教程
非常简单的一个html单页，用浏览器打开即可使用
发题自己修改背诵内容改变txt内容即可
```js
        //改这儿
        var txt = "题目：啦啦，可以<br>换行:答案:提示,题目2:答案2";
        txt += ",题目3:答案3";
        //end
```

格式参考:
- "题目:答案:提示,题目2:答案";
- 注意符号使用中文符号，避免使用系统符号导致错误
- 换行使用:&lt;br&gt;

答题:
- 输入答案后直接回车和确定即可完成答题，如果错误会显示答案和提示并将错误的题目加到现有最后一个下次再答,输入正确后进入下一题

错误统计的使用方法:
- 在输入框中输入 ex1 确认,显示统计信息
- 在输入框中输入 ex2 确认,显示的是所有错误题目的txt格式，方便使用
- 在输入框中输入 ex3 确定,清空统计信息