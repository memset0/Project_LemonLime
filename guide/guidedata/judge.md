# 评测

在左上角选中 `选手` ，进入选手名单。

点击选手名单的表头可以对某一个参数排序。

## 背景颜色

正常评测的成绩将会拥有以绿色为基础颜色的背景颜色。

颜色从白到绿对应分数从低到高，总分的颜色会更深。这个配色方案大体来自 IOI。

如果出现 `编译错误`、`编译超时` 等不正常情况，背景颜色将会是粉色。

如果出现 `未找到选手程序`，背景颜色将会是灰色。

## 整理文件

> **！ 注意**
>
> 如果子文件夹里面的文件有文件名和子文件夹外面的文件相同的，子文件夹**外面的文件会丢失**！
>
> **大部分**无关文件也将**全部丢失**！
> 
> 最好在整理文件之前备份一份，以防不测。

为每个选手的每一个文件创建它的子文件夹内的文件和子文件夹外的文件，无论它们以前是在子文件夹内还是子文件夹外，并且删除大部分无用文件。


## 刷新

刷新选手列表。

## 测试选中

可以选中任意选手的任意题目。

在选手列表中选中一些选手的一些题目，点击 `测试选中` 就能测试它们。

如果选中了某选手的排名、名称、总分、总用时、测试时间的其中某一个，那么将默认测试这个选手的所有题目。

## 测试全部

测试全部选手的全部题目。

## 测试未测试

测试所有选手的还没有测试的题目，并且更新成绩。

## 测试未找到文件的

测试所有选手的未找到文件的情况的题目。

## 测试编译出错的

测试所有选手的编译出错的情况（编译错误、编译超时等）的题目。

## 测试情况对话框

这个对话框会实时显示当前评测的情况。

不同的评测结果的字体颜色会不相同。

如果选手在某一个测试点 `答案正确` 或者 `答案部分正确`，那么会显示它的得分、用时和所使用的空间。

进度条上会显示当前进度和总时间限制。

### * 跳过这一题

当你肯定某个选手是卡评测或者其它原因，或者这个题的评测结果无关紧要（比如自己自娱自乐的时候），那么可以点击 `跳过这一题` 。

这会打断当前评测的题目，并跳过这道题之后的所有测试点。

跳过的测试点会显示 `超过时间限制`。（如果显示 `被跳过`，那被跳过的人看到了肯定会很不高兴然后 D 评测人员。）

注意：LemonLime 使用 GPLV3 许可证，``There is no warranty for this free software``。

### 停止测试

点击后将停止测试，保留之前测试过后得到的所有分数数据。