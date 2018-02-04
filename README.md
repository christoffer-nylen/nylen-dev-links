# software-development-list
My favorite software development links.

**Table of Contents:**

- [Software verification](https://github.com/christoffer-nylen/exploring-software-development/blob/master/README.md#software-verification) - Quality and safety.
- [Version control](https://github.com/christoffer-nylen/exploring-software-development/blob/master/README.md#version-control) - Git happens.
- [Machine learning](https://github.com/christoffer-nylen/exploring-software-development/blob/master/README.md#machine-learning) - Buzz.
- [Visualization](https://github.com/christoffer-nylen/exploring-software-development/blob/master/README.md#visualization) - For fun mostly.
- [Programming](https://github.com/christoffer-nylen/exploring-software-development/blob/master/README.md#programming) - Coding is hard.
- [Culture](https://github.com/christoffer-nylen/exploring-software-development/blob/master/README.md#culture) - Process problems.

Rather than leaving undecided stuff out, the following rating system is used:

- **10/10: Awesome!** - Significant daily impact.

- **9/10: Very Good!** - Daily impact.

- **8/10: Good** - Useful in some situation.

- **7/10: Ok** - Fun example or nicely put explanation.

## Software verification

### Test driven development

[TDD, where did it all go wrong? (1h version)](https://vimeo.com/68375232) - Rating: 10/10

> Since Kent Beck wrote the book on TDD in 2002 a lot of words have been dedicated to the subject. But many of them propogated misunderstandings of Kent's original rules so that TDD practice bears little resemblance to Kent's original ideas. Key misunderstandings around what do I test, what is a unit test, and what is the 'public interface' have led to test suites that are brittle, hard to read, and do not support easy refactoring. In this talk we re-discover Kent's original proposition, discover where key misunderstandings occured and look at a better approach to TDD that supports sofware development instead of impeding it. Be prepared from some sacred cows to be slaughtered and fewer but better tests to be written

[TDD, where did it all go wrong? (5min version)](https://www.youtube.com/watch?v=HNjlJpuA5kQ) - Rating: 8/10

>- What is the main misunderstanding of TDD?
>- Why are some people moving away from TDD, how do you stop that?
>- What is the relationship between ATDD and TDD?
>- What architectural styles make TDD easier?

[What's in a story?](https://dannorth.net/whats-in-a-story/) - Rating: 8/10

> Behaviour-driven development is an “outside-in” methodology. It starts at the outside by identifying business outcomes, and then drills down into the feature set that will achieve those outcomes. Each feature is captured as a “story”, which defines the scope of the feature along with its acceptance criteria. This article introduces the BDD approach to defining and identifying stories and their acceptance criteria.
>
> BDD provides a structure for a story. This is not mandatory – you can use a different story format and still be doing BDD – but I am presenting it here because it has been proven to work on many projects of all shapes and sizes. At the very least, your story should contain all of the elements described in the template.

[Tests are about design](https://www.reddit.com/r/programming/comments/5hwwni/tests_are_about_design/) - Rating: 7/10

> The problem is everyone always reduces tests to one angle, they have an impact on a lot of aspects.

[How Rust is tested](https://www.reddit.com/r/programming/comments/6mftj9/how_rust_is_tested/) - Rating: 7/10

> This document then, is a catalog of all the ways we test Rust. I hope it provides insight into what it takes to deliver a production-quality programming language, a hint at the wide variety of techniques employed in software validation, and that it reinforces your confidence in Rust’s reliability.

[How SQLite Is Tested](https://www.sqlite.org/testing.html)

[Principles of Automated Testing](https://www.reddit.com/r/programming/comments/6nh362/principles_of_automated_testing/)

### Robustness testing

[Open lecture by James Bach on software testing](https://www.youtube.com/watch?v=ILkT_HV9DVU) - Rating: 8/10

> Your job as a tester is not to just numbly copy a requirement, put the word “verify” in front of it and call it a test case; it’s not simple like that! Instead you should question it and model it in you mind! Imagining it in different ways it might interact with other things. And in so doing; you’re expanding the world beyond what is written down explicitly for you. That’s a big part of your job as a tester. To make the world clear.

[Keep calm and break stuff: Software testing for beginners](https://www.emilyobyrne.com/blog/software-testing-for-beginners) - Rating: 7/10

[The art of defensive programming](https://www.reddit.com/r/programming/comments/5k9p1w/the_art_of_defensive_programming/)

[James Bach's blog](http://www.satisfice.com/blog/)

### Code review

[Effective code review with two simple rules](https://www.reddit.com/r/programming/comments/5wbfdd/effective_code_review_with_two_simple_rules/) - Rating: 10/10

> 1. Identify a problem.
> 2. Propose a solution.

>This is relatively decent life advice in general

[10 tips for better pull requests](http://blog.ploeh.dk/2015/01/15/10-tips-for-better-pull-requests/) - Rating: 9/10

> Here's a list of tips to make your Pull Request better. It isn't exhaustive, but I think it addresses some of the more important aspects of creating a good Pull Request.

[Best kept secrets of peer code review](http://smartbear.com/SmartBear/media/pdfs/best-kept-secrets-of-peer-code-review.pdf) - Rating: 7/10

[Improve software quality with software inspections](http://www.methodsandtools.com/archive/archive.php?id=29) - Rating: 7/10

[The practice of code review](https://www.reddit.com/r/programming/comments/5gakph/the_practice_of_code_review/) - Rating: 7/10

[Effective Code Reviews](https://www.reddit.com/r/programming/comments/6yw4fo/effective_code_reviews/)

### Coding rules

[A comparison of industrial coding rules](http://www.adalog.fr/publicat/coding-rules.pdf) - Rating 8/10

> AdaControl is a (free) tool whose purpose is to enforce coding standards and programming rules in Ada programs. As AdaControl is more and more widely used in the industry, we had to review many industrial coding standards, in order to write the corresponding AdaControl rules. This paper presents our experience with rules of various origins, analyzes the rules commonly encountered, and provides some lessons-learned about good and bad programming rules. 

[In-Depth: Static Code Analysis](https://www.reddit.com/r/programming/comments/37n39g/john_carmack_shares_his_experiences_with_static/) - Rating: 7/10

> It is impossible to do a true control test in software development, but I feel the success that we have had with code analysis has been clear enough that I will say plainly it is irresponsible to not use it.

[NASA's 10 coding rules for writing safety critical program](https://www.reddit.com/r/programming/comments/66pzb8/nasas_10_coding_rules_for_writing_safety_critical/)

[NASA C style guide](http://homepages.inf.ed.ac.uk/dts/pm/Papers/nasa-c-style.pdf)

[Awesome static analysis!](https://github.com/mre/awesome-static-analysis)

[Codechecker](https://github.com/Ericsson/codechecker)

[Clang static analysis toolset final](http://llvm.org/devmtg/2015-04/slides/Clang_static_analysis_toolset_final.pdf)

[Why you should really care about C/C++ static analysis](https://www.reddit.com/r/programming/comments/6luqe9/why_you_should_really_care_about_cc_static/)

### Code coverage

[Advanced coverage criteria](https://www.st.cs.uni-saarland.de/edu/testingdebugging10/slides/04-AdvancedCoverageCriteria.pdf) - Rating 8/10

> Coverage criteria serve two main purposes: To measure adequacy of existing test suites, and to guide generation of new test cases. Even though coverage is often used to measure the quality of an existing test suite, coverage is not a good measurement for this. Generally, coverage is only good at telling you which parts haven’t been covered.

There are many kinds of code coverage criteria. The link explains many of them in a short and understandable way.

### Mutation testing

[An analysis and survey of the development of mutation testing](http://crest.cs.ucl.ac.uk/fileadmin/crest/sebasepaper/JiaH10.pdf) - Rating 8/10

> Mutation Testing is a fault–based software testing technique that has been widely studied for over three decades. The literature on Mutation Testing has contributed a set of approaches, tools, developments and empirical results. This paper provides a comprehensive analysis and survey of Mutation Testing. The paper also presents the results of several development trend analyses. These analyses provide evidence that Mutation Testing techniques and tools are reaching a state of maturity and applicability, while the topic of Mutation Testing itself is the subject of increasing interest.

[Subsumption of Condition Coverage Techniques by Mutation Testing](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.25.7805) - Rating 8/10

> Condition coverage testing is a family of testing techniques that are based on the logical flow of control through a program. The condition coverage techniques include a variety of requirements, including that each statement in the program is executed and that each branch is executed. Mutation testing is a fault-based testing technique that is widely considered to be very powerful, and that imposes requirements on testing that include, and go beyond, many other techniques. In this paper, we consider the six common condition coverage techniques, and formally show that these techniques are subsumed by mutation testing, in the sense that if mutation testing is satisfied, then the condition coverage techniques are also satisfied.

[An Empirical Evaluation of Mutation Testing for Improving the Test Quality of Safety-Critical Software](http://ieeexplore.ieee.org/abstract/document/6298894/) - Rating: 8/10

> In this study, we provide an empirical evaluation of the application of mutation testing to airborne software systems which have already satisfied the coverage requirements for certification. Specifically, we apply mutation testing to safety-critical software developed using high-integrity subsets of C and Ada, identify the most effective mutant types, and analyze the root causes of failures in test cases. Our findings show how mutation testing could be effective where traditional structural coverage analysis and manual peer review have failed. They also show that several testing issues have origins beyond the test activity, and this suggests improvements to the requirements definition and coding process. Our study also examines the relationship between program characteristics and mutation survival and considers how program size can provide a means for targeting test areas most likely to have dormant faults.

> Subsets may be imposed through restrictions in coding standards or through industry best practice (e.g., MISRA C). This again reduces the legal substitutions which can be made during mutation testing.

> In some instances, a simple error in the definition of the test case has rendered the test ineffective against the majority of mutants. Given that these test-case sets met the coverage criteria, this gives us cause to question the effectiveness of the test coverage objectives (i.e., the objectives that need to be achieved for certification purposes).

> The general consensus from both sessions was that the improvements identified using mutation testing provided a level of assurance beyond that offered by manual review. Not only were unsatisfactory deficiencies identified using mutation testing, but the findings were consistently repeatable.

> The group of engineers indicated that the potential to replace manual test-case review with mutation testing offered a real benefit given sufficient evidence to support its viability.

> There was a clear correlation between the test-case sets which failed to achieve a mutation adequacy score of 100 percent and the cyclomatic complexity of the SUT. In most cases, the code items considered were not large, and so this did not necessarily mean higher overheads.

> There is insufficient data at present to suggest that mutation testing could replace manual review, but it does provide evidence to complement a review and to understand reviewer capability.

[Mutation testing - Clean coder blog](https://www.reddit.com/r/programming/comments/4nlstd/mutation_testing_clean_coder_blog/) - Rating: 8/10

> As hard-nosed as I am about TDD as a necessary discipline; if I saw a team using mutation testing to guarantee the semantic stability of a test-after suite; I would smile, and nod, and consider them to be highly professional. (I would also suggest that they work test-first in order to streamline their effort.)

[Introduction to mutation testing](https://medium.com/@_simondel/introduction-to-mutation-testing-93f613323b0a#.rdqhv14t3) - Rating: 7/10

[What the heck is mutation testing?](http://www.codeaffine.com/2015/10/05/what-the-heck-is-mutation-testing/) - Rating: 7/10

### Test frameworks

[A quick introduction to the Google C++ testing framework](https://www.ibm.com/developerworks/aix/library/au-googletestingframework.html) - Rating: 8/10

> There are many good reasons for you to use this framework. This section describes several of them.

### Formal verification

[Formal verification: The gap between perfect code and reality](https://www.reddit.com/r/programming/comments/7lv280/formal_verification_the_gap_between_perfect_code/) - Rating: 8/10

> I went into the class believing that formal verification is the future — the only solution to a world of software ridden with bugs and security issues. But after recent events and a semester of trying to apply formal methods, I’m a serious skeptic. In this post, I’ll discuss why I think formal verification has a long way to go — and why it just doesn’t work right now.

[How can you trust formally verified software?](https://media.ccc.de/v/34c3-8915-how_can_you_trust_formally_verified_software#t=1257)

### Non-functional testing

[American fuzzy lop](http://lcamtuf.coredump.cx/afl/)

![alt text](http://lcamtuf.coredump.cx/afl/afl_screen.png)

> American fuzzy lop is a security-oriented fuzzer that employs a novel type of compile-time instrumentation and genetic algorithms to automatically discover clean, interesting test cases that trigger new internal states in the targeted binary. This substantially improves the functional coverage for the fuzzed code. The compact synthesized corpora produced by the tool are also useful for seeding other, more labor- or resource-intensive testing regimes down the road.

[OSS-Fuzz - Continuous Fuzzing for Open Source Software](https://github.com/google/oss-fuzz)

## Version control

[Git happens](https://www.youtube.com/watch?v=Dv8I_kfrFWw) - Rating: 8/10

> There's a million tutorials on the internet that tell you what to type in Git, but not why! Go one level deeper: A few straightforward concepts and some pictures, and git will magically make sense.

[Pro git book](https://git-scm.com/book) - Rating: 8/10

[In what cases could `git pull` be harmful?](https://stackoverflow.com/questions/15316601/in-what-cases-could-git-pull-be-harmful) - Rating: 8/10

> The git pull command is safe so long as it only performs fast-forward merges. If git pull is configured to only do fast-forward merges and a fast-forward merge isn't possible, then Git will exit with an error. This will give you an opportunity to study the incoming commits, think about how they might affect your local commits, and decide the best course of action (merge, rebase, reset, etc.).

[Some git tips courtesy of the CIA](https://wikileaks.org/ciav7p1/cms/page_1179773.html) - Rating: 7/10

[Git cheat sheat](https://www.reddit.com/r/programming/comments/5uj9kc/git_cheat_sheet/) - Rating: 7/10

[Trunc based development](https://www.reddit.com/r/programming/comments/7eko0m/trunk_based_development/) - Rating 7/10

> A source-control branching model, where developers collaborate on code in a single branch called ‘trunk’ *, resist any pressure to create other long-lived development branches by employing documented techniques. They therefore avoid merge hell, do not break the build, and live happily ever after.

[`git push --force` and how to deal with it](https://www.reddit.com/r/programming/comments/71441f/git_push_force_and_how_to_deal_with_it/)

> In this tutorial, we will show you how to recover from an unfortunate `git push --force` quickly.

[Why github can't host the linux kernel community](https://www.reddit.com/r/programming/comments/6slsjn/why_github_cant_host_the_linux_kernel_community/)

[Spend effort on your git commits](https://www.reddit.com/r/programming/comments/6cm1af/spend_effort_on_your_git_commits/)

![alt text](https://imgs.xkcd.com/comics/git_commit.png "Spend effort on your git commits")

[Git commit messages](https://www.reddit.com/r/programming/comments/6at5uc/git_commit_messages/)

## Machine learning

[You (probably) don't need machine learning](https://www.reddit.com/r/programming/comments/5lywfy/you_probably_dont_need_machine_learning/) - Rating: 7/10

> Of particular note is the ‘cleaned-up data’ piece.  That’s huge and something that many companies forget (or ignore) when working with their data. Without proper data quality, data governance and data management processes / systems, you’ll most likely fall into the Garbage in / Garbage out trap that has befallen many data projects.

[A super simple introduction to neural networks](http://www.mattzeunert.com/2016/12/09/neural-networks-super-simple-introduction.html)

[A visual and interactive guide to the basics of neural networks](https://jalammar.github.io/visual-interactive-guide-basics-neural-networks/)

[A basic introduction to neural networks](http://pages.cs.wisc.edu/~bolo/shipyard/neural/local.html)

## Visualization

[Up and down the ladder of abstraction](https://www.reddit.com/r/programming/comments/5ef1wh/great_tutorial_on_learning_to_think_abstractly/) - Rating: 8/10

> The most powerful way to gain insight into a system is by moving between levels of abstraction. Many designers do this instinctively. But it's easy to get stuck on the ground, experiencing concrete systems with no higher-level view. It's also easy to get stuck in the clouds, working entirely with abstract equations or aggregate statistics.
>
> This interactive essay presents the ladder of abstraction, a technique for thinking explicitly about these levels, so a designer can move among them consciously and confidently.

[Five best eclipse plugins](https://mcuoneclipse.com/2012/06/25/5-best-eclipse-plugins-1-eclox-with-doxygen-graphviz-and-mscgen/)

## Programming

### Languages

[Why is Rust difficult?](https://www.reddit.com/r/programming/comments/7s36oi/why_is_rust_difficult/) - Rating: 8/10

> This is my point of view what I believe are the reasons. Also, I’ll claim this upfront ‒ I don’t consider it necessarily a bad thing for a language to be hard to learn, not when I get something in return for the investment.

> One of the problems why I found Rust hard to learn was that it looked similar to other imperative languages on one side, but introduced a lot of novel concepts. It has all these cycles, conditions, functions, like everyone else. But it also has the ownerships and traits and lifetimes. These do have its reasons, but they feel alien at first ‒ but not alien enough to completely switch mental models. But that also make the language interesting.

[The complete guide to (external) domain specific languages](https://www.reddit.com/r/programming/comments/5v3ff5/the_complete_guide_to_external_domain_specific/)

[A list of programming languages that are actively developed on GitHub.](https://www.reddit.com/r/programming/comments/5lpekw/a_list_of_programming_languages_that_are_actively/)

[Tips for self-learning programming](https://www.reddit.com/r/programming/comments/5ho5o7/tips_for_selflearning_programming/)

[Disadvantages of purely functional programming](https://www.reddit.com/r/programming/comments/5glb3f/disadvantages_of_purely_functional_programming/)

[How does one improve as an intermediate programmer?](https://www.reddit.com/r/programming/comments/5idpoq/how_does_one_improve_as_an_intermediate_programmer/)

[What is memory safety?](http://www.pl-enthusiast.net/2014/07/21/memory-safety/)

[Pointers gone wild: Memory safety and D](https://www.youtube.com/watch?v=u-g5ZVgvVrE)

> Memory safety: A concern in software development that aims to avoid software bugs that cause security vulnerabilities dealing with random-access memory (RAM) access, such as buffer overflows and dangling pointers

[Is abstraction overrated in programming?](https://www.reddit.com/r/programming/comments/7ngvcf/an_answer_to_is_abstraction_overrated_in/)

[Strongly Typed Languages Reduce Bugs by 15%](https://www.reddit.com/r/programming/comments/710yaq/strongly_typed_languages_reduce_bugs_by_15/)

[Static vs. Dynamic Languages: A Literature Review](https://www.reddit.com/r/programming/comments/6zmgn7/static_vs_dynamic_languages_a_literature_review/)

### General

[Blockchain - A Visual Demo](https://www.youtube.com/watch?v=_160oMzblY8) - Rating 8/10

> This is a very basic visual introduction to the concepts behind a blockchain. We introduce the idea of an immutable ledger using an interactive web demo.

### Embedded

[D as a Better C](https://www.reddit.com/r/programming/comments/6viswu/d_as_a_better_c/) - Rating 8/10

> D and C programs can now be mixed together in any combination, meaning existing C programs can now start taking advantage of D.

[Quantum Break: AAA Gaming With Some D Code](https://www.youtube.com/watch?v=OLFBal4Qo_k) - Rating 7/10

[An Uncharted Tech Retrospective](https://www.youtube.com/watch?v=4ZFtP8LbUYc) - Rating 7/10

> Naughty Dog programmer John "Cowboy" Bellomy stops by to talk about the tools of his trade after spending nearly a decade with Nathan Drake.

[Write your own strace and gdb](http://hondu.co/blog/write-a-strace-and-gdb)

[Introduction to strace](https://jorge.fbarr.net/2014/01/19/introduction-to-strace/)

[Writing C without the standard library](https://www.reddit.com/r/programming/comments/5fggs5/writing_c_without_the_standard_library_linux/)

[Why does calloc exist?](https://www.reddit.com/r/programming/comments/5grdc4/why_does_calloc_exist/)

[Write a shell in C](https://www.reddit.com/r/programming/comments/5gt2jr/write_a_shell_in_c/)

[How much memory is my process using?](https://www.reddit.com/r/programming/comments/5gpoo0/how_much_memory_is_my_process_using/)

[Static and dynamic libraries](https://www.reddit.com/r/programming/comments/5e4wg1/static_and_dynamic_libraries/)

[VisUAL - A highly visual ARM emulator](https://www.reddit.com/r/programming/comments/7mvjfv/visual_a_highly_visual_arm_emulator/)

[Demystifying Floating Point Precision](https://www.reddit.com/r/programming/comments/7eoe56/demystifying_floating_point_precision/)

[Meltdown And Spectre - What we know so far](https://www.youtube.com/watch?v=IPhvL3A-e6E)

### Reverse engineering

[How Metal Gear Solid V renders a frame](https://www.reddit.com/r/programming/comments/7kewco/how_metal_gear_solid_v_renders_a_frame/) - Rating: 7/10

![alt text](http://www.adriancourreges.com/img/blog/2017/mgsv/logo.jpg)

> This was a pretty amazing article even before I got to the end and realized he is not actually a developer from the MSGV team, but just a guy who reverse-engineered the process by intercepting the D3D API calls. "Oh yeah btw I had to fork ReShade with custom hooks to bypass the DLL injection detection of the game, no biggie."

[Disassembling Jak & Daxter (which has one of the best game engine ever created)](https://www.reddit.com/r/programming/comments/5nmip9/disassembling_jak_daxter_which_has_one_of_the/) - Rating: 7/10

![alt text](http://www.codersnotes.com/notes/disassembling-jak/screenshot.jpg#right#thumb "The massive world of Jak & Daxter")

> It's a hell of a thing, when you think about it. To create your own programming language, from scratch, and then write the entire game engine in it. I don't know of any other games out there that do that.

### Building

[Making build systems not suck](https://www.youtube.com/watch?v=KPi0AuVpxLI)

> The Meson build system was created from scratch with one simple goal in mind: every second spent writing build definitions is a second wasted. Meson tries to solve this problem by reliably providing all features required for modern software development with the least amount of effort. This presentation will show an overview of the ways in which developers can spend more time developing their software and less time babysitting their build configuration.

[What test engineers do at Google: Building test infrastructure](https://testing.googleblog.com/2016/11/what-test-engineers-do-at-google.html)

[Ninja, a new build system](http://neugierig.org/software/chromium/notes/2011/02/ninja.html)

> Ninja started as a hobby project by google employee Evan Martin. In this blogg, Evan tells about the problems with GNU Make when building Chromeum, that led to the invention of Ninja.

[The Ninja build system](https://ninja-build.org/manual.html)

>Where other build systems are high-level languages, Ninja aims to be an assembler.
>
>Build systems get slow when they need to make decisions. When you are in a edit-compile cycle you want it to be as fast as possible — you want the build system to do the minimum work necessary to figure out what needs to be built immediately.

[YAML sucks](https://www.reddit.com/r/programming/comments/7ctwi7/yaml_sucks/)

## Culture

### Workflow

[From wasteland to fearless machine](https://vimeo.com/191484977) - Rating: 8/10

> Expressen is the fastest growing media site in Sweden. In 2013 I joined Expressen with the goal of, together with a few others, build a new development department. This is the story of how we went from zero to 60 developers. This is the story of how we gradually went from a monolithic .NET CMS to a plethora of small applications built with Node. This is the story of how we built an agile and fearless culture.

[Building a high-performance team is everyone's job](https://www.youtube.com/watch?v=Pd7ObKc6NrY) - Rating: 8/10

[Talk of tech innovation is bullsht, shut up and get the work done!](https://www.reddit.com/r/programming/comments/5uc57m/talk_of_tech_innovation_is_bullsht_shut_up_and/) - Rating 7/10

> It's almost boring how well our process works," Torvalds said. "All the really stressful times for me have been about process. They haven't been about code. When code doesn't work, that can actually be exciting ... Process problems are a pain in the ass. You never, ever want to have process problems ... That's when people start getting really angry at each other.

[Unexpected learnings from the cia leak](https://www.reddit.com/r/programming/comments/5yatl9/unexpected_learnings_from_the_cia_leak/) - Rating: 7/10

> It’s amusing to see how, after all, under all the layers of secrecy and mystery we are all engineers facing similar challenges and using the same tools. Starting with the obvious: the CIA uses JIRA, Confluence and git. Yes, the very same tools you use every day and love/hate. But there’s much more.

[Debugging with humility](https://www.reddit.com/r/programming/comments/5j5ctv/debugging_with_humility/) - Rating: 7/10

[Why I only work remotely](https://www.reddit.com/r/programming/comments/5jlwgp/why_i_only_work_remotely/) - Rating: 7/10

[Agile must be destroyed once and for all](https://www.reddit.com/r/programming/comments/2y4dzg/agile_must_be_destroyed_once_and_for_all_erik/)

[20-Year experience of software development methodologies](https://www.reddit.com/r/programming/comments/76i979/20year_experience_of_software_development/)

![alt text](https://i2.wp.com/zwischenzugs.com/wp-content/uploads/2016/03/software-development-methods-explained-with-cars-toggl-infographic-02.jpg?resize=980%2C4298&ssl=1)

[GOTO 2015 - Space Shuttle](https://www.youtube.com/watch?v=AyrRoKN_kvg)

### Maintenance

[Short-term vs long-term perspective in software development](https://www.reddit.com/r/programming/comments/6v2caj/shortterm_vs_longterm_perspective_in_software/)

[A practical explanation of tech debt and why it can be found in most startups](https://www.reddit.com/r/programming/comments/76qm4k/a_practical_explanation_of_tech_debt_and_why_it/)

![alt text](https://cdn-images-1.medium.com/max/800/1*mOkmsSxjdGpDd1EHQqdB8Q.jpeg "Technical debt everywhere")

[Developer-driven development](https://www.reddit.com/r/programming/comments/6zem4c/developerdriven_development/)

[The Mess We're In](https://www.youtube.com/watch?v=lKXe3HUG2l4)

### Career

[The impact github is having on your software career](http://reddit.com/r/programming/comments/5vif4n/the_impact_github_is_having_on_your_software/)

[How to pay programmers less](http://reddit.com/r/programming/comments/5gtd0k/how_to_pay_programmers_less/)

[Software architect a role not a job](https://www.reddit.com/r/programming/comments/2wvgis/software_architect_a_role_not_a_job/)

[Your job is not your life: Staying competitive as a programmer](https://www.reddit.com/r/programming/comments/5ngda1/your_job_is_not_your_life_staying_competitive_as/)

[What percent of your career have you wasted?](https://www.reddit.com/r/programming/comments/5ijjgu/what_percent_of_your_career_have_you_wasted/)

[A curated awesome list of lists of interview questions](https://www.reddit.com/r/programming/comments/5fp3u8/a_curated_awesome_list_of_lists_of_interview/)

[From engineer to manager: Keeping your technical skills](https://www.reddit.com/r/programming/comments/62drjp/from_engineer_to_manager_keeping_your_technical/)

[Questions a developer should ask at a job interview](https://www.reddit.com/r/programming/comments/5m5tgx/questions_a_developer_should_ask_at_a_job/)

[The eight levels of programmers](https://www.reddit.com/r/java/comments/12kcid/the_eight_levels_of_programmers/)

[What new software development managers should know](https://www.reddit.com/r/programming/comments/5n3a3y/what_new_software_development_managers_should_know/)
