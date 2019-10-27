---
layout: cv
title: Stan Lo's CV
---
# Stan Lo

Ruby/Rails developer, Boxing lover, Toy maniac with a cat

<div id="webaddress">
  <a href="stan001212@gmail.com">stan001212@gmail.co</a>
| <a href="https://twitter.com/_st0012">Twitter</a>
| <a href="https://github.com/st0012">GitHub</a>
</div>


# T1 - CV
## Work experience
### Ticketsolve (2017/11 - present)
- Upgraded our 11-years old legacy application’s Rails version from 4.2 to 5.2
- Lead API development for our new  online box-office platform
	- Coordinated with multiple frontend team members as the lead API developer at the same time and delivered features on time
	- Designed consistent, easy-to-integrate API for the frontend application
	- Overcame limitations from the API framework and even contributed back: [list of PRs](https://github.com/cerebris/jsonapi-resources/pulls?q=is%3Apr+author%3Ast0012+is%3Aclosed) (closed PRs are merged into different branches of the library instead of master)
	- Developed tools to detect/fix performance regressions ahead of time to make sure we’re all covered while moving forward rapidly. Successfully caught many problematic query with small dataset and automated the workflow so it got better every time.
- Participated system operations and was responsible for major tasks
	- Updated terraform from `0.11.13` to `0.12.2`, which contains multiple breaking changes and required thoughtful ahead-of-time plans and refactoring
	- Performed Redis upgrade on multiple production stacks from `3.2` to `5.0`
- Improve productivity and workflow
	- Wrote a series of helpers for debugging, profiling…etc.
	- Automated performance optimization flow, reduced manual operations from 10 steps to 4 steps. Largely reduced the overhead of tracking performance issues.
	- Successfully reduced queries generated from some endpoints for 10~30% and in some cases reduced response time by 3x.

### Goby (2017/06 - 2017/10)
Goby is a programming language I created for fun. And yes, I did spend almost four months to work on my project full-time without any income ;-). [These](https://github.com/goby-lang/goby/graphs/contributors?from=2017-06-03&to=2017-09-30&type=c) are my commits created during this period. Some important feature of Goby are built in these few months, like
- Refactored components like virtual machine, parser..etc.
- Implemented some core classes/libs like `Range`, `Regex`, `JSON`, `Float` ..etc.
- Introduced Goby’s REPL, `igb` (interactive Goby, just like Ruby’s `irb`)

### iCook (2015/09 - 2017/05)
- Built advanced recipe searching feature on the platform.
	- Provided multiple sorting options to the recipe searching feature. Especially sorting by popularity, which then became the VIP feature of the platform. I used the document scoring feature of ES, which I then tried to contribute back to Searchkick library https://github.com/ankane/searchkick/pull/492
	- Supported grouping recipes by date. I used the date histogram functionality of ES to achieve this while the Searchkick hadn’t supported this feature. So I also contributed that back later: https://github.com/ankane/searchkick/pull/709
- Maintained a high traffic Rails application
	- Reduced average API response time by 10%. For some critical features like recipe searching, we even saw 20% of improvement.
	- Upgraded Rails from 4.1 to 5.1. I even contributed the featured we needed to Rails: https://github.com/rails/rails/pull/22825
- Managed and improved our cloud infrastructure
	- Introduced immutable infrastructure into our operation practices in order to increase product stability and deployment overhead
	- Containerized 6 applications including the main platform with Docker
	- Established new continuous delivery flow to adopt immutable infrastructure with DockerCloud and Amazon ECS
### Backer-founder (2014/07 - 2015/07)
- Was one of the core team members that joined before the company is founded.
	- Helped to build the team’s development practices like introducing TDD and CI system into the standard workflow. 
- Built different types of products:
	- [`Backme`](http://backme.tw): payment & customer management system  for crowdfunding projects
	- `Crowdtrail`: an internal data aggregation system that collects campaign data from major crowdfunding platforms like [`Kickstarter`](https://www.kickstarter.com), [`Indiegogo`](https://www.indiegogo.com)..etc.

## Conference/Meetup Talks
- 2015 Taipei.rb
  - https://www.youtube.com/watch?v=iCArCCKIkrU
- 2017 RubyKaigi: 
  - https://www.youtube.com/watch?v=GRNlTWzoC74
  - https://www.slideshare.net/LoStan/goby-and-its-compiler
- 2018 RubyConfTaiwan
  - https://www.youtube.com/watch?v=CiLlQiHPVKc&t=3s
- 2018 RubyKaigi: 
  - https://www.youtube.com/watch?v=ldqb5u4pQb0
  - https://www.slideshare.net/LoStan/what-would-your-own-version-of-ruby-look-like-rubykaigi

## Open Source Contributions

### [Goby](https://github.com/goby-lang/goby)

Goby is a toy/experimental programming language I created few years ago. It’s written in Golang while largely inspired by Ruby & Golang. 

Some stats about the project
  - Has 37 contributors
  - Has a global team with people from Poland, Taiwan, Japan, U.S., Italy and many other countries
  - Gained almost 3000 stars
  - I gave 3 talks about it at international conferences (twice at Rubykaigi and once at RubyConfTW)

### Rails
Currently I’m [ranked at 164](https://contributors.rubyonrails.org/contributors/stan-lo/commits)) in total of 5000+ contributors. I have several important code contributions, as showed below. But besides writing code, I also do a lot of [issue triaging](https://github.com/rails/rails/issues?utf8=%E2%9C%93&q=is%253Aissue+commenter%253Ast0012)) (like [this](https://github.com/rails/rails/issues/36177)) and [code reviews](https://github.com/rails/rails/pulls?q=is%3Apr+commenter%3Ast0012) (like [this](https://github.com/rails/rails/pull/36133)).

#### Major contributions (from old to recent)

- [Cacheable view for ActionMailer](https://github.com/rails/rails/pull/22825)
- [Better logging of cached partial renders in ActionView](https://github.com/rails/rails/pull/25825)
- [Add `Vary: Accept` header when using `Accept` header for response](https://github.com/rails/rails/pull/36213)


### Other projects
- [jsonapi-resources](https://github.com/cerebris/jsonapi-resources/pulls?q=is%3Apr+author%3Ast0012) - Some of my contributions are for different branches `release-0-9` so they’re marked as closed instead of merged
- [database_cleaner](https://github.com/DatabaseCleaner/database_cleaner/pull/405)
- [formtastic](https://github.com/justinfrench/formtastic/pulls?q=is%3Apr+author%3Ast0012+is%3Aclosed)
- [searchkick](https://github.com/ankane/searchkick/pulls?q=is%3Apr+author%3Ast0012+is%3Aclosed)


<!-- ### Footer

Last updated: Octobor 2019 -->


