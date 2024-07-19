---
title: GROWSメソッドのワークフロー
origin: https://growsmethod.com/practices/index.html
---

<!-- The GROWS Method® Workflow -->

<!-- The GROWS Method® workflow is based on a simple OODA loop–a variation of Observe, Orient, Decide, Act. -->

GROWSメソッドのワークフローはシンプルなOODAループ（Observe: 観察, Orient: 状況判断, Decide: 意思決定, Act: 行動）をベースにしている。

<!-- GROWS Development Loop -->
![GROWS開発ループ](/images/DevLoop.png)

```
「GROWS開発ループ」

継続的なレビュー

フィードバックの評価 → 出口
↓ データ
発見
- 「要求」
- 対話
- 共有学習
↓ 理解
TODOリスト
↓ WTF
DevOps
- CI/CD/CM
- デプロイ
↓ プロダクト
```

<!-- I. Observe: Observe Intently -->
## I. 観察：しっかりと観察する

<!-- You might consider this first step in the loop 
 !-- 	to be your chance to gather feedback. 
 !-- At this step, you gather the latest data, however informally, on how the team performed last time, how is the company doing, how much technical debt is there, and so on. -->

ループの最初のステップは、フィードバックを収集するチャンスである。
非公式で構わないので、チームのパフォーマンス、会社の業績、技術的負債の量などの最新のデータを収集する。

<!-- The first time through the loop for this development cycle, 
 !-- you may need to take a very broad approach and gather data from many levels, including: -->

開発サイクルの最初のループでは、以下のようなさまざまなレベルからデータを収集する必要がある。

<!-- Individual
 !-- Team
 !-- Practice
 !-- Company
 !-- Competition
 !-- Customer -->

- 個人
- チーム
- プラクティス
- 会社
- 競合他社
- 顧客

<!-- Outcome: Available Data -->
**アウトカム: 利用可能なデータ**

<!-- II. Orient: Build the Picture -->
## II. 状況判断：イメージを構築する

<!-- This next step is all about understanding and context building.  -->
<!-- The goal is gain clarity and get solid, team-wide comprehension.  -->
<!-- This may include further and ongoing discovery of requirements 
 !-- 	and connecting outcomes to vision, including the business goals and the overall, architectural vision of the system. -->

次のステップは、状況の理解とコンテキストの構築である。
目標となるのは、現状を明らかにして、チーム全体で知識を獲得することである。
これには、要求の発見、アウトカムとビジョン（ビジネスゴールやシステム全体のアーキテクチャのビジョンを含む）の接続なども含まれる。

<!-- It’s very important to conduct this step as a conversation:  -->
<!-- a dialog, not a monologue, and not a document.  -->
<!-- This step is about asking good questions, sharing knowledge, exploration and discovery. -->

このステップでは話しをすることが重要だ。
独り言や文書ではなく、人々との対話である。
対話によって、適切な質問をし、知識を共有し、探索し、発見するのである。

<!-- Create shared understanding -->
> 共通理解を生み出す

<!-- Of course, 
 !-- that’s easier said than done 
 !-- and our cognitive biases work against us, making harder to actually see what we need to see.  -->
<!-- So part of this step involves compensating for biases as well. -->

もちろん、これは言うは易く行うは難しである。
認知バイアスが働くため、見るべきものを見ることも難しい。
したがって、このステップにはバイアスを排除することも含まれる。

<!-- Outcome: Informed Understanding -->
**アウトカム: 十分な情報に基づいた理解**

<!-- III. Decide: Choose What to Do Next -->
## III. 意思決定：次に何をするかを選択する

<!-- Next, the team decides what to do—and what not to do, and creates a work queue.  -->
<!-- This could be as simple as a TODO List, 
 !-- 	or a more formal Backlog as used in some common methodologies. However, in keeping with Lean ideals, you want to minimize work-in-process (WIP). -->

次に、チームは何をするか（何をしないか）を決定し、作業キューを作成する。
作業キューはTODOリストのようなシンプルなもので済む場合もあれば、一般的な方法論で使用される正式なバックログが必要となる場合もある。
いずれにしても、リーンの理想に従い、仕掛品（WIP: work-in-process）は最小限に抑えたい。

<!-- Keep tasks small and manageable -->

> タスクを小さく管理しやすくする

<!-- The goal in this step is to decompose the selected work items (which may include more than just feature development) into very small, manageable tasks, and then prioritize them. -->

このステップの目標は、選択した作業項目（機能開発以外の場合もある）を小さく管理しやすいタスクに分解し、優先順位を付けることである。

<!-- Most tasks should be chosen so as to take between an hour and a half a day.  -->
<!-- No single task should be expected to take any longer than three (3) days as an absolute maximum. -->

タスクは1時間から半日で終わるように選択する必要がある。
ひとつのタスクにかかる時間は最大で3日を超えてはならない。

<!-- You can choose to fill up an iteration with tasks to fill the time in a Sprint (as Scrum does), 
 !-- or take a more agile approach and pull tasks from the queue and deliver as you go (as in Lean/Kanban). -->

イテレーションの時間を埋めるようにタスクを積み上げるか（スクラム方式）、キューからタスクをプルして提供するアジャイルな手法（リーンやカンバン方式）にするかを選択できる。

<!-- Whether you use a “push” or “pull” model,
 !-- make tasks very small and deliverable.  -->
<!-- This helps avoid the trap of fortune-telling (i.e., “estimates”) 
 !-- and wasting time on calculating story points or other proxies.  -->
<!-- Just break the work down and do it in order. -->

「プッシュ」モデルか「プル」モデルかどうかにかかわらず、タスクは常に小さく提供可能にしておきたい。
これにより、占い（「見積り」とも言う）の罠を回避し、ストーリーポイントなどの代替品の計算のムダを排除できる。
作業を分解して、順番に実行するだけでいい。

<!-- As per the ThreeTrackAttack practice,  -->
<!-- you may have more tasks to work on other than just delivering features.  -->
<!-- Any items from the other two tracks need to be put on the queue as well. -->

[[3トラックアタック]]のプラクティスが示すように、機能を提供する以外のタスクがあるかもしれない。
他の2つのトラックの作業項目もキューに入れる必要がある。


<!-- Outcome: Priority Queue of Tasks -->
**アウトカム: 優先順位が付けられたタスクのキュー**

<!-- IV: Act: Continuous Development -->
## IV: 行動：継続的に開発する

<!-- The steps above should not take a lot of time; 
 !-- 	just long enough to feel comfortable with a basic, 
 !-- 	first-level understanding and create a task queue.  -->
<!-- Now, it’s time to act, to use the Continuous Paradigm 
 !-- 	to produce Working, Tested, Features that give the users new capabilities. -->

これまでのステップにはそれほど時間はかからない。
基本的なレベルを理解し、タスクのキューを作成するだけでいい。
それでは、行動の時間である。
[[継続的パラダイム]]を使用して、ユーザーに新しい能力を提供するWTF（working tested features: 動作するテストされた機能）を生み出そう。

<!-- The idea behind the the Continuous Paradigm is to use Continuous Integration, testing, deployment and monitoring in order to get feedback as fast as possible. -->
継続的パラダイムの背後にある考え方は、[[継続的インテグレーション]]、テスト、デプロイ、監視を使用して、できるだけ早くフィードバックを取得するというものである。

<!-- Rate of feedback is your speed limit -->
> フィードバックの頻度が制限速度になる

<!-- That means that some common practices are actually counter-productive.  -->
<!-- For instance, in a git-driven workflow,  -->
<!-- it might be common practice to use long-lived feature branches for development, 
 !-- 	with an eventual merge many days, weeks, or months later.  -->
<!-- Don’t do it.  -->
<!-- By deferring a merge,  -->
<!-- you are creating a huge opportunity for conflicts and headaches.  -->
<!-- The whole point of Continuous Development is to have everyone work on the main development branch at all times. -->

つまり、逆効果になるプラクティスもあるということだ。
たとえば、gitを使ったワークフローでは、開発用のフィーチャーブランチを作成し、数日、数週間、数ヶ月後にマージすることがある。
これはやめてほしい。
マージを遅延させると、コンフリクトや頭痛の種が生じる可能性が高い。
[[継続的開発]]の要点は、全員が常にメインのブランチで開発することである。

<!-- To do that effectively 
 !-- 	requires rock-solid automation and deployment practices, 
 !-- which are a necessary first step in any modern software organization. -->

そのためには、堅実な自動化とデプロイのプラクティスが必要になる。
これは現代のソフトウェア組織にとって必要な最初のステップである。

<!-- And as mentioned in the last step, code is not the only thing you grow.  -->
<!-- Continuous Development applies to the process itself, to individual and team skills, and ultimately organizational capability. -->

最後のステップで述べたように、成長させるのはコードだけではない。
[[継続的開発]]は、プロセス自体、個人およびチームのスキル、そして最終的には組織の能力にも適用される。

<!-- Outcomes: User Capabilities, Skill Improvement, Process Improvement -->
**アウトカム: ユーザーの能力、スキルの向上、プロセスの改善**

<!-- I. Observe: Observe Intently -->
## I. 観察：しっかりと観察する

<!-- And now we’re back to step one again, 
 !-- evaluating feedback and observing.  -->
<!-- This time through (and subsequent times through the loop), 
 !-- you have more feedback, more data to gather, from the project itself
 !-- 	that you didn’t have the first time.  -->
<!-- This might include areas such as: -->

最初のステップに戻ってきた。
フィードバックを評価し、再び観察しよう。
今回（およびその後のループ）は、初回では得られなかったフィードバックやデータがプロジェクトから得られる。
それには以下のような領域が含まれる。

<!-- Discover technical debt (e.g., via Software X-Rays) -->
<!-- Gather detailed user feedback -->
<!-- Retrospective activities -->

- 技術的負債を発見する（例: [[ソフトウェアX線]]）
- ユーザーからの詳細なフィードバックを収集する
- ふりかえり活動

<!-- It’s critical to note that as you go through the OODA/development loop, it will become apparent that changes need to made—to people, to process, to code, to architecture, to mental models and assumptions. -->

OODA開発ループを進めていくと、人々、プロセス、コード、アーキテクチャ、メンタルモデル、前提などを変更しなければならないことが明らかになる。そのことに注意することが重要である。

<!-- Make the changes that must be made -->
> 必要な変更を加えよう

<!-- Don’t live with Broken Windows, fix what’s broken as soon as you can. -->
壊れた窓を放置せず、できるだけ早く修理しよう。

<!-- Outcome: Available Data -->
**アウトカム: 利用可能なデータ**
