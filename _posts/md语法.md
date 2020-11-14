---
layout: post
title: "Markdown �﷨�����ʼ�"
date:   2018-6-21
tags: [markdown]
comments: true
author: lemonchann
toc: true
---
**Markdown��һ�ֿ���ʹ����ͨ�ı��༭����д�ı�����ԣ�ͨ���򵥵ı���﷨��������ʹ��ͨ�ı����ݾ���һ���ĸ�ʽ��markdown��Ϊ��Щ��Ҫ�������ֻ��߽��������Ű�ġ����������ٺ��Ű�˳������Ҫ�����Ⱥ��Ƶģ�����ϣ���ü��̰��������ݴ��������Ѿ��Ű���ˣ���ô�ͷ��β����Ҫʹ����ꡣ��Щ�˰���������Ҫд�ĵ�����ũ������д�֡���վС�ࡢ����ҵ��ʿ�ȵ�** �ο�[**�ٶȰٿ�**](https://baike.baidu.com/item/markdown/3245829?fr=aladdin)

<!-- more -->

### markdown�﷨
��ʼѧϰmarkdown���б�Ҫ�˽�һ�»������﷨����������һЩ�������﷨����Щ�﷨�Ƿǳ����ҳ��õģ��ܹ�����������������������ı�����Բ����ܹ�����д�Լ���С���ͣ�����д�𲩿�֮��һЩ�߼����÷����Ա��ñ�ѧ��

- **������ʽ**
��Markdown�У���һ�����ֱ�����Ϊ���⣬ֻҪ���������ǰ�� # �ż��ɡ�ע������#�ź������пո�ġ�
>'# 'һ�����⣬ '## '�������⣬ '### '��������
- **�б�**
1. �����б�ʹ��`*`��+��-����Ϊ�б����Ŀ��ǣ���Щ�����Ƕ�����ʹ�õ�,ע��������ַ���**������һ���ո�**��
>* Candy.
>* Gum.
>* Booze.
>- Candy.
>- Gum.
>- Booze.
>+ Candy.
>+ Gum.
>+ Booze.
2. ������б�����ʹ��һ������ֽ���һ��Ӣ�ľ����Ϊ��Ŀ��ǣ�
>1. Red
>2. Green
>3. Blue 
- **Ŀ¼**
>��`[TOC]`����Ŀ¼
- **�Ӵ�** ��˫*��
>`**xxx**` **xxx**
- **����** ��'>'��ͷ
>`>`
- **б��**��*��
>`*x*` *x*
- **ɾ����** ˫������
>`~~xx~~` ~~xx~~
- **�ָ���** ����һ��������������*
>`***` 
- **�»���** ++ ��ͷ ++��β
>`++�»���++` ++�»���++
- **�������** ==��ͷ ==��β
>`==�������==` ==�������==
- **����**  ��ĩβ�û��������Ͽհף�Ȼ��س�

- **��������**
>�﷨��`[����˵��](uri)`
- **����ͼƬ**   
>�﷨: `![image](uri)` �﷨�ϺͲ�������ֻ�Ƕ��˸��� ����ͼƬ�ķ����кܶ��֣�csdn markdown�ṩ����ͼƬ���ܣ�Ҳ����ע�����ͼ������������˵����ţ������ã�û�ù�������������˵һ���Ի�·�������GitHub��ͼ������ͼƬ�ķ�����ԭ���Ӳο�[֪��](https://www.zhihu.com/question/21065229/answer/61070700?utm_medium=social&utm_source=wechat_session)   
- **�������**

> :smile: :smile_cat: 
### ���ҵ�ʵ���ٸ�ͼƬ��������ӣ�

1. ��markdown��Ҫ�õ�ͼƬ�ŵ�git�ֿ��У�������github��
2. �����ҵ�github�ֿ�https://github.com/lemonchann/cloud_image
3. ����ͼƬcloud_image/Markdown�﷨�����ʼ�1.png 
4. �� download ��ť���ڵ�ַ�����Ը���ͼƬ��ַ��������Download��ť��ֱ���Ҽ� "�������ӵ�ַ"
5. �������ӵ�ַhttps://raw.githubusercontent.com/lemonchann/cloud_image/master/Markdown%E8%AF%AD%E6%B3%95%E7%AE%80%E6%98%8E%E7%AC%94%E8%AE%B01.png
6. ��Markdown������ͼƬ
7. ������ƪ��������markdown�༭����ı༭������![Markdown�﷨�����ʼ�1](https://github.com/lemonchann/lemonchann.github.io/raw/master/images/2018-6-21-Markdown_brief_syntactic/Markdown%E8%AF%AD%E6%B3%95%E7%AE%80%E6%98%8E%E7%AC%94%E8%AE%B01.png)

  ![Markdown�﷨�����ʼ�2](https://github.com/lemonchann/lemonchann.github.io/raw/master/images/2018-6-21-Markdown_brief_syntactic/Markdown%E8%AF%AD%E6%B3%95%E7%AE%80%E6%98%8E%E7%AC%94%E8%AE%B02.png)
- **����ͼƬ2**
> ͼƬ�����������·���ķ������룬�����markdown�ļ���ͬĿ¼�µ��ļ����ļ��У������ַ������ʺ�д��ƪ��csdn��֪�����£���������д��д���˲��͡�
> �﷨ʾ����   
> `![pic](image/test.png) �� ![pic](test.png)`
- **����Ա�ر������**  ������ ` ��ͷ���������ͺ� ``` ��β���м���������
```c++
#include<iostream>
using namespace std;
class test
{
  int a;
  string str;
};
```
- **�����** ������ ` �Ѵ�������м���Ǵ���Σ�Ҳ�������ڷ�ֹmarkdown�﷨��Ч������ת�����   
>`it is code`

- **���**   

header 1 | header 2  
---|---   
row 1 col 1 | row 1 col 2  
row 2 col 1 | row 2 col 2



### �༭���Ƽ�

�Ƽ��༭��

- typora��˭��˭֪����

- vscode+markdown



### �ο�����
- [Markdown: Basics ���������ţ�](http://wowubuntu.com/markdown/basic.html)
- [Markdown�в���ͼƬ��ʲô���ɣ�](https://www.zhihu.com/question/21065229/answer/61070700?utm_medium=social&utm_source=wechat_session)

- [�����װ桿�е��Ʊʼ�Markdownָ��](http://note.youdao.com/iyoudao/?p=2445)
- [�������桿�е��Ʊʼ�Markdownָ��](http://note.youdao.com/iyoudao/?p=2411)it
