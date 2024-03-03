# 3 Years of Programming and Lessons Learned

My programming journey began in 10th grade, fueled by my fascination with playing Clash of Clans. I started selling clan posters and team logos on a Clash of Clans Discord server. Within six months, I had earned enough money to buy a PC.

Once I had the PC, I was uncertain about how to start learning programming. I spent a lot of time on Twitch and stumbled upon a founder who coded live. I asked if I could work on the web dashboard of his product. Gradually, I moved from working on the dashboard to Android development and then to logic board programming. Within 8-10 months, I had written 5,000 lines of code.

The startup didn't succeed, but soon after, I joined [focusbear.io](http://focusbear.io) as a backend developer. Little did I know, this would be the most epic job I'd ever have. Over 1.5 years of employment, I wrote around 100,000 lines of code, worked on the backend, then moved to frontend, then to Android and iOS. The startup aimed to create an app similar to digital wellbeing but cross-platform, with features like routine scheduling. It was an insane experience.

One project I haven't mentioned yet was during my initial days at Focusbear. We aimed to create an AI-based fitness app that could count your reps using a pose detection algorithm. We also developed a special game challenge where a game character would move based on your pose, similar to Subway Surfers, but the character's movements and jumps were based on your detected movements. I worked on this for around 4-5 months, focusing on Java APIs and neural engines like TNN and NCNN. It was one of the most technically challenging and fun projects I've worked on.

## Lessons and Experiences

1. **Fearlessness**: There were features we wanted to ship for the mobile app, but we couldn't find the right way to do it. Sometimes there was no documentation or it was too verbose. For example, listing all apps installed on a phone required diving straight into the android operating system source code

2. **Move fast, break things, learn fast**: Our codebase was never stable; we were probably merging 10-15 PRs every week. The codebase grew rapidly, but the key to managing the chaos was fixing things as they broke. Unit tests and automation scripts for UI tests don't help much when you're building quickly and testing with pilot users.

3. **Hiring is hard**: There are many factors to consider when hiring engineers. I've interviewed countless people and learned to hire slowly but make decisions quickly. If they're a fit, double down; if not, communicate clearly where they are lacking.

4. **Debt is bad, technical debt is worse**: Always strive to keep technical debt as low as possible. It's inevitable that you'll need to rewrite significant components of your repository at some point, but understand that you can never eliminate it completely. It's a cycle. Every refactor lasts only up to a certain scale. Find the balance between doubling down on key features and allocating resources for refactoring.

5. **Writing code is easy, maintenance is hard**: Adding dependencies is easy; maintaining them is hard. Be careful with what you integrate.
