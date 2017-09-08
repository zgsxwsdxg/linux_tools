#!/usr/bin/env bash
echo 'Hello,World'
CWD=$(pwd)
echo ${CWD}

# 统计当前文件夹下文件的个数
ls -l |grep "^-"|wc -l

# 统计当前文件夹下目录的个数
ls -l |grep "^d"|wc -l

# 统计当前文件夹下*.jpg文件的个数
ls -l *.jpg|grep "^-"|wc -l

# 统计当前文件夹下*.jpg文件的个数
ls -l ${CWD}/*.jpg |wc -l

# 统计当前文件夹下*.jpg文件的个数
ls ${CWD}/*.jpg |wc -l
