---
title: シミュレーターの操作方法
origin: https://sim.growsmethod.com/instructions
---

<!-- Instructions -->

<!-- In this simulation, you are part of a software development team at Dunsel Universal Holdings, commonly referred to by the employees as “DUH.”  -->
<!-- You’ll make decisions about which work to accept from the backlog, and make choices when unexpected events occur. -->

このシミュレーションでは、あなたはDunsel Universal Holdings（DUH）社のソフトウェア開発チームに所属している。あなたはバックログからどの項目を受け入れるかを決定し、予期しないイベントが発生したときには選択を迫られることになる。

<!-- You have ten (10) turns. 
 !-- Your score depends on how many Delivery Points your team delivers in that time. 
 !-- You deliver points based on the roll of a dice.  -->
<!-- Along the way, you’ll encounter situations based on real world experiences. Your choices will impact your ability to deliver. -->

シミュレーションは10ターンある。スコアはチームが時間内に達成したデリバリーポイントで決まる。デリバリーポイントはサイコロの目で決まる。途中で現実世界に基づいた状況に遭遇する。あなたの選択はデリバリー能力に影響を与える。

<!-- Each team should have around 5-8 people. The first thing you need to do is pick a team name. You logon to the simulation at sim.growsmethod.com using the workshop id (which we will provide) and the team name. -->

チームの人数は5〜8人である。シミュレーションにログインするには、<https://sim.growsmethod.com> に（提供された）ワークショップIDを入力する。そして、チームを選択する。

<!-- On each team, choose one person to be the score keeper, everyone else will be team members.  -->
<!-- The score keeper rolls the dice and reads out Chance cards. 
 !-- The score keeper should share their screen 
 !-- 	so that all the team members can watch.  -->
<!-- Each team member will have their own screen to peruse and accept Activity Cards, and will watch the score keeper on the shared screen. -->

各チームで1人だけ**スコアキーパー**になる人を選ぶ。その他は全員**チームメンバー**になる。
スコアキーパーはサイコロを振り、チャンスカードを読み上げる。スコアキーパーは、チームメンバー全員に見えるように画面を共有する。
チームメンバーはスコアキーパーの共有画面を見ながら、自分の画面でアクティビティカードを閲覧および受け入れる。

<!-- Turns -->
## ターン

<!-- Each turn consists of several phases: -->
各ターンはいくつかのフェーズで構成される。

![Diagram of GROWS simulation turns](/images/GameFlow.png)

```
アクティビティカードを受け入れる（バックログから選ぶ）
↓
サイコロを振る（機能を開発する）
↓
チャンスカードに答える  OR  運命の手
```

<!-- Activity cards contain value to deliver. Each Activity Card has two implementation options: one expensive, one cheap. The whole team discusses the options and collectively decides what to accept. -->
1. アクティビティカードには、提供する価値が含まれている。実装の選択肢は2つある。高価なものと安価なものだ。チーム全体で選択肢について話し合い、何を受け入れるかを決定する。
<!-- Any team member can pick an Activity Card for the team to work on. You click on the Activity Card to accept it. The selected card is instantly moved from the Activity Pool to the Accepted Activities at the top of the window. -->
2. チームメンバーは誰でも、チームが取り組むアクティビティカードを選択できる。選択するにはアクティビティカードをクリックする。選択したカードは、Activity Pool（アクティビティの貯蔵庫）から画面上部にあるAccepted Activities（受け入れたアクティビティ）に即座に移動する。
<!-- The score keeper then rolls the dice. This simulates the work the team completed, which may be from 1 to the highest number on the dice. -->
3. スコアキーパーがサイコロを振る。これは、チームが完了させた作業をシミュレートしている。
<!-- A Chance Card is dealt. Each Chance Card poses a problem, with several potential answers to choose from. The team discusses and selects the best answer. -->
4. チャンスカードが配られる。チャンスカードには問題といくつかの選択肢が書かれている。チームで話し合い、最善な答えを選択する。
<!-- Instead of a Chance Card, you might receive a Hand of Fate card. There is no opportunity to provide any answer, your Health Scores will either be affected or not depending on specific values in your Team's Health factors. -->
5. チャンスカードの代わりに、Hand of Fate（運命の手）カードが届く場合がある。こちらのカードには答えの選択肢はない。チームの健康状態の特定の値に応じて、健康スコアに影響があるか、影響がないかのいずれかになる。

<!-- Dice -->
## サイコロ

<!-- There are four kinds of dice in the game.  -->
<!-- You start off with a common, six-sided dice, known as a “d6.” As your team gets healthier, 
 !-- you can use larger dice, which means you can deliver more per turn. The four possible dice are: -->

ゲームには4種類のサイコロがある。
最初は一般的な6面のサイコロ（d6）から始まる。
チームの健康状態が上がっていくと、面の数が大きいサイコロを使えるようになる。
ターンでデリバリーできる量が増えるということだ。
サイコロの種類は6面（d6）、8面（d8）、10面（d10）、20面（d20）の4種類である。


<!-- Health -->
## 健康状態

<!-- As in the real world, your organization’s overall health is composed of several separate factors.  -->
<!-- In this simulation, your actions and decisions affect overall health in these different areas: -->

現実世界と同様、組織の健康状態はいくつかの要因で構成されている。
このシミュレーションでは、あなたの行動と決定が以下の領域に影響を与える。

<!-- Deploy Health—Ability to deliver and deploy. This is influenced by technical habits, CI/CD infrastructure, and so on. This directly affects the size dice you can roll. -->
- **デプロイの健康**―デリバリーとデプロイの能力。これは技術的習慣やCI/CDのインフラなどに影響を受ける。また、サイコロの目に直接影響を受ける。
<!-- Collaborative Health—How well the team collaborates within itself and with the rest of the organization. -->
- **コラボレーションの健康**―チームがチーム内や組織とどれだけうまくコラボレーションできているか。
<!-- Learning Environment—A measure of skill improvement. This includes personal learning habits and skill acquisition, and ability to embrace and take on novel problems. -->
- **学習環境**―スキル向上の尺度。これには、個人の学習習慣、スキルの習得、新たな問題を受け入れて取り組む能力が含まれる。
<!-- Ability to do Experiments—Ability to use Experiments to gather feedback on technical and process-oriented questions and problems. -->
- **実験能力**―実験を使用して、技術的およびプロセスの質問や問題に関するフィードバックを収集する能力。
<!-- Using Acuals over Proxies—A measure of your “Grasp of Reality,” or use of actual, high-quality data instead of low-quality proxies. -->
- **プロキシよりも現実を使用**―「現実を把握する」尺度。低品質のプロキシの代わりに、実際の高品質なデータを使用する。
<!-- User Health—End user/customer happiness and satisfaction. -->
- **ユーザーの健康**―エンドユーザーや顧客の幸福と満足。
<!-- Team Health—Team member happiness and satisfaction. -->
- **チームの健康**―チームメンバーの幸福と満足。
<!-- Executive Health—Executive and other leadership happiness and satisfaction. -->
- **経営者の健康**―経営者およびその他のリーダーの幸福と満足。

<!-- Again, Hand of Fate cards may be disastrous or not affect your team at all depending on specific health values. -->
繰り返しになるが、Hand of Fate（運命の手）カードは、チームの健康状態の特定の値に応じて、健康スコアに影響があるか、影響がないかのいずれかになる。

<!-- Video Walkthrough -->
## 動画による解説

<!-- Please watch the following walkthough to get a better sense of how to play the simulation: -->
シミュレーションのプレイ方法をよりよく理解するには、以下の動画を見てほしい。

<https://growsmethod.com/videos/GrowsWalkthrough.mp4>

<!-- Good luck! -->
幸運を！

<!-- ©2021-2023 The GROWS Method® Institute. All Rights Reserved. Unauthorized reproduction prohibited. -->
