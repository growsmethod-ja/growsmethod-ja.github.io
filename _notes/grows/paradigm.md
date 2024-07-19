---
title: 継続的パラダイム
origin: https://growsmethod.com/grows_learning.html
---

<!-- Over the last few years, the industry has lurched toward adopting better bits and pieces of software development and deployment. Practices such as Continuous Integration and Continuous Delivery, commonly abbreviated as CI/CD, are hailed as a breakthrough in establishing consistent, reliable delivery. -->

過去数年間で、業界はより良いソフトウェアの開発とデプロイメントを採用する方向に進んでいる。継続的インテグレーション（CI）や継続的デリバリー（CD）のようなプラクティスは、一貫性と信頼性のあるデリバリーを確立する画期的なものとして称賛されている。

<!-- But CI/CD is only part of the picture, and a relatively mechanical one at that.  There are many more aspects of development that must happen continuously.  In fact, pretty much every aspect of development should happen in a continuous manner, not in an “episodic” manner. For example, we know we need CI/CD, but how about: -->

しかし、CI/CDは全体の一部にすぎない。さらには比較的「機械的」なものである。開発で継続的に行なうべきものは、他にも数多く存在する。実際、開発のほぼすべては、一度きりの「エピソード的」な方法ではなく、継続的な方法で行われるべきである。CI/CDが必要なことはわかっているが、以下についてはどうだろうか？

<!-- Continuous Experiments
 !-- Continuous Budgeting
 !-- Continuous Monitoring
 !-- Continuous Learning
 !-- Continuous Discovery
 !-- Continuous Review & Repair
 !-- Continuous Value -->
- 継続的実験
- 継続的予算策定
- 継続的監視
- 継続的学習
- 継続的発見
- 継続的レビュー＆修復
- 継続的価値

<!-- Development is hard enough as it is, how can we possibly do everything, all the time, all at once? The secret is simple. Take SmallBitesAlways. -->

開発は十分に難しい。それなのに、すべてを、常に、同時に、実行することは可能なのだろうか？
答えは簡単だ。[[常に少しずつ]]食べるのである。

<!-- GeePaw Hill (@GeePawHill@mastodon.social) phrases this as taking “Many more, much smaller steps.” (See the full write up beginning at https://www.geepawhill.org/2021/09/29/many-more-much-smaller-steps-first-sketch/). The key to taking smaller steps is to make many more of them. -->

GeePaw Hill（`@GeePawHill@mastodon.social`）は、このことを「ステップを増やせば、ステップは小さくなる」と表現している（詳細な解説は<https://www.geepawhill.org/2021/09/29/many-more-much-smaller-steps-first-sketch/>）。つまり、小さなステップを踏むには、ステップを多く踏むのである。

<!-- In the early days of the agile movement, we used the analogy of walking through a vast, pitch black cave system with only a small, weak, flashlight. You have to take small steps, literally.  Running as fast as you can through the dark is great if you don’t mind falling off a cliff into the void, slamming into a wall, tripping over a boulder, and so on. You know, the stuff we do on a project all the time. -->

アジャイルムーブメントの初期には「小さな懐中電灯だけで真っ暗な洞窟を進む」というアナロジーを使っていた。つまり、小さなステップで進む必要があるわけだ。崖から落ちたり、壁にぶつかったり、岩につまづいたりすることが気にならなければ、暗闇をすばやく駆け抜けようとしてもいい。つまり、あなたがいつもプロジェクトでやっているようなやり方だ。

<!-- In The GROWS Method®, we use Experiments to drive development and process adoption. The key to a successful experiment (and slinging code especially) is a really short feedback loop. In other words, a very small step. -->

GROWSメソッドでは、開発やプロセスの導入を進めるために実験を使用する。実験（特にコードを書くときの実験）を成功させるの鍵は、**非常に短いフィードバックループ**である。言い換えれば、非常に小さなステップである。

<!-- How small? That depends on the task. But consider these guidelines: -->

「小さな」とはどれくらいだろうか？それはタスクによって決まる。だが、以下のガイドラインを考慮するといいだろう。

<!-- Code: less than 2 hours
 !-- Feature: less than 2-3 days
 !-- Process: less than a week -->

- コード：2時間以下
- 機能：2〜3日以下
- プロセス：1週間以下

<!-- What do we mean when we say “code in less than two hours?”  We mean that you’ve broken down an assignment into steps such that you can reach each next step in about an hour or two.  That means writing the tests, writing the code, having the tests pass, and committing to trunk.  It may be small, it may not do much — yet, but it’s successful. -->

「2時間以内にコードを書く」とはどういう意味だろうか？1〜2時間で終わるステップに作業を分割するという意味である。つまり、1〜2時間でテストを書き、コードを書き、テストをパスさせ、トランクにコミットするのである。それはあまりにも小さく、何の役にも立たないものかもしれない。だが、それでいいのである。

<!-- Your goal isn’t to work faster, or produce better quality, although those will probably happen anyway. Your goal is to: -->

あなたの目標は、速く作業をすることではない。品質を高めることでもない。いずれも結果として生じるものである。あなたの本当の目標は、

<!-- Shorten your Success Horizon -->
**成功までの時間を短縮すること**

である。

<!-- This allows you pursue true Trunk-Based Development, and eliminate any long-running feature branches, which can often be disastrous.  Instead, this model lets you experience a code base that is always shippable, always working. -->

これにより、本当の意味での「トランクベースの開発」を追求できる。また、しばしば破滅を引き起こす長期間のフィーチャーブランチを排除することができる。このモデルを使えば、常に出荷可能で、常に動作するコードベースを体験できるだろう。

<!-- With that as a base, now we look at the other aspects that we must do continuously: -->
以上ことを念頭に置き、継続的に行うべき他の側面を見ていこう。

<!-- Continuous Learning
 !-- Continuous Value
 !-- Continuous Review & Repair -->
- 継続的学習
- 継続的価値
- 継続的レビュー＆修復

<!-- ## Learning -->
## 継続的学習

“In times of change, learners inherit the earth, while the learned find themselves beautifully equipped to deal with a world that no longer exists.”—Eric Hoffer

GROWS Core

The very center of GROWS cites the two most important skills a programmer needs: Learning and Communication.

Surprise! Those probably aren’t the first two that sprang to mind. You were probably thinking of math skills, or the ability to abstract, or problem solving, and so on. Those are important, but the most important skills are learning and communication.

We are learning all the time. Not just the new technology which seems to drop daily, but also learning the problem domain, the solution space, the evolving behavior of the software itself, the nature of your teammates and organization, the ever-changing competitive and possibly regulatory landscape, … the list goes on. And these are almost all moving targets, subject to rapid and often dramatic change. We have to be able to keep up.

Programming involves active learning: experimenting with tests, toy programs, and prototypes. Making mistakes, deliberate or otherwise, to learn how the system reacts and validate your understanding—your mental models that represent the system. Learning more about your user’s needs.

And as you might guess, learning goes hand-in-hand with communication. We communication all the time: with the computer and software, with team members, with sponsors and leadership, with the users.

The GROWS Method® emphasizes the importance of learning by including learning and related activities as first-class practices (which we prefer to call habits).

And unlike school or university, this learning is on-going and continuous as things change. Which means that as much we need to learn that’s brand new, we need to unlearn old, outdated concepts and facts just as readily. The flow of learning and unlearning is continuous, ever-changing and dynamic. A static mindset that applies the same old thinking, same old tools, just doesn’t cut it anymore.


## Value
While learning is continuous in the sense of it being ever-changing, we talk about Continuous Value a little differently. Continuous Value is important because it’s not batch value.

In older, traditional organizations, software may have only been delivered annually at best, or even every few years, in a massive new release. That means that the organization only sees new business value in a big batch once a year or every couple of years.

Even worse, the organization realized revenue only after the release. But the organization has to pay for developers and the needed infrastructure throughout the long development cycle. This negative cash flow continues right up until the “gold disc” is burned, duplicated and distribution can finally start. Sometime after that, the organization will eventually realize revenue.

The CHAOS studies from the Standish Group showed consistent data over many years, leading to a simple but iron-clad conclusion: more frequent releases produce greater return on investment (ROI), less risk, and greater ability to generate business value.

But to accomplish that, you need robust feedback mechanisms and a culture of exploration, discovery and learning. And that environment may be a lot harder to create than you think.

That’s where the GROWS Method® can help. The GROWS Method® emphasizes the idea of business value as a continuous stream of small events instead of a single large, high-risk, rare event.

### And Who Gets this Value?
First, your users.

A successful organization depends on the value it provides. Your goal is to enable your users with a new “superpower:” something that helps them do their jobs and meet their goals better, faster, more creatively or more efficiently.

Second, the team gets value. With robust feedback mechanisms, teams understand the difference between the users’ needs and their own understanding. As the batch size gets smaller (implying delivery happens more often), the ability to change the prior release and engineer a better starting point for the next set of work increases. Interacting with users and collaborating with team members requires vision and psychological safety. This means less time dealing with failure demand (fixing defects and reworking delivered features) and more time delivering feature demand—new features and value.

Ultimately, this all adds up to making the organization itself more valuable, with real, long-term, resilient, measurable value. Not with short-term accounting tricks that may look good on paper but cheat or damage users, teams, society, the planet, or other stakeholders.

This is the real stuff.

## Continuous Review & Repair
Taking small steps will keep you from smashing into a wall or falling into a hole, but that’s not quite enough. You need to also make sure you’re still headed in the right direction.

A traditional project retrospective, or “post-mortem,” is aptly named. It’s too late. The patient is dead. Even a bi-weekly retrospective may be too late to prevent collateral damage. Instead, you want to create an environment of Continuous Review & Repair.

We use After Action Reviews (AAR) whenever needed. It’s critical to be able to perform an AAR in a psychologically safe, blame-free environment otherwise they do not work. The goal is not blame, but learning. Learning what needs to change; what needs to be fixed or changed.

In a similar spirit, “code reviews” should never really be about the code. If you’re worried about less experienced developers making mistakes that might need code review, you should be using pair programming or ensemble (“mob”) programming instead. What we will do for a “code review” should instead be focused on a decision review.

In other words, discuss what trade-offs were made, and why, and whether that is still appropriate. The results of this discussion are worth documenting, either in the code, or in a project wiki, etc. In addition to reviewing the decisions made now, set a date in the future to revisit these decisions, to ensure that you are still headed in the right direction.

That’s the continuous part. These decisions made sense at the time, but are they still appropriate a year from now? Five?

Similarly for everything from relationships to process to code. We know we need to fix defects in code, and improve code by refactoring (which doesn’t change functionality), but the same thing needs to happen with everything else as well.

Review your relationships. Is there a defect that needs repair? What about your process? Your environment? Regularly take a look, hold an AAR if needed, and formally schedule any repairs needed.

Taken all together, we can move beyond a simple CI/CD approach and move toward an effective Continuous Paradigm.


