## TDD-KATA

> TDD刻意训练

## Table of Contents

- [Introduction](#introduction)
- [Dave Thomas's CodeKata](#codekata)

## Introduction
A kata, or code kata, is defined as an exercise in programming which helps hone your skills through practice and repetition. Dave Thomas [@pragdave](https://twitter.com/pragdave), started this movement for programming. This project aims to provide you with a list of some kata exercises that I've found in the Internet and the Github community. These exercises vary from general to more complex algorithms and real life situations for you to try using your preferred programming language. Remember that code katas are not quizzes or puzzles. You should not only try to 'solve' it, but find a very good solution, following best practices of the programming language you are using.

## [CodeKata](http://codekata.com/)
  - [Kata01: Supermarket Pricing](http://codekata.com/kata/kata01-supermarket-pricing/)
  - [Kata02: Karate Chop](http://codekata.com/kata/kata02-karate-chop/)
  - [Kata03: How Big? How Fast?](http://codekata.com/kata/kata03-how-big-how-fast/)
  - [Kata04: Data Munging](http://codekata.com/kata/kata04-data-munging/)
  - [Kata05: Bloom Filters](http://codekata.com/kata/kata05-bloom-filters/)
  - [Kata06: Anagrams](http://codekata.com/kata/kata06-anagrams/)
  - [Kata07: How'd I Do?](http://codekata.com/kata/kata07-howd-i-do/)
  - [Kata08: Conflicting Objectives](http://codekata.com/kata/kata08-conflicting-objectives/)
  - [Kata09: Back to the Checkout](http://codekata.com/kata/kata09-back-to-the-checkout/)
  - [Kata10: Hashes vs. Classes](http://codekata.com/kata/kata10-hashes-vs-classes/)
  - [Kata11: Sorting It Out](http://codekata.com/kata/kata11-sorting-it-out/)
  - [Kata12: Best Sellers](http://codekata.com/kata/kata12-best-sellers/)
  - [Kata13: Counting Code Lines](http://codekata.com/kata/kata13-counting-code-lines/)
  - [Kata14: Tom Swift Under the Milkwood](http://codekata.com/kata/kata14-tom-swift-under-the-milkwood/)
  - [Kata15: A Diversion](http://codekata.com/kata/kata15-a-diversion/)
  - [Kata16: Business Rules](http://codekata.com/kata/kata16-business-rules/)
  - [Kata17: More Business Rules](http://codekata.com/kata/kata17-more-business-rules/)
  - [Kata18: Transitive Dependencies](http://codekata.com/kata/kata18-transitive-dependencies/)
  - [Kata19: Word Chains](http://codekata.com/kata/kata19-word-chains/)
  - [Kata20: Klondike](http://codekata.com/kata/kata20-klondike/)
  - [Kata21: Simple Lists](http://codekata.com/kata/kata21-simple-lists/)


## TDD编码方式

- 先分解任务，分离关注点
- 列Example，用实例化需求，澄清需求细节
- 写测试，只关注需求，程序的输入输出，不关心中间过程
- 写实现，不考虑别的需求，用最简单的方式满足当前这个小需求即可 • 重构，用手法消除代码里的坏味道
- 写完，手动测试一下，基本没什么问题，有问题补个用例，修复
- 转测试，小问题，补用例，修复
- 代码整洁且用例齐全，信心满满地提交。


## 实战

### 停车场
> 需求

- 停车场(Parking Lot)可以停车、取车;
- 不同的停车小哥(Parking Boy)能够依次或者按优先级(空置率、空闲车位数)在多个停车
场中停放车辆;
- 停车经理(Parking Manger)指挥多个停车小哥，也可以自己去停车。

#### 需求一：停车场(Parking Lot)可以停车、取车;

> 分解任务

- 停车
- 取车

> 测试列表

- 在一个未满的停车场停车
- 在一个满的停车场停车
- 在一个未空的停车场取车
- 在一个空的停车场取车
- 停车后再取车