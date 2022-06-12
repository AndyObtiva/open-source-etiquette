# Open-Source Etiquette
## By [Andy Maleh](https://github.com/AndyObtiva) (Author of [Glimmer](https://github.com/AndyObtiva/glimmer))

(work in progress)

All the points made in this Open-Source Etiquette are intuitively known and practiced by highly ethical and skilled software engineers.

### Everyone:

- Software engineers with less skill and experience in a certain topic must always be humble enough to defer to software engineers with more skill and experience in that topic and accept advice by them in order to enable the best work possible. After all, if newbie snowboarders encounter Shaun White on the snow mountain, they will obviously follow in his footsteps to learn the best snowboarding tricks, not the other way around. That said, deferring to a more skilled and experienced software engineer does not mean to treat them as infallible. Everyone makes mistakes, so it is OK to point out error and challenge solutions, but that must be done respectfully (in deference) and with good intentions (not out of childish spite). Also, keep in mind that two software engineers might both defer to each other regarding different topics that each is a master of. As such, it is important to be humble and honest about one's own skill and experience level in order to enable the best collaboration possible.

### Open-source project users:

- Generally, avoid asking questions about an open-source project before putting in the effort to try it yourself (unless you get stuck of course), as that is considered the lazy behavior of unskilled software engineers and actual trolls, and you might get ignored for it. Respectful software engineers always give open-source projects the benefit of the doubt and do due diligence before asking questions to avoid wasting the project author's time.
- Do not open an issue when the effort to implement a fix or a feature is very small, including documentation changes. Open a pull request instead. Remember that open-source projects are a community effort. Finding a small issue or feature that is quick to implement is your opportunity to make a contribution!
- When reporting an issue, provide a step-by-step scenario for reproducing the issue if it is easy to reproduce, and follow troubleshooting instructions that project authors might give you to help you troubleshoot the issue further.
- Never put pressure on an open-source project's author if he is unavailable or too busy as that comes across as disrespectful and might discourage them from becoming available, especially given that they offer the project as a free service. There is never a need to sweat an author's lack of availability with open-source projects. The whole point of open-source is anybody can clone the code and make future changes themselves in a fork if the project's author becomes temporarily or permanently unavailable. And, Pull Requests make it possible to eventually merge the fork back in if the author does become available again. Furthermore, this can be an opportunity to learn a new codebase and improve your software engineering skills. Do not waste it by whining about an author's lack of availability.
- Do not make promises to contribute to a project. Instead, contribute first, and then announce your contribution after you have done all the work for it. That gains you respect as a doer, not just a talker, and helps keep you motivated to contribute further given the tangible results of your finished contributions. Remember that people who make promises are a dime a dozen, and gain zero respect unless they finish work on actual contributions. In fact, making promises often puts a lot of pressure on you to try to impress the people who heard your promises, to the point that it might stall you completely from actually following up on your promises and contributing. So, avoid promises and contribute directly instead! Only then will you be recognized as a true contributor.
- Consider extracting reusable parts of your application that rely on an open-source library and either contributing back to the open-source library or making available as their own open-source libraries. It is good to give back to the open-source community.
- If you finish building a fully working application using a certain open-source library, it would be courteous to mention it to the project author so that he would advertise in a list of applications built by his open-source library that demonstrate its usefulness. That gets your application free advertisement as well.
- If your company finds a certain open-source project useful, consider hiring the project author if he is available and/or dedicating company staff for contributing to the open-source project in collaboration with the project author. That would do your company and the open-source community a lot of good.
- If you get stuck while learning a certain part of an open-source project, instead of opening issues for what potentially is an error on your part, hit up the project author on the project chat channel (e.g. Gitter or IRC). Even if the project author is busy, other users of the project might be available to answer your questions.

...6 more items to add

### Open-source project authors:

- Always make frequent small releases instead of big ones to avoid falling for the trap of getting stuck with a huge blob of features that never feel "perfect" enough to release. I know many open-source projects that died that way. Do not let yours die that way too!
- Try to make commits to incomplete open-source projects (ones that have not had version 1.0 yet) every other month at minimum, and preferably once per week. If you have more than one incomplete open-source project, make commits in no more than 3 projects at a time to ensure finishing them before moving on to others.
- If you receive an issue, evaluate if it is serious first, and if it is, do not respond or close until you do the work to fully address it (unless you add it to another issue or attribute its cause to another project). Closing the issue becomes a motivation to work on it and fully address it. Do not waste that opportunity if it is a serious issue, and definitely avoid making promises if you did not work on the issue yet. Remember that actions speak louder than words!
- Do not talk (i.e. comment or chat) too much without taking action. Make sure to only talk the talk when you also walk the walk. Think of action as the currency that makes it possible for you to talk. If you have not taken any action yet, you cannot talk. This acts as a motivation to do more in open-source projects and produce, which is the most important goal, instead of just wasting a lot of time talking or making big promises that become back-breaking to meet. Instead, take small actions that deliver small results, talk only a little bit afterwards if you want, and then take more small actions to deliver more small results. That way, you never fall for the trap of making promises so big you can never meet or that discourage you from action in the future.
- If you fail to meet a promise you made to someone or a deadline you agreed to, do not just apologize without doing anything to make up for your failure as that will come across as empty words that make matters even worse! Instead, silently work as hard and as fast as you can on finishing the promised output that you are delayed with and only respond with an apology once you have something fully finished that would redeem you.
- Always ground your open-source project in a real world application (app samples do count) to ensure you are eating your own dog food, thus understanding how software engineers truly use your project to provide more realistic support for features and tuning of the software architecture (e.g. performance, security, maintainability, etc...)
- Avoid over-engineering your open-source project by attempting to handle every case imaginable. Instead, as per the bullet point about grounding your project in real world applications, just make sure to handle every case needed in a real world scenario, and leave any future ideas till they are actually needed. When you engineer solutions for your projects, always keep the YAGNI rule in mind (Ya Ain't Gonna Need It) to filter out any unnecessary dead-code features.
- Ensure the best software architecture and software design by only keeping today's known requirements in mind and applying the YAGNI rule on future speculative requirements. Refactor your open-source project code often to always ensure it has the best structure given today's requirements.
- Always provide examples (aka samples) of how to use your open-source project. 
- Documentation is optional in an open-source project because software engineers can always read the source code directly and try out examples to understand how it works, assuming the project has well-factored code and contains examples (aka samples). However, putting the effort into providing documentation greatly increases the popularity of an open-source project, so when possible, do your best to document your open-source project.
- Never take sincere feedback defensively. Remember that if someone gives you feedback, it does not mean they think you are lacking in software engineering skills, yet it means they are interested enough in your project to do you the great favor of providing feedback that helps your project improve. Any feedback is pure gold that you must not let go to waste by rejecting, yet you should use as fuel to iron out the rough edges of your project. Rejecting feedback is always considered a sign of mediocrity. In fact, the irony is that rejecting feedback is what would tell others that you are lacking in software engineering skills, not the inverse.
- Setup a chat room for your project (e.g. [Gitter](https://gitter.im/) or IRC) to help users get instant help and provide feedback.
- If people try to waste your time by asking questions without having done any due dilligence, it is better to ignore their messages completely and close their issues right away as those people are effectively trolls and clearly do not belong to the demographic of strong software engineers that you should be targetting to begin with. So, do not waste any effort or time responding to them.

...19 more items to add
