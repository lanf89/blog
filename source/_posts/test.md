---
title: Hexo+Github Page搭建博客，部署失败的原因和解决方法
date: 2024-12-13 21:56:44
tags:
---
我不使用一键部署，按照官网的方法一一步步部署，Action却总是失败。
琢磨许久，原因是action build时，总是默认使用jekyll构建，pages.yml中并不需要这一步。
解决方法：直接运行pages.yml，成功！

