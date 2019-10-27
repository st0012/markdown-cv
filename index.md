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

## Awards

`2012`
President, *Royal Society*, London, UK

Associate, *French Academy of Science*, Paris, France



## Publications

<!-- A list is also available [online](http://scholar.google.co.uk/citations?user=LTOTl0YAAAAJ) -->

### Journals

`1669`
Newton Sir I, De analysi per æquationes numero terminorum infinitas. 

`1669`
Lectiones opticæ.

etc. etc. etc.

### Patents

`2012`
Infinitesimal calculus for solutions to physics problems, [SMBC](http://www.techdirt.com/articles/20121011/09312820678/if-patents-had-been-around-time-newton.shtml) patent 001


## Occupation

`1600`
__Royal Mint__, London

- Warden
- Minted coins

`1600`
__Lucasian professor of Mathematics__, Cambridge University



<!-- ### Footer

Last updated: May 2013 -->


