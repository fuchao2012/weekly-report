## Example

![](http://g.recordit.co/svlsBqYHni.gif)

## What does weekly-report do

1. Recursively find Git repos under your working dir
1. generate prettified commit report of last 7 days.

## When will you need it

- You are contributin to **multipul**/one project to your company/yourself
- You need to present a weekly report
- You want to see what you have done last week

## Install

```
$ npm install -g weekly-report
```

## Usage

```
# Go to your working dir (should be project using git or contains git projects inside)
$ cd dir/contains/projects/using/git

# Generate weekly report
$ weekly-report # or wr for short
```

## Note

- The script will stop inspect dirs inside a dir if the dir is a git project.
- script will go 3 layer down
- make sure your git repos are on the right branch

## Todo

- 添加 Nodemailer 发送邮件
- 删除 git commit 中的 merge 信息
- 贴近现有周报样式格式化输出文本
- 给出最佳git commit 方式
