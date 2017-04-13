**What**: [Better Code Hub](https://bettercodehub.com) - a [GitHub Integration](https://github.com/integrations/better-code-hub) provided by [Software Improvement Group SIG](https://www.sig.eu).

**When**: 21 & 22 April 2017 during [Blockgeeks Lab Hackathon](http://bglhackathon.com)

**Where**: [MaRS Discovery District, Toronto Canada](https://marsdd.com)

With Better Code Hub, you can check how good is your team's code in raport with the state of the art in software engineering. If Better Code Hub says you're compliant (✅) then it means you're performing like the top teams in the industry with regards to 10 guidelines for maintainable software. 

## The 10 guidelines

![10 guidelines](https://cdn-images-1.medium.com/max/1440/1*TS-ZTeI7sQS7dy_AlMqSXQ.png)

The guidelines are described in full in the book [“Building Maintainable Software”](http://shop.oreilly.com/product/0636920049159.do) (get your free copy during the event!)

Compliance to guidelines is derived from the Software Improvement Group's industry benchmark (8 billion lines of code in more than 180 different technologies). 

## Supported Languages

![Languages](languages.png)

## If you're on GitHub you're good to go

* Public repo? Just go to [BetterCodeHub.com](https://bettercodehub.com) and login [FREE] with your GitHub account.

* Private? Share your Github handle to get [PRO] access. Before the event: e-mail your name and personal GitHub handles to [bettercodehub@sig.eu](mailto:bettercodehub@sig.eu). During the event: go to the local Hackathon staff with the handles.

## Zero set-up time

Using Better Code Hub is easy. Head over to [bettercodehub.com](https://bettercodehub.com) and login with your GitHub account. You'll then see your repos, and you can start an analysis clicking the ▶️ button. 

* If you want Better Code Hub to run for every Push and Pull Request on your repo, click the ⚙ icon and toggle the switch:

![githubflow](https://cdn-images-1.medium.com/max/720/1*N4wz389i80UbXKnjSp_QoA.png "Activate GitHub flow")

## File exclusions

Better Code Hub analyses all the code that is in your repository. This might include all the external libraries that you use. 

First do an initial analysis of your repository, so the "Analysis configuration" option becomes available. Then you can exclude these files by making a **.bettercodehub.yml** configuration file in the root of your repository. The code that goes into this file, can be generated with the "Analysis configuration" page which contains the following widget:

![BCH Config](yml.png)

You can find this page by first clicking on the ⚙ icon and then clicking on "Analysis configuration". 

This might look like:

~~~~
exclude:
- /mylibrary/src/.*
component_depth: 1
languages:
- java
~~~~

For more details on configuration check our [configuration manual](https://bettercodehub.com/docs/configuration-manual)


## Support and PRO License 

* If needed, get support through bettercodehub@sig.eu
* Your Pro access to Better Code Hub remains valid for *6 months* after the Blockgeekslab Hackathon 2017

## Blockchain and code quality?

Because our society needs solutions that are innovative and sustainable

* [Why blockchain needs future-proof code.](https://medium.com/@jstvssr/why-blockchain-needs-future-proof-code-cb09b39175e1#.bqfmcig55)

* Has this been used in other Hackathons? Yes, [Here's a write-up.](https://medium.com/softwareimprovementgroup/how-a-hackathon-appreciates-quality-code-bd1bdb8b3479)

## Feedback on Better Code Hub

Don't hesitate to send us feedback about our platform at [bettercodehub@sig.eu](mailto://bettercodehub@sig.eu]). 

Let's build some great software 😊!

[Rob](https://github.com/robvanderleek), [Mircea](https://github.com/mcadariu) and [Michiel](https://github.com/michielcuijpers)

