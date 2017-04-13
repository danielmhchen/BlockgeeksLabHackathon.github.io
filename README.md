**What**: [Better Code Hub](https://bettercodehub.com) - a [GitHub Integration](https://github.com/integrations/better-code-hub) provided by [Software Improvement Group SIG](https://www.sig.eu).

**When**: 21 & 22 April 2017 during [Blockgeeks Lab Hackathon](http://bglhackathon.com)

**Where**: [MaRS Discovery District, Toronto Canada](https://marsdd.com)

## Why look at code quality?

Because our society needs solutions that are innovative and sustainable

* Why look at the quality of Blockchain implementations? [Here's our answer.](https://medium.com/@jstvssr/why-blockchain-needs-future-proof-code-cb09b39175e1#.bqfmcig55)

* Has this been done before in the context of Hackathons? Yes, [Here's a write-up.](https://medium.com/softwareimprovementgroup/how-a-hackathon-appreciates-quality-code-bd1bdb8b3479)

## Evaluation of public or private repos ?

* Working with public repos? No registration is needed. Just goto [BetterCodeHub.com](https://bettercodehub.com) and login [FREE] with your GitHub credentials

* Working with private repository? Share your Github handle to get [PRO] access. Before the event: e-mail your name and personal GitHub handles to [bettercodehub@sig.eu](mailto:bettercodehub@sig.eu). During the event: go to the local hackathon staff and share your Github handle to get Pro access. 


## How does evaluation work?
Better Code Hub supports [16 modern programming languages](https://bettercodehub.com/docs/configuration-manual). Max repo size is 100,000 lines of code. 

Your code will be automatically evaluated for compliance with these 10 guidelines for building maintainable software: 

* Write Short Units of Code
* Write Simple Units of Code
* Write Code Once
* Keep Unit Interfaces Small
* Separate Concerns in Modules
* Couple Architecture Components Loosely
* Keep Architecture Components Balanced
* Keep Your Codebase Small
* Automate Tests
* Write Clean Code

The guidelines are described in full in the book [“Building Maintainable Software”](http://shop.oreilly.com/product/0636920049159.do) (get your free copy during the event!)


## How to setup, configure PR and exclude files?

Using Better Code Hub is easy. Head over to [bettercodehub.com](https://bettercodehub.com) and login with your GitHub account. You'll then see your repos, and you can start an analysis clicking the ▶️ button. 

* If you want Better Code Hub to run for every Push and Pull Request on your repo, click the ⚙ icon and toggle the switch:

![githubflow](https://cdn-images-1.medium.com/max/720/1*N4wz389i80UbXKnjSp_QoA.png "Activate GitHub flow")

* Exluding files via .yml

Better Code Hub analyses all the code that is in your repository. This might include all the external libraries that you use (CocoaPods are excluded by default (go heuristics!)). First do an initial analysis of your repository, so the "Analysis configuration" option becomes available. Then you can exclude these files by making a **.bettercodehub.yml** in the root of your repository. The code that goes into this file, can be generated under "Analysis configuration" under "Settings" in Better Code Hub:

![BCH Config](yml.png)

This might look like:

`exclude:`

`- /mylibrary/src/.*`

`component_depth: 1`

`languages:`

`- java`

For more details on configuration check our [configuration manual](https://bettercodehub.com/docs/configuration-manual)


## Support and PRO License 

* If needed, get support through bettercodehub@sig.eu

* Your Pro access to Better Code Hub remains valid for *6 months* after the Blockgeekslab Hackathon 2017


## Feedback on Better Code Hub

Don't hesitate to send us feedback about our platform at bettercodehub@sig.eu. 

Let's build some great software 😊!

[Rob](https://github.com/robvanderleek), [Mircea](https://github.com/mcadariu) and [Michiel](https://github.com/michielcuijpers)

