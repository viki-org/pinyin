
# CHANGELOG

## 2.5.0 (2015-06-18)

* featute（分词）: 增加分词选项，默认不开启分词（不兼容选项）
* test(performance): 增加了性能测试。

## 2.4.4 (2015-06-08)

* Upgrade dependency nodejieba@1.0.1, fixed #41

## 2.4.3 (2015-06-08)

* Fixed #40 更新 nodejieba 依赖，修复 nodejieba 对 iojs@2.0 的支持。

## 2.4.2 (2015-05-14)

* Fixed #38 , 结巴分词的词典路径问题。

## 2.4.1 (2015-05-13)

* Fixed: #33, #37 `便宜`

## 2.4.0 (2015--05-13)

* Update 分词模块从 Segment 切换为 Jieba。fixed #36

## 2.3.3 (2014-07-29)

* Fixed #17 多音词『朝阳』

## 2.3.2 (2014-06-03)

* 由于 #15, npm@1.4.12 的 bug 导致在 npmjs.org 发布的 pinyin@2.3.0 和
  pinyin@2.3.1 shasum 值计算错误，新版 npm 无法正常安装，所以下线处理，
  并发布了 pinyin@2.3.2。

## 2.3.1 (2014-05-27)

* 更新了针对 Web 环境的拼音库，使用 3500 个常用字库。

## 2.3.0 (2014-05-15)

* 托 spm@3.x 的福，Node 和 Web 版融合到一个仓库中。hotoo/node-pinyin 即将下线。

## 2.2.1 (2014-05-24)

* Fixed: hotoo/node-pinyin#23 , extend(default, more.hasOwnProperty is not function).

## 2.2.0 (2014-02-17)

* Update: 使用全新的，较为完整的拼音库。
* Update: 部分算法有调整。

## 2.1.3 (2014-02-06)

* Fixed hotoo/node-pinyin#19, missing some words.

## 2.1.2 (2014-01-26)

* Fixed #12, 补充缺失的『楞』字拼音。

## 2.1.1 (2013-09-08)

* Fixed: 补充缺失的『特』字拼音。
* Fixed: hotoo/node-pinyin#16, 部分修复了忽略空白的问题。

## 2.0.2 (2013-08-09)

* hotoo/node-pinyin#9 新增命令行支持。 Thanks @lyuehh

## 2.1.0 (2013-07-12)

* #6 调整返回的结果集结构，非汉字部分以原始字符和原始风格返回。

  ```
  spm install hotoo/pinyin@2.1.0
  ```

### for Node

* Fix: 直接操作拼音库，影响后续的拼音转换正确性问题。
* Update: 非中文原样返回，不做任何处理。
* Add: 完善测试用例。
* Update: 其他的一些优化。