# Provenance of this copy

This is an anonymised copy of the authors' working repository, made for double-anonymous review.
It has a fresh git history. The original history, whose commit times show that each
pre-registration and amendment in `paper/PREREG-*.md` was committed before the run it governs,
will be linked after review. Commit hashes are withheld here because they would identify the
original repository. Below: every original commit, oldest first, as date (UTC) | subject.

```
2020-03-12 07:31 UTC | docs: record training branch provenance
2020-03-13 09:30 UTC | refactor(run): reduce coupling around python bin
2020-03-13 11:12 UTC | feat(scripts): extend measure test coverage for the django application b
2020-03-13 17:18 UTC | feat(scripts): wire build and push docker images into the flow
2020-03-17 07:45 UTC | refactor(scripts): simplify test flow
2020-03-17 11:59 UTC | refactor(scripts): simplify verify submission flow
2020-04-15 08:15 UTC | feat(agents): extend init behavior
2020-04-24 06:39 UTC | feat(agents): add init support
2020-04-24 08:29 UTC | refactor(agents): separate init responsibilities
2020-04-24 15:04 UTC | refactor(agents): centralize init handling
2020-04-28 06:28 UTC | refactor(agents): centralize init handling
2020-04-28 11:13 UTC | refactor(error-analysis-agent): centralize checker sub state handling
2020-04-28 12:58 UTC | refactor(error-analysis-agent): reduce coupling around init
2020-04-29 05:56 UTC | feat(error-analysis-agent): add init support
2020-04-29 11:39 UTC | refactor(error-analysis-agent): separate init responsibilities
2020-04-30 05:50 UTC | refactor(error-analysis-agent): separate init responsibilities
2020-04-30 17:48 UTC | feat(error-analysis-agent): wire init into the flow
2020-05-01 05:19 UTC | feat(agents): introduce init
2020-05-01 08:16 UTC | feat(agents): support init configuration
2020-05-01 10:56 UTC | feat(agents): add init support
2020-05-08 08:51 UTC | feat(agents): support init configuration
2020-05-08 13:02 UTC | refactor(agents): make init easier to follow
2020-05-08 16:23 UTC | feat(agents): support init configuration
2020-05-15 11:22 UTC | refactor(agents): separate init responsibilities
2020-05-15 14:03 UTC | refactor(agents): separate init responsibilities
2020-05-15 17:23 UTC | feat(agents): introduce config
2020-05-19 10:23 UTC | feat(agents): extend init behavior
2020-05-19 17:52 UTC | feat(agents): add checkpoints support
2020-05-28 11:49 UTC | feat(agents): support exists configuration
2020-06-02 12:55 UTC | feat(agents): extend init store behavior
2020-06-05 16:14 UTC | refactor(llm): centralize init handling
2020-06-10 05:24 UTC | refactor(llm): simplify generate flow
2020-06-15 09:19 UTC | feat(memory): support init configuration
2020-06-15 12:36 UTC | refactor(memory): separate init responsibilities
2020-06-17 07:43 UTC | refactor(agents): simplify init flow
2020-06-22 08:12 UTC | refactor(prompts): make init easier to follow
2020-06-23 14:16 UTC | refactor(prompts): simplify diff flow
2020-06-23 16:20 UTC | refactor(agents): make init easier to follow
2020-06-25 06:53 UTC | feat(agents): wire pre processing step into the flow
2020-06-30 06:24 UTC | feat(tools): extend init behavior
2020-07-06 15:00 UTC | refactor(tools): simplify init flow
2020-07-14 17:19 UTC | feat(utils): add init support
2020-07-17 06:09 UTC | refactor(utils): reduce coupling around clone repository
2020-07-17 18:28 UTC | refactor(utils): centralize get repo default branch handling
2020-07-18 11:24 UTC | refactor(utils): separate gather files responsibilities
2020-07-24 09:08 UTC | refactor(utils): separate load review json responsibilities
2020-08-04 09:01 UTC | refactor(utils): centralize parse response handling
2020-08-05 07:20 UTC | feat(utils): introduce generate markdown
2020-08-05 12:35 UTC | refactor(utils): make clone repo easier to follow
2020-08-05 17:47 UTC | refactor(utils): simplify save graph flow
2020-08-07 08:48 UTC | refactor(utils): reduce coupling around build retrieve graph tool
2020-08-09 07:07 UTC | refactor(core): separate message short responsibilities
2020-08-09 13:28 UTC | refactor(core): separate get responsibilities
2020-08-12 08:11 UTC | refactor(core): simplify ready flow
2020-08-12 16:08 UTC | refactor(core): simplify get flow
2020-08-14 06:44 UTC | refactor(core): separate get queryset responsibilities
2020-08-19 11:56 UTC | refactor(langgraph-client): make init easier to follow
2020-08-20 09:22 UTC | refactor(core): make get base llm usage queryset easier to follow
2020-08-28 12:04 UTC | refactor(migrations): reduce coupling around migration
2020-08-28 16:55 UTC | refactor(migrations): centralize migration handling
2020-09-01 06:26 UTC | refactor(migrations): separate migration responsibilities
2020-09-02 07:56 UTC | refactor(migrations): simplify migration flow
2020-09-02 17:50 UTC | feat(migrations): add migration support
2020-09-04 15:06 UTC | refactor(migrations): reduce coupling around migration
2020-09-07 11:46 UTC | refactor(core): simplify create user flow
2020-09-07 18:16 UTC | refactor(core): reduce coupling around has object permission
2020-09-08 09:29 UTC | refactor(core): separate my threads responsibilities
2020-09-08 12:18 UTC | feat(core): wire get queryset into the flow
2020-09-09 06:34 UTC | feat(core): support history configuration
2020-09-09 09:05 UTC | refactor(core): reduce coupling around create
2020-09-09 10:51 UTC | refactor(core): simplify generate oauth state flow
2020-09-11 08:37 UTC | refactor(core): make update thread last comment info easier to follow
2020-09-15 18:11 UTC | feat(tasks): wire process webhook event into the flow
2020-09-16 11:08 UTC | refactor(core): simplify test create user requires github id flow
2020-09-19 08:01 UTC | refactor(core): reduce coupling around get queryset
2020-09-19 13:38 UTC | feat(core): wire urls into the flow
2020-09-21 17:54 UTC | refactor(core): make get easier to follow
2020-09-29 11:01 UTC | feat(core): wire views into the flow
2020-10-05 12:39 UTC | feat(core): support github webhook configuration
2020-10-06 17:28 UTC | refactor(webhooks): make init easier to follow
2020-10-16 16:42 UTC | feat(django-backend): support init configuration
2020-10-17 13:57 UTC | refactor(django-backend): make asgi easier to follow
2020-10-17 18:03 UTC | refactor(django-backend): make debug task easier to follow
2020-10-20 12:33 UTC | refactor(django-backend): make env bool easier to follow
2020-11-03 12:02 UTC | feat(django-backend): introduce test settings
2020-11-03 13:31 UTC | feat(django-backend): add urls support
2020-11-03 17:34 UTC | refactor(django-backend): reduce coupling around wsgi
2020-11-05 08:29 UTC | refactor(api): make main easier to follow
2020-11-10 09:19 UTC | feat(codecontext): support set language for file configuration
2020-11-23 13:49 UTC | feat(codecontext): support normalize query configuration
2020-11-23 17:15 UTC | feat(codecontext): add set language for file support
2020-11-24 07:31 UTC | refactor(graph): make extract repo details easier to follow
2020-11-24 18:13 UTC | feat(graph): wire find file by name into the flow
2020-11-25 06:15 UTC | refactor(graph): reduce coupling around load the graph from the pkl file
2020-11-25 13:15 UTC | test(readme): verify tests behavior
2020-11-26 11:08 UTC | test(agent-runtime-exports): add regression coverage for test agents pac
2020-11-28 05:14 UTC | test(agent-runtime-utils): cover load module edge cases
2020-11-28 07:48 UTC | test(backend-api-flows): verify set up behavior
2020-12-01 06:25 UTC | test(backend-review-sources): verify set up behavior
2020-12-01 13:15 UTC | test(backend-services): verify set up behavior
2020-12-02 18:20 UTC | test(code-context-graph-loading): cover init edge cases
2020-12-10 09:24 UTC | test(diff-formatter): verify test parse and format returns text summary
2020-12-10 11:52 UTC | test(github-service): add regression coverage for init
2020-12-10 13:05 UTC | test(graph-analyzer): cover init edge cases
2020-12-14 11:13 UTC | test(langgraph-client): cover build client edge cases
2020-12-14 13:30 UTC | test(review-runtime-agents): add regression coverage for load module
2020-12-14 16:10 UTC | test(review-runtime-execution): add regression coverage for load module
2020-12-17 13:02 UTC | test(review-runtime-graph-reporting): add regression coverage for load m
2020-12-20 06:50 UTC | test(review-tasks-unit): exercise exception class failure paths
2020-12-20 08:53 UTC | test(runtime-tooling): exercise ensure stub modules failure paths
2020-12-20 17:47 UTC | test(views-compat): verify test legacy views module reexports view calla
2020-12-21 14:10 UTC | test(webhook-handler): add regression coverage for test handle event ign
2020-12-24 09:32 UTC | feat(web): extend eslint config behavior
2020-12-25 09:13 UTC | refactor(tests): make client auth test easier to follow
2020-12-29 10:37 UTC | feat(tests): introduce data modules test
2020-12-29 17:41 UTC | refactor(api): make normalize commit easier to follow
2021-01-01 08:24 UTC | feat(api): support normalize user configuration
2021-01-01 14:34 UTC | refactor(api): simplify build absolute url flow
2021-01-01 16:11 UTC | feat(api): introduce code review api
2021-01-05 10:48 UTC | refactor(api): simplify commits api flow
2021-01-05 15:13 UTC | feat(api): wire pull request api into the flow
2021-01-08 07:05 UTC | feat(api): support normalize repo configuration
2021-01-08 12:58 UTC | feat(api): support review api configuration
2021-01-08 16:20 UTC | refactor(api): simplify workflow api flow
2021-01-15 12:34 UTC | feat(web): wire wait for into the flow
2021-01-18 12:18 UTC | feat(web): support app configuration
2021-01-22 15:18 UTC | feat(tests): introduce error message test
2021-01-27 06:16 UTC | refactor(tests): reduce coupling around form input test
2021-01-28 06:07 UTC | feat(tests): support loading spinner test configuration
2021-02-05 07:19 UTC | feat(tests): introduce sidebar test
2021-02-09 15:02 UTC | feat(tests): extend submit button test behavior
2021-02-12 10:41 UTC | refactor(components): centralize error message handling
2021-02-12 14:54 UTC | refactor(components): make form checkbox easier to follow
2021-02-16 12:55 UTC | feat(components): add form input support
2021-02-22 06:50 UTC | feat(components): support loading spinner configuration
2021-02-22 12:05 UTC | feat(components): extend sidebar behavior
2021-02-25 07:15 UTC | feat(components): introduce submit button
2021-02-25 12:36 UTC | refactor(constants): centralize review report response handling
2021-03-02 14:15 UTC | refactor(tests): reduce coupling around sidebar context test
2021-03-15 12:42 UTC | feat(contexts): introduce error
2021-03-16 10:31 UTC | feat(web): wire main into the flow
2021-03-19 12:00 UTC | feat(tests): extend code review test behavior
2021-03-22 17:05 UTC | feat(tests): extend commit detail test behavior
2021-03-26 16:16 UTC | feat(tests): extend commit list test behavior
2021-03-29 10:25 UTC | feat(codereview): support error configuration
2021-03-30 07:55 UTC | feat(codereview): add commit detail support
2021-03-30 13:48 UTC | feat(codereview): support commit list configuration
2021-03-31 13:25 UTC | feat(tests): wire index test into the flow
2021-04-02 10:44 UTC | feat(dashboard): wire index into the flow
2021-04-02 13:45 UTC | refactor(tests): separate login ui test responsibilities
2021-04-05 05:46 UTC | feat(components): introduce form checkbox
2021-04-05 11:49 UTC | refactor(components): make form input easier to follow
2021-04-06 11:48 UTC | feat(components): wire login form into the flow
2021-04-12 08:56 UTC | refactor(components): reduce coupling around social login
2021-04-12 17:33 UTC | refactor(components): centralize submit button handling
2021-04-15 05:20 UTC | refactor(login): centralize login page handling
2021-04-15 13:55 UTC | feat(tests): support index test configuration
2021-04-20 10:48 UTC | feat(repooverview): wire index into the flow
2021-04-21 13:07 UTC | refactor(tests): make index test easier to follow
2021-04-28 13:52 UTC | refactor(reporegistration): reduce coupling around index
2021-04-28 16:09 UTC | feat(tests): introduce index test
2021-04-30 09:32 UTC | feat(reposettings): support index configuration
2021-04-30 16:05 UTC | feat(tests): extend index test behavior
2021-05-04 07:31 UTC | feat(repositories): support index configuration
2021-05-04 10:24 UTC | feat(tests): add index test support
2021-05-04 17:18 UTC | refactor(reviewdetail): reduce coupling around index
2021-05-12 15:05 UTC | feat(tests): extend render pull requests page behavior
2021-05-17 05:29 UTC | feat(reviews): support index configuration
2021-05-17 08:58 UTC | feat(tests): extend state test behavior
2021-05-21 06:18 UTC | feat(actions): extend auth action behavior
2021-05-26 18:30 UTC | feat(actions): extend code review action behavior
2021-05-27 05:12 UTC | refactor(actions): centralize commit action handling
2021-05-27 10:38 UTC | refactor(actions): simplify commit detail action flow
2021-05-28 05:38 UTC | refactor(actions): simplify pull request action flow
2021-05-28 12:14 UTC | feat(actions): support create repository configuration
2021-05-28 14:58 UTC | feat(slices): add auth slice support
2021-06-14 10:49 UTC | refactor(slices): separate code review slice responsibilities
2021-06-15 12:57 UTC | feat(slices): add commit detail slice support
2021-06-16 18:04 UTC | feat(slices): support commits slice configuration
2021-06-19 08:29 UTC | feat(slices): add pull requests slice support
2021-06-23 05:11 UTC | refactor(slices): make repo slice easier to follow
2021-06-23 17:01 UTC | feat(redux): introduce store
2021-06-24 07:36 UTC | test(web): exercise setup failure paths
2021-06-28 09:06 UTC | refactor(web): make vite env d easier to follow
2021-06-28 12:58 UTC | feat(web): introduce define config
2021-06-29 05:45 UTC | build(pre-commit-config): update pre commit config defaults
2021-06-29 09:20 UTC | docs(changelog): document the changelog workflow
2021-06-29 16:11 UTC | build(docker-compose): align docker compose build settings
2021-07-03 06:07 UTC | build(dockerfile): update dockerfile defaults
2021-07-03 14:18 UTC | docs(architecture): document the architecture workflow
2021-07-03 16:12 UTC | docs(endpoints): expand api documentation guidance
2021-07-08 11:03 UTC | docs(infrastructure): document the docker deployment guide workflow
2021-07-08 15:08 UTC | chore(monitoring): clean up metrics configuration
2021-07-09 07:45 UTC | docs(readme): clarify code review copilot usage
2021-07-12 13:57 UTC | docs(security): clarify security policy usage
2021-07-14 12:13 UTC | chore(agents): align docker compose project settings
2021-07-14 17:01 UTC | build(agents): align dockerfile build settings
2021-07-27 18:01 UTC | build(agents): align langgraph build settings
2021-07-29 12:57 UTC | build(agents): wire pyproject into the build
2021-08-04 17:44 UTC | docs(api): expand requirements guidance
2021-08-05 10:30 UTC | chore(graph): clean up pyproject configuration
2021-08-05 14:11 UTC | docs(graph): document the repo graph workflow
2021-08-05 16:17 UTC | docs(graph): expand requirements guidance
2021-08-10 09:10 UTC | docs(testing): clarify testing usage
2021-08-17 16:34 UTC | chore(web): align package project settings
2021-08-19 09:12 UTC | chore(web): keep tsconfig app metadata consistent
2021-08-25 11:38 UTC | build(web): wire tsconfig into the build
2021-08-27 12:33 UTC | build(web): update tsconfig node defaults
2021-08-30 06:49 UTC | feat(coveragerc): wire repr into the flow
2021-08-30 09:15 UTC | refactor(env): separate performance settings responsibilities
2021-08-30 12:34 UTC | refactor(gitignore): separate python responsibilities
2021-09-03 05:13 UTC | refactor(agents): separate dockerignore responsibilities
2021-09-03 14:07 UTC | feat(agents): wire gitignore into the flow
2021-09-07 08:54 UTC | feat(agents): support python version configuration
2021-09-09 11:37 UTC | feat(web): introduce logs
2021-09-16 12:04 UTC | feat(web): wire index into the flow
2021-09-16 16:58 UTC | refactor(web): reduce coupling around postcss config
2021-09-21 11:54 UTC | feat(public): introduce vite
2021-09-24 08:01 UTC | refactor(web): simplify app flow
2021-09-28 13:09 UTC | feat(assets): add react support
2021-09-29 07:52 UTC | refactor(web): reduce coupling around index
2021-09-30 06:30 UTC | feat(web): introduce tailwind config
2021-10-01 06:24 UTC | refactor(agents): make this file is automatically generated by poetry 2
2021-10-01 13:42 UTC | build(web): update package lock defaults
2021-10-04 09:35 UTC | perf(run): avoid repeated allocations in system exit
2021-10-04 14:06 UTC | fix(agents): guard len against partial updates
2021-10-08 17:26 UTC | refactor(agents): make initialize memory tools easier to follow
2021-10-13 11:11 UTC | fix(agents): preserve isinstance on failure
2021-10-13 16:10 UTC | refactor(prompts): separate calls responsibilities
2021-10-15 07:41 UTC | feat(agents): add repo summary node support
2021-10-15 14:12 UTC | fix(utils): correct extract file path edge cases
2021-10-19 07:59 UTC | chore(utils): clean up generate code graph configuration
2021-10-19 12:16 UTC | refactor(utils): separate enumerate responsibilities
2021-10-23 07:31 UTC | chore(utils): organize main support files
2021-11-06 08:42 UTC | fix(core): correct review info edge cases
2021-11-06 17:10 UTC | feat(core): extend post behavior
2021-11-09 07:10 UTC | fix(core): guard trigger review against empty results
2021-11-09 16:24 UTC | fix(langgraph-client): guard handle feedback against repeated requests
2021-11-10 11:45 UTC | perf(core): streamline list processing
2021-11-11 10:33 UTC | refactor(migrations): centralize 0001 initial handling
2021-11-16 11:47 UTC | fix(migrations): avoid stale state in 0003 remove thread langgraph threa
2021-11-23 07:09 UTC | perf(core): reuse intermediate str state
2021-11-23 13:07 UTC | feat(core): add has object permission support
2021-11-24 13:34 UTC | feat(core): extend trigger review behavior
2021-11-24 16:10 UTC | chore(core): organize get permissions support files
2021-11-25 09:08 UTC | chore(core): organize get queryset support files
2021-11-25 12:39 UTC | refactor(core): separate to representation responsibilities
2021-11-25 16:57 UTC | refactor(core): simplify get user repos from github flow
2021-11-30 09:18 UTC | refactor(tasks): make process pr review easier to follow
2021-12-01 09:18 UTC | perf(core): avoid repeated allocations in test regenerate webhook secret
2021-12-01 13:17 UTC | refactor(core): make response easier to follow
2021-12-08 13:31 UTC | chore(core): organize get support files
2021-12-10 11:52 UTC | fix(core): guard http response against repeated requests
2021-12-13 09:13 UTC | fix(webhooks): correct handle member edge cases
2021-12-16 09:24 UTC | fix(django-backend): avoid stale state in settings
2021-12-16 13:00 UTC | fix(codecontext): handle empty results in parse tree
2021-12-18 17:55 UTC | fix(codecontext): avoid stale state in retrieve node context
2021-12-24 06:54 UTC | fix(codecontext): handle concurrent changes in parse file
2021-12-24 16:24 UTC | fix(graph): handle missing input in main
2021-12-29 14:23 UTC | feat(graph): introduce direct dependencies of file
2021-12-30 12:14 UTC | test(agent-runtime-exports): exercise test prompt templates are non empt
2021-12-30 13:38 UTC | test(agent-runtime-utils): cover test parse and format preserves additio
2021-12-30 18:24 UTC | test(backend-api-flows): add regression coverage for authenticate
2022-01-03 09:10 UTC | test(backend-review-sources): add regression coverage for authenticate
2022-01-04 06:28 UTC | test(backend-services): add regression coverage for test get all repo co
2022-01-04 09:10 UTC | test(code-context-graph-loading): verify predecessors behavior
2022-01-04 13:05 UTC | test(diff-formatter): exercise test extract file path strips prefixes fa
2022-01-05 11:41 UTC | test(github-service): add regression coverage for test get repositories
2022-01-10 07:07 UTC | test(langgraph-client): exercise wire client failure paths
2022-01-10 12:53 UTC | test(review-runtime-agents): verify test code reviewer agent generates r
2022-01-10 16:28 UTC | test(review-runtime-execution): cover build memory module edge cases
2022-01-12 06:07 UTC | test(review-runtime-graph-reporting): verify successors behavior
2022-01-12 08:52 UTC | test(review-tasks-unit): exercise test closed pull request does not enqu
2022-01-14 05:35 UTC | test(runtime-tooling): exercise test build retrieve graph tool serialize
2022-01-26 09:09 UTC | test(webhook-handler): verify test handle pull request queues review for
2022-01-26 14:49 UTC | refactor(tests): centralize import handling
2022-01-26 16:25 UTC | fix(tests): avoid stale state in data modules test
2022-01-31 08:31 UTC | refactor(api): centralize fetch repos from api handling
2022-01-31 17:46 UTC | refactor(api): reduce coupling around fallback review payload
2022-02-12 06:06 UTC | perf(api): avoid repeated allocations in normalize pull request
2022-02-17 16:03 UTC | perf(web): reuse intermediate app state
2022-02-21 16:56 UTC | chore(components): clean up sidebar configuration
2022-02-23 08:56 UTC | refactor(constants): centralize review report response handling
2022-02-23 14:17 UTC | chore(tests): clean up wait for configuration
2022-02-25 08:14 UTC | fix(tests): preserve wait for on failure
2022-02-25 17:13 UTC | perf(tests): streamline wait for processing
2022-03-07 06:11 UTC | refactor(codereview): reduce coupling around code review
2022-03-07 14:11 UTC | refactor(codereview): simplify commit detail flow
2022-03-08 06:26 UTC | feat(codereview): add summarize history support
2022-03-08 11:07 UTC | refactor(tests): simplify index test flow
2022-03-08 13:51 UTC | refactor(dashboard): centralize index handling
2022-03-09 08:35 UTC | refactor(tests): make wait for easier to follow
2022-03-14 16:24 UTC | chore(components): align login form project settings
2022-03-16 11:14 UTC | feat(tests): wire index test into the flow
2022-03-21 16:48 UTC | feat(repooverview): extend index behavior
2022-03-25 05:30 UTC | fix(tests): avoid stale state in wait for
2022-03-25 16:35 UTC | fix(reporegistration): correct index edge cases
2022-03-31 17:58 UTC | refactor(tests): reduce coupling around wait for
2022-04-04 09:11 UTC | perf(reposettings): streamline dispatch processing
2022-04-04 13:20 UTC | refactor(tests): simplify index test flow
2022-04-04 18:19 UTC | perf(repositories): avoid repeated allocations in index
2022-04-05 06:39 UTC | feat(tests): extend wait for behavior
2022-04-09 05:26 UTC | chore(reviewdetail): clean up index configuration
2022-04-12 14:39 UTC | fix(tests): correct error edge cases
2022-04-14 08:35 UTC | refactor(reviews): separate index responsibilities
2022-04-15 10:48 UTC | feat(tests): wire state test into the flow
2022-04-18 07:57 UTC | feat(slices): wire repo slice into the flow
2022-04-18 11:08 UTC | build(agents): update docker compose defaults
2022-04-19 12:08 UTC | refactor(agents): make poetry easier to follow
2022-04-19 12:49 UTC | chore(web): clean up package lock configuration
2022-04-20 13:33 UTC | fix(agents): avoid stale state in log action
2022-04-25 08:06 UTC | fix(agents): guard repo summary node against empty results
2022-04-25 13:08 UTC | fix(prompts): handle repeated requests in calls
2022-04-26 06:24 UTC | refactor(agents): separate run syntax check responsibilities
2022-04-26 11:40 UTC | refactor(utils): centralize get structured diff handling
2022-04-28 13:31 UTC | fix(utils): correct format the html template with the data edge cases
2022-05-02 11:21 UTC | fix(core): preserve response on failure
2022-05-03 09:20 UTC | perf(langgraph-client): avoid repeated allocations in prepare input data
2022-05-05 08:10 UTC | feat(migrations): add 0001 initial support
2022-05-06 11:10 UTC | refactor(core): reduce coupling around str
2022-05-18 12:43 UTC | refactor(core): make response easier to follow
2022-05-19 05:55 UTC | feat(core): wire registered collaborators into the flow
2022-05-19 08:14 UTC | fix(core): guard create thread against repeated requests
2022-05-19 12:08 UTC | fix(core): handle boundary values in to representation
2022-05-23 06:44 UTC | refactor(core): separate get repository pull requests from github respon
2022-05-23 15:05 UTC | refactor(tasks): make exception easier to follow
2022-05-26 06:22 UTC | feat(core): extend test is assigned reviewer for thread uses reques beha
2022-05-26 11:47 UTC | perf(core): reduce work in isinstance
2022-05-27 05:22 UTC | feat(codecontext): extend extract inheritance tags behavior
2022-05-27 11:27 UTC | feat(codecontext): wire parse python like file into the flow
2022-06-02 14:21 UTC | fix(graph): handle invalid state in open
2022-06-03 08:27 UTC | feat(graph): extend variables accessed by function behavior
2022-06-04 11:37 UTC | test(backend-api-flows): verify test review feedback returns server erro
2022-06-08 14:39 UTC | test(backend-review-sources): cover test pull request trigger review ret
2022-06-13 05:21 UTC | test(backend-services): verify test get user orgs from github passes pag
2022-06-13 08:35 UTC | test(review-runtime-agents): exercise test repo summarizer builds tree a
2022-06-23 10:38 UTC | test(review-runtime-execution): cover test raises when input has no issu
2022-06-23 15:13 UTC | test(review-runtime-graph-reporting): exercise test generate code tags s
2022-06-23 16:28 UTC | test(review-tasks-unit): exercise test happy path completes review failu
2022-06-28 06:27 UTC | test(webhook-handler): cover test handle member added creates collaborat
2022-06-28 08:33 UTC | refactor(tests): centralize data modules test handling
2022-06-28 14:33 UTC | refactor(api): centralize build context route handling
2022-06-29 11:12 UTC | refactor(constants): reduce coupling around review report response
2022-06-29 16:58 UTC | feat(tests): extend wait for behavior
2022-06-30 08:34 UTC | refactor(tests): make wait for easier to follow
2022-07-06 11:30 UTC | perf(codereview): reuse intermediate code review state
2022-07-07 11:42 UTC | chore(codereview): align if project settings
2022-07-08 06:41 UTC | chore(repooverview): clean up index configuration
2022-07-08 13:56 UTC | fix(reporegistration): handle concurrent changes in index
2022-07-14 18:22 UTC | perf(tests): reduce work in index test
2022-07-15 05:37 UTC | feat(reposettings): introduce index
2022-07-15 10:52 UTC | fix(tests): correct wait for edge cases
2022-07-15 13:15 UTC | refactor(reviewdetail): make index easier to follow
2022-07-15 16:13 UTC | fix(tests): avoid stale state in index test
2022-07-18 13:56 UTC | chore(reviews): align summarize history project settings
2022-07-20 16:08 UTC | refactor(agents): centralize poetry handling
2022-07-25 06:06 UTC | chore(web): keep package lock metadata consistent
2022-07-25 10:59 UTC | feat(agents): add initialize state support
2022-07-29 12:19 UTC | fix(agents): correct run syntax check edge cases
2022-08-05 17:54 UTC | feat(prompts): support message configuration
2022-08-08 14:21 UTC | fix(agents): guard generate fix against partial updates
2022-08-08 16:55 UTC | chore(utils): organize get commit diff support files
2022-08-10 06:51 UTC | chore(utils): keep save html report metadata consistent
2022-08-10 08:27 UTC | perf(core): avoid repeated allocations in response
2022-08-22 18:03 UTC | refactor(core): make response easier to follow
2022-08-26 05:59 UTC | chore(core): organize retrieve commit by sha support files
2022-08-26 09:17 UTC | chore(core): keep submit ai rating metadata consistent
2022-08-26 11:03 UTC | perf(core): avoid repeated allocations in create
2022-08-31 08:43 UTC | refactor(core): centralize get thread state handling
2022-09-02 13:13 UTC | refactor(tasks): centralize process commit review handling
2022-09-03 05:26 UTC | fix(core): correct test user repositories view requires github toke edge
2022-09-03 08:16 UTC | fix(core): handle repeated requests in response
2022-09-03 10:48 UTC | refactor(codecontext): reduce coupling around extract tags
2022-09-06 10:40 UTC | refactor(graph): centralize unused imports handling
2022-09-07 07:05 UTC | test(backend-api-flows): verify test submit ai rating creates feedback a
2022-09-07 11:42 UTC | test(backend-review-sources): add regression coverage for test commit tr
2022-09-07 13:30 UTC | test(backend-services): verify test get all repo collaborators returns e
2022-09-15 06:33 UTC | test(review-runtime-agents): cover test long term memory agent analyzes
2022-09-15 14:10 UTC | test(review-runtime-execution): add regression coverage for test clone r
2022-09-22 10:59 UTC | test(review-runtime-graph-reporting): cover test generate review report
2022-09-27 07:39 UTC | test(review-tasks-unit): add regression coverage for test marks review f
2022-09-28 08:42 UTC | fix(tests): correct data modules test edge cases
2022-09-28 17:31 UTC | feat(constants): introduce review report response
2022-09-29 09:17 UTC | fix(codereview): correct code review edge cases
2022-09-29 10:41 UTC | chore(reposettings): clean up index configuration
2022-09-29 18:03 UTC | feat(reviewdetail): support index configuration
2022-10-03 05:56 UTC | perf(agents): avoid repeated allocations in poetry
2022-10-04 05:26 UTC | chore(web): organize package lock support files
2022-10-05 07:13 UTC | refactor(agents): separate initialize llm responsibilities
2022-10-05 17:32 UTC | fix(agents): correct generate fix edge cases
2022-10-19 06:48 UTC | perf(prompts): reuse intermediate prompts state
2022-10-19 08:36 UTC | fix(core): handle missing input in check permissions must be owner or co
2022-10-19 16:11 UTC | perf(core): reuse intermediate response state
2022-10-20 09:01 UTC | fix(core): guard get thread count against concurrent changes
2022-10-21 10:46 UTC | refactor(core): simplify get user info flow
2022-10-21 14:41 UTC | fix(tasks): handle repeated requests in if we need to fetch more detaile
2022-10-21 17:33 UTC | feat(core): extend test thread serializer filters comment data for  beha
2022-10-26 11:59 UTC | chore(codecontext): organize extract imports support files
2022-10-27 09:32 UTC | test(backend-api-flows): verify test admin user update persists changes
2022-10-27 11:56 UTC | test(review-runtime-agents): cover test error analysis summarizer and ch
2022-10-31 08:50 UTC | test(review-runtime-execution): cover test save to file writes review js
2022-10-31 18:22 UTC | fix(constants): preserve review report response on failure
2022-11-02 12:44 UTC | feat(agents): support poetry configuration
2022-11-09 06:38 UTC | build(web): wire package lock into the build
2022-11-09 11:38 UTC | fix(agents): handle invalid state in sufficiency checker
2022-11-11 07:16 UTC | fix(prompts): preserve steps on failure
2022-11-11 17:11 UTC | refactor(tasks): centralize calculate cost handling
2022-11-16 05:33 UTC | chore(core): align test is repository owner rejects non owner project se
2022-11-16 09:08 UTC | refactor(codecontext): reduce coupling around get tags
2022-11-16 17:54 UTC | test(review-runtime-agents): verify init behavior
2022-11-19 17:40 UTC | refactor(constants): separate review report response responsibilities
2022-11-22 10:33 UTC | fix(agents): handle boundary values in poetry
2022-11-22 14:50 UTC | build(web): wire package lock into the build
2022-11-25 10:38 UTC | perf(agents): streamline log memory processing
2022-12-05 16:12 UTC | refactor(prompts): separate prompts responsibilities
2022-12-08 06:59 UTC | feat(core): add test user organizations view requires token support
2022-12-09 16:05 UTC | refactor(codecontext): simplify open flow
2022-12-14 06:15 UTC | test(review-runtime-agents): cover add conditional edges edge cases
2022-12-14 17:05 UTC | feat(agents): support poetry configuration
2023-01-04 12:06 UTC | build(web): update package lock defaults
2023-01-05 10:57 UTC | chore(agents): align guardrail checker project settings
2023-01-05 16:13 UTC | refactor(core): separate test github organization serializer allows blan
2023-01-11 15:12 UTC | fix(codecontext): handle concurrent changes in 3 file class function edg
2023-01-17 08:57 UTC | test(review-runtime-agents): verify test error analysis base aggregate r
2023-01-17 13:03 UTC | feat(agents): support poetry configuration
2023-01-17 16:44 UTC | build(web): align package lock build settings
2023-01-19 15:08 UTC | refactor(agents): separate review integrator responsibilities
2023-01-23 09:33 UTC | feat(core): introduce test commit serializer representation uses conte
2023-01-23 12:18 UTC | fix(codecontext): preserve 6 function function edges from calls on failu
2023-01-25 09:00 UTC | refactor(agents): reduce coupling around poetry
2023-01-26 07:07 UTC | build(web): align package lock build settings
2023-01-26 13:35 UTC | feat(agents): extend chat responder behavior
2023-01-27 12:18 UTC | refactor(core): simplify test repository list requires authentication fl
2023-01-29 07:05 UTC | fix(codecontext): correct 8 var dependencies function variable edge case
2023-01-30 05:45 UTC | refactor(agents): reduce coupling around poetry
2023-01-30 16:57 UTC | chore(web): keep package lock metadata consistent
2023-01-31 10:39 UTC | feat(core): extend test retrieve pull request falls back to github behav
2023-01-31 13:27 UTC | refactor(codecontext): reduce coupling around get node key
2023-02-01 14:12 UTC | refactor(agents): make poetry easier to follow
2023-02-03 12:33 UTC | build(web): align package lock build settings
2023-02-08 05:18 UTC | feat(codecontext): support open configuration
2023-02-08 11:12 UTC | refactor(agents): separate poetry responsibilities
2023-02-16 16:34 UTC | chore(web): keep package lock metadata consistent
2023-02-28 07:41 UTC | refactor(codecontext): centralize find files handling
2023-03-06 07:55 UTC | refactor(agents): centralize poetry handling
2023-03-07 05:31 UTC | chore(web): clean up package lock configuration
2023-03-07 09:18 UTC | refactor(codecontext): separate open responsibilities
2023-03-07 14:21 UTC | fix(agents): preserve poetry on failure
2023-03-08 11:18 UTC | chore(web): clean up package lock configuration
2023-03-08 12:51 UTC | fix(agents): avoid stale state in poetry
2023-03-08 18:28 UTC | build(web): wire package lock into the build
2023-03-15 05:22 UTC | perf(agents): reduce work in poetry
2023-03-15 08:30 UTC | chore(web): organize package lock support files
2023-03-15 11:06 UTC | refactor(agents): simplify poetry flow
2023-03-16 07:07 UTC | chore(web): align package lock project settings
2023-03-16 16:17 UTC | fix(agents): handle concurrent changes in poetry
2023-03-17 06:50 UTC | build(web): align package lock build settings
2023-03-17 09:34 UTC | fix(agents): guard poetry against empty results
2023-03-23 17:12 UTC | chore(web): keep package lock metadata consistent
2023-03-24 06:35 UTC | fix(agents): handle repeated requests in poetry
2023-03-27 05:39 UTC | build(web): update package lock defaults
2023-03-28 08:03 UTC | feat(agents): introduce poetry
2023-03-28 11:07 UTC | chore(web): clean up package lock configuration
2023-04-03 08:50 UTC | fix(agents): correct poetry edge cases
2023-04-03 14:33 UTC | build(web): update package lock defaults
2023-04-05 08:51 UTC | feat(agents): introduce poetry
2023-04-05 14:17 UTC | chore(web): organize package lock support files
2023-04-11 09:17 UTC | feat(agents): wire poetry into the flow
2023-04-11 11:38 UTC | build(web): update package lock defaults
2023-04-13 11:32 UTC | refactor(agents): reduce coupling around poetry
2023-04-21 06:05 UTC | chore(web): organize package lock support files
2023-04-21 09:14 UTC | refactor(agents): simplify poetry flow
2023-04-25 11:11 UTC | build(web): update package lock defaults
2023-04-25 16:05 UTC | feat(agents): wire poetry into the flow
2023-04-28 06:00 UTC | build(web): align package lock build settings
2023-04-28 09:24 UTC | fix(agents): correct poetry edge cases
2023-04-28 11:18 UTC | chore(web): clean up package lock configuration
2023-05-01 06:54 UTC | refactor(agents): simplify poetry flow
2023-05-01 14:13 UTC | chore(web): align package lock project settings
2023-05-02 12:45 UTC | fix(agents): correct poetry edge cases
2023-05-02 17:51 UTC | chore(web): clean up package lock configuration
2023-05-08 16:15 UTC | refactor(agents): centralize poetry handling
2023-05-10 07:18 UTC | build(web): wire package lock into the build
2023-05-10 08:32 UTC | fix(agents): preserve poetry on failure
2023-05-11 08:40 UTC | chore(web): align package lock project settings
2023-05-11 11:38 UTC | feat(agents): wire poetry into the flow
2023-05-12 12:53 UTC | build(web): update package lock defaults
2023-05-15 07:51 UTC | fix(agents): avoid stale state in poetry
2023-05-15 10:34 UTC | chore(web): clean up package lock configuration
2023-05-16 12:15 UTC | feat(agents): support poetry configuration
2023-05-18 13:59 UTC | build(web): align package lock build settings
2023-05-20 17:54 UTC | refactor(agents): separate poetry responsibilities
2023-05-26 09:10 UTC | build(web): update package lock defaults
2023-05-31 09:10 UTC | refactor(agents): separate poetry responsibilities
2023-05-31 14:30 UTC | build(web): update package lock defaults
2023-06-01 09:29 UTC | refactor(agents): simplify poetry flow
2023-06-01 13:08 UTC | chore(web): organize package lock support files
2023-06-06 12:12 UTC | perf(agents): streamline poetry processing
2023-06-09 11:52 UTC | chore(web): clean up package lock configuration
2023-06-12 07:17 UTC | fix(agents): handle missing input in poetry
2023-06-13 12:07 UTC | build(web): update package lock defaults
2023-06-19 12:19 UTC | refactor(agents): simplify poetry flow
2023-06-21 05:42 UTC | build(web): update package lock defaults
2023-07-04 10:50 UTC | refactor(agents): reduce coupling around poetry
2023-07-08 12:08 UTC | chore(web): clean up package lock configuration
2023-07-10 06:37 UTC | feat(agents): extend poetry behavior
2023-07-12 06:25 UTC | chore(web): clean up package lock configuration
2023-07-20 09:17 UTC | fix(agents): handle boundary values in poetry
2023-07-20 12:19 UTC | build(web): update package lock defaults
2023-07-21 08:41 UTC | refactor(agents): separate poetry responsibilities
2023-07-25 13:14 UTC | build(web): update package lock defaults
2023-07-25 18:21 UTC | chore(agents): organize poetry support files
2023-07-28 05:56 UTC | build(web): wire package lock into the build
2023-08-09 06:57 UTC | chore(web): align package lock project settings
2023-08-10 07:38 UTC | chore(web): clean up package lock configuration
2023-08-10 11:45 UTC | build(web): align package lock build settings
2023-08-10 18:03 UTC | build(web): update package lock defaults
2023-08-11 13:39 UTC | chore(web): align package lock project settings
2023-08-15 16:49 UTC | chore(web): align package lock project settings
2023-08-21 05:14 UTC | build(web): wire package lock into the build
2023-08-21 08:48 UTC | build(web): wire package lock into the build
2023-08-22 05:51 UTC | build(web): align package lock build settings
2023-08-24 09:20 UTC | chore(web): clean up package lock configuration
2023-08-28 11:12 UTC | chore(web): organize package lock support files
2023-09-06 11:52 UTC | chore(web): align package lock project settings
2023-09-06 17:49 UTC | chore(web): align package lock project settings
2023-09-07 14:57 UTC | chore(web): organize package lock support files
2023-09-12 05:39 UTC | chore(web): organize package lock support files
2023-09-12 09:12 UTC | chore(web): clean up package lock configuration
2023-09-12 12:06 UTC | build(web): wire package lock into the build
2023-09-19 08:01 UTC | build(web): update package lock defaults
2023-09-25 06:49 UTC | build(web): align package lock build settings
2023-09-25 08:06 UTC | chore(web): organize package lock support files
2023-09-25 12:01 UTC | chore(web): organize package lock support files
2023-09-27 05:31 UTC | chore(web): align package lock project settings
2023-09-27 09:09 UTC | chore(web): clean up package lock configuration
2023-09-27 15:20 UTC | build(web): update package lock defaults
2023-10-04 06:23 UTC | build(web): align package lock build settings
2023-10-05 13:01 UTC | chore(web): organize package lock support files
2023-10-19 17:20 UTC | chore(web): keep package lock metadata consistent
2023-10-20 07:10 UTC | chore(web): keep package lock metadata consistent
2023-10-20 07:59 UTC | build(web): wire package lock into the build
2023-10-20 16:24 UTC | chore(web): align package lock project settings
2023-10-22 11:00 UTC | build(web): align package lock build settings
2023-10-22 17:16 UTC | chore(web): organize package lock support files
2023-10-23 05:18 UTC | build(web): align package lock build settings
2023-10-25 08:07 UTC | build(web): wire package lock into the build
2023-10-26 05:39 UTC | build(web): wire package lock into the build
2023-10-27 18:30 UTC | chore(web): clean up package lock configuration
2023-10-31 07:13 UTC | build(web): update package lock defaults
2023-11-01 08:53 UTC | chore(web): clean up package lock configuration
2023-11-01 12:40 UTC | build(web): wire package lock into the build
2023-11-06 12:50 UTC | chore(web): organize package lock support files
2023-11-08 17:17 UTC | chore(web): organize package lock support files
2023-11-09 14:54 UTC | chore(web): organize package lock support files
2023-11-14 06:56 UTC | chore(web): align package lock project settings
2023-11-14 11:09 UTC | build(web): update package lock defaults
2023-11-14 16:17 UTC | chore(web): keep package lock metadata consistent
2023-11-15 06:20 UTC | chore(web): align package lock project settings
2023-11-15 15:13 UTC | build(web): update package lock defaults
2023-11-23 13:43 UTC | chore(web): clean up package lock configuration
2023-11-27 16:10 UTC | chore: align final snapshot with main
2026-08-18 15:14 UTC | fix(webhook): make handler idempotent and verify signature before writing
2026-08-18 21:11 UTC | feat(models): add Finding table and experiment fields, harden constraints
2026-08-18 21:44 UTC | test(webhook): expect 400 rather than 500 for a malformed payload
2026-08-27 04:43 UTC | fix: make the test suite and the graph parser actually run
2026-08-27 04:47 UTC | chore: split the environment template and check it
2026-08-27 05:37 UTC | feat(retrieval): add the depth knob, the condition switch, and a token budget
2026-08-27 05:55 UTC | feat(experiments): pin the run matrix, size the effect, anchor the retriever
2026-08-27 07:31 UTC | feat(conditions): add the oracle ceiling and a dense retrieval arm
2026-08-27 07:33 UTC | feat(experiments): load the benchmark and score it per defect
2026-08-27 08:33 UTC | feat(experiments): add the provider client, the review step, and clustered metrics
2026-08-27 09:53 UTC | feat(benchmark): score against demonstrated defects, not review opinions
2026-08-27 10:56 UTC | feat(experiments): runner, sparse graphs for slow links, truncation guards
2026-08-27 11:13 UTC | fix(experiments): budget the delivered string, and choose models by measurement
2026-08-27 11:24 UTC | fix(experiments): one candidate cap for every condition
2026-08-27 17:31 UTC | fix(benchmark): review the revision the humans reviewed
2026-08-27 17:44 UTC | perf(sparse): fetch a hop's files concurrently
2026-08-27 17:54 UTC | feat(experiments): analysis and LaTeX export for a completed run
2026-08-27 18:16 UTC | feat(benchmark): state the inclusion criterion instead of skipping silently
2026-08-27 21:13 UTC | feat(run): implement condition E instead of silently duplicating A
2026-08-27 22:04 UTC | fix(analyse): report parity over the arms that compete with each other
2026-08-27 23:42 UTC | results: freeze the gpt-4o-mini run into the repository
2026-08-28 02:38 UTC | results: the null replicates on a second model family
2026-08-28 03:09 UTC | results: depth ablation shows no monotonic effect
2026-08-28 03:11 UTC | paper: draft every section from the frozen results
2026-08-28 03:11 UTC | docs: carry the plan into the repository alongside the draft
2026-08-28 10:03 UTC | fix(analyse): compute precision from unmatched findings
2026-08-28 10:23 UTC | fix(graph): resolve calls and inheritance across files
2026-08-28 10:33 UTC | feat(crossfile): generate review tasks whose defect is invisible in the diff
2026-08-28 10:39 UTC | feat(crossfile): require a production caller, and wire the benchmark into the runner
2026-08-28 11:02 UTC | data: 171 cross-file defects across 39 repositories
2026-08-28 11:11 UTC | fix(crossfile): a one-line diff makes the task free
2026-08-28 11:40 UTC | data: cross-file corpus with distractors, 189 tasks over 39 repositories
2026-08-28 11:52 UTC | fix(crossfile): honest line numbers, and score against known-harmless lines
2026-08-28 12:42 UTC | results: on a benchmark where the defect is not in the diff, context helps
2026-08-28 14:02 UTC | feat(agent): compare an agent that can search against one handed the graph
2026-08-28 18:54 UTC | docs: replace the research position, and rename the oracle honestly
2026-08-28 19:18 UTC | docs: revise the experiment after a second review found three confounds
2026-08-28 19:59 UTC | docs: density-matched controls, three encodings, and two rejected review points
2026-08-29 02:53 UTC | results: the random control kills the relevance interpretation
2026-08-29 03:05 UTC | results: the zero tool calls were behaviour, not breakage
2026-08-29 03:05 UTC | docs: record both blocking results in the plan
2026-08-29 04:24 UTC | feat(evidence): build the evidence set and the seven arms
2026-08-29 04:27 UTC | feat(structure): the runner, and arm 7 varies the evidence rather than the label
2026-08-29 08:00 UTC | results: structure adds nothing once the code is present
2026-08-29 09:00 UTC | docs: record the structure result and the manipulation check
2026-08-29 12:00 UTC | perf(evidence): cache fetched sources
2026-08-29 12:45 UTC | results: corrupted structure hurts, and only under one encoding
2026-08-29 13:30 UTC | results: correct structure never helps; wrong structure can hurt
2026-08-29 13:30 UTC | docs: the three-encoding result
2026-08-29 15:04 UTC | results: the structure null replicates; the relevance null does not
2026-08-29 15:04 UTC | docs: the two-model result, and §1.5's relevance claim withdrawn
2026-08-29 15:08 UTC | results: 100% of comments anchor inside the change; a third point outside it
2026-08-29 15:09 UTC | docs: Phase B in the plan — anchoring is total, evidence scope is not
2026-08-29 16:29 UTC | retract: "random beats graph retrieval" — the arm was not doing graph retrieval
2026-08-30 10:03 UTC | fix(retrieval): query the function, walk deep enough, rank cross-file first
2026-08-30 10:36 UTC | results: with retrieval that works, graph beats no context by 9.1 points
2026-08-30 10:47 UTC | feat(mining): real cross-file regressions from repository history
2026-08-30 19:37 UTC | data: 96 real cross-file regression candidates from 17 repositories
2026-08-30 19:58 UTC | audit: withdraw "which code does not matter"; the retrievers never separated
2026-10-01 06:33 UTC | withdraw: the generated benchmark, and rebuild it with verified evidence
2026-10-01 06:36 UTC | docs: mark withdrawn results, pre-register the re-run before data exists
2026-10-01 06:38 UTC | paper: rewrite Method and Artifact around the rebuilt benchmark
2026-10-01 06:39 UTC | paper: Related Work from the October 2026 sweep
2026-10-01 06:51 UTC | paper: Introduction and Limitations drafts; tree-listing rebuild mode
2026-10-01 07:12 UTC | analysis: strict mechanism verdict; record rubric contamination before the data
2026-10-01 07:30 UTC | analysis: blind model judge for mechanism; record the rubric's boilerplate failure before the data
2026-10-01 07:33 UTC | feat(benchmark): safe twins — the same mutation where the shown caller is robust
2026-10-01 07:45 UTC | rebuild: directory-coherent file selection; record the sampling change
2026-10-01 08:40 UTC | feat: twins, chains, noise, balanced accuracy; typed defaults; spacing distractor
2026-10-01 08:59 UTC | perf(generator): index called names per file; eleven minutes per pool becomes seconds
2026-10-01 09:10 UTC | fix(generator): tuple swap by syntax-tree spans; parse-check every mutation; strict judge validated
2026-10-01 09:40 UTC | docs: results index — withdrawn, standing, and the rebuilt-benchmark runs
2026-10-01 11:26 UTC | perf(judge): eight workers; an hour becomes minutes
2026-10-01 12:06 UTC | results: rebuilt benchmark, first three runs frozen, c-CRAB graph re-run
2026-10-01 12:12 UTC | results: llama-3.3-70b replication frozen — topology +7.6 on the judge, +14.2 on precision
2026-10-01 12:13 UTC | paper: Results draft from the frozen runs; two pending subsections marked
2026-10-01 12:13 UTC | paper: correct three Results statements against the frozen files
2026-10-01 12:15 UTC | paper: Abstract and Discussion drafts; Limitations updated for the judge, twins, corrupted arm and chains
2026-10-01 12:16 UTC | paper: authoritative-callers twin result — metadata read as accusation, not information
2026-10-01 12:18 UTC | results: controlled c-CRAB comparison — graph retrieval +13 to +15 over random, lexical and diff
2026-10-01 12:20 UTC | feat(random arm): other-files-only variant, the control the c-CRAB result needs; findings page
2026-10-01 12:33 UTC | paper/results: authoritative instruction removes the precision cost of showing the caller
2026-10-01 12:34 UTC | results: random-other-files control — graph retrieval wins by 15 points on real defects
2026-10-01 13:03 UTC | paper: reconcile numbers after review; disclose the judge family; report the foreign arm under the instruction
2026-10-01 13:05 UTC | paper/results: explanation does not trade against precision; cost per true finding
2026-10-01 13:09 UTC | paper: report both judges side by side; claims restated to what both support
2026-10-01 13:20 UTC | results: authoritative twins (143) and defects (226) on the full runs
2026-10-01 13:20 UTC | data: the rebuilt benchmark, its 150 twins and 3 chains; fourth-family judge verdicts for every run
2026-10-01 13:50 UTC | results: all twins on both models; tables and limitations updated
2026-10-01 13:56 UTC | results: deepseek twins complete; twin claim restated to what both models show
2026-10-01 13:56 UTC | paper: sync twin sentence to final table
2026-10-02 06:31 UTC | paper: related work on framing bias, matched pairs and judge bias
2026-10-02 06:34 UTC | paper: figures from frozen results; HTML/PDF builder; first assembled PDF
2026-10-02 06:35 UTC | paper: heading numbering glitch
2026-10-02 06:36 UTC | paper: figure citations and section references after renumbering
2026-10-02 06:36 UTC | paper: intro and method aligned with the runs actually performed
2026-10-02 06:38 UTC | paper: bibliography resolved from arXiv metadata; venue works cited by key
2026-10-02 06:39 UTC | paper: discussion aligned with the two-judge and twin results
2026-10-02 06:42 UTC | paper: read-through fixes — intervals, quantifiers, n's, figure captions, title
2026-10-02 06:42 UTC | paper: remove duplicated sentence
2026-10-02 06:57 UTC | paper: external review applied — partial-input and contrast-set framing, overclaims cut, c-CRAB repairs stated, pre-registration commit cited, judge disclosure, twin public-API limitation, figure order, mechanical fixes
2026-10-02 06:58 UTC | docs: what the external review leaves open, with costs
2026-10-02 07:03 UTC | prep: arm 2b (snippets, no block), blind labelling sheet and scorer, credit-dependent run script
2026-10-02 09:13 UTC | paper: second-pass fixes — judge ranges, serialisation count, figure order, abstract under 250 words
2026-10-02 09:14 UTC | paper: abstract trimmed
2026-10-02 09:15 UTC | paper: abstract at 250 words
2026-10-02 09:15 UTC | paper: abstract trimmed to 250
2026-10-02 09:15 UTC | paper: abstract 250 words
2026-10-02 10:13 UTC | paper: related-work contribution names the judge, not the failed rubric; data: third-party license notes
2026-10-02 10:33 UTC | paper: pre-registration commit cited by its hash after the history clean-up (same date and content)
2026-10-25 09:45 UTC | paper: pre-registration commit cited by its new hash after the author clean-up (same date and content)
2026-10-25 14:23 UTC | paper: c-CRAB funnel (410/339/291/219) stated, reviewer prompt presumes a defect disclosed, diff-only ceiling applied to real defects
2026-10-25 14:48 UTC | artifact: scripts/reproduce.py recomputes all 32 analyses offline (0 differ); REPRODUCE.md, CITATION.cff, .zenodo.json; analyse_ccrab.py; discussion reconciles with SWE-PRBench and AACR-Bench
2026-10-26 05:51 UTC | generator: fix five review findings (same-name imports, unsafe twins, non-neutral distractors, line-number labels, parse failures scored as answers)
2026-10-26 06:00 UTC | audit: re-check v2 with the fixed resolver, distractor and twin checks (36/229 imports unresolved, 91/650 distractors change the tree, 25/150 twins unsafe within two files)
2026-10-26 06:01 UTC | withdraw v2 structure and twin results pending v3; mark data superseded; queue v3 runs behind an explicit no-spend guard
2026-10-26 07:00 UTC | rebuild: --from-pools mode ordered after its definition; audit script takes any benchmark version
2026-10-26 07:28 UTC | generator: three more tree-neutral distractor rewrites (reverse quotes, parenthesised return and assignment) so quote changes do not dominate; distractor tests assert tree identity
2026-10-26 08:38 UTC | Add v3 defects (277) and chains, plus test-verification results for v2 defects (17 test-verified of 86)
2026-10-26 09:56 UTC | Add v3 twins (165) and the v3 instrument audit: 0 unresolved imports, 0 tree-changing distractors, 0 unsafe twins
2026-10-26 11:00 UTC | Limitations: report test-verification of generated defects (17 of 86) and rebuild the PDF
2026-10-26 11:03 UTC | Rebuild the paper PDF
2026-10-26 12:27 UTC | Metadata note describes the function-name labels, not the withdrawn stem:line form
2026-10-26 12:45 UTC | empty_to_none evidence points at the iteration, not the enclosing def; list() counts as iteration; repair the one affected v3 row; verifier takes --out
2026-10-26 12:47 UTC | Queue script: interpreter from PYTHON env, record the approved scope
2026-10-26 13:39 UTC | Normalise trailing whitespace and end-of-file newlines across the older service, web and test files
2026-10-26 13:42 UTC | Remove stale CHANGELOG, SECURITY, TESTING and docs pages; run_tests.py takes PYTHON and skips the web suite cleanly; Docker images on current 3.12/20 tags with a .dockerignore and restart policies
2026-10-26 13:44 UTC | Drop the unused pre-commit config (2021 pins, never wired into CI); tidy the coverage scope
2026-10-26 13:48 UTC | Remove unreferenced files: scratch audit scripts, stale deploy and submission scripts, Prometheus config, the v1 generator, and three unused data files (25 MB c-CRAB preprocess dump, no-distractor v1 set, raw regression mining output)
2026-10-26 14:08 UTC | v3 ceiling check: diff-only exact-line hit 95.5% on 201 defects; queue stopped under the pre-set rule
2026-10-26 14:08 UTC | v3 ceiling note: record the spend
2026-10-26 14:09 UTC | v3 ceiling note: spend figure
2026-10-26 14:49 UTC | Paper: narrow to the diagnostics (ceiling on three versions, anchor vs evidence, twins pending, test verification, c-CRAB retrieval, search trigger); withdraw the held-constant results; figures and reproduction map updated
2026-10-26 14:54 UTC | reproduce.py checks the v3 twin analyses and the stopped ceiling run's table; new figures
2026-10-27 06:20 UTC | Paper: the three questions the experiment was built for and what happened to each; precision signal from the stopped v3 run (real caller -14 points, bare link recovers nothing)
2026-10-27 07:03 UTC | v3 twins on two models (frozen + analysed); paper 4.3 and discussion filled; c-CRAB pipeline disclosures (seed from ground-truth line, tool sentence, tolerance) and the --strip-seed control for the graph condition's seed span
2026-10-27 07:04 UTC | v3 test verification: 32 test-verified, 27 not caught, 218 no verdict; reported in 4.4 and limitations
2026-10-27 07:56 UTC | Neutral-prompt twins on gpt-4o-mini: diff only leaves 82% of safe changes alone, the tolerant caller 54%, a bare link 40%, the attributed relation 11%; paper, figure 3 and docs updated
2026-10-27 09:23 UTC | Withdraw the c-CRAB graph-retrieval result: the graph condition alone carried the defect function's line span; seed-stripped control localises 34.1% vs 33.2% diff only (+0.9, spans zero). Paper, figure 2, notice, docs, PDF
2026-10-27 12:13 UTC | Neutral prompt on the 277 v3 defects, gpt-4o-mini: diff alone 30% hit, attributed link 82%, but balanced accuracy against the neutral twins never beats the diff (caller −2.4, attributed −9.6); analyser reads several files and bootstraps balanced accuracy
2026-10-27 12:53 UTC | Neutral-prompt twins on deepseek-v3.2 (three shards, 158 paired): same order as gpt-4o-mini at a tenth of the size, 89% cleared from the diff to 79% with the relation named; paper 4.3, 5 and abstract carry both neutral runs and balanced accuracy; PDF rebuilt
2026-10-27 14:33 UTC | Repair c-CRAB retrieval (step 1, code only): every condition delivers each entity's source trimmed to its line range in one payload shape; seeds come from the diff's changed hunks, never the ground truth, and carry no line range or metadata; the builder resolves attribute and method calls, dotted and relative imports, aliases, re-exports and inherited methods, and creates no phantom nodes; 19 new tests
2026-10-27 16:01 UTC | c-CRAB retrieval: the model text carries neither the condition letter nor the budget block (both logged per call in raw.jsonl); experiments/validate_graph.py checks caller recall and precision of the old and new builders against jedi find-references on repositories outside the task set
2026-10-27 19:01 UTC | Graph validation against jedi find-references on six repositories outside the c-CRAB task set: pooled caller recall 0.40 -> 0.92, precision 0.89 -> 0.85, phantom function nodes 805 -> 0
2026-10-27 19:08 UTC | Pre-register the c-CRAB retrieval rerun after the repair (PLAN.md section 10): A, B, C, Cx, D with code payloads and diff-derived seeds, 3,000 tokens for every condition, tolerance 5 and 0, gpt-4o-mini, primary B minus Cx with the paired repository bootstrap, $3 stop rule, reported whatever it is; analyse_ccrab.py takes a directory, header and exact-line flag
2026-10-27 20:03 UTC | Sparse collector requests only paths the repository's tree listing contains (one API call per task, cached, waits on the quota): same files, none of the ~480 misses per task on this link; PLAN.md amendment recorded before the restart
2026-10-28 00:30 UTC | Sparse collector: per-fetch tracing on SPARSE_DEBUG=1 (path, status, seconds), no behaviour change
2026-10-28 15:16 UTC | c-CRAB pre-registered rerun (PLAN.md s10): raw records, outcomes and analysis; B does not beat Cx or A
2026-10-29 05:35 UTC | Pre-register the numbered-diff rerun (PLAN s10 amendment); chance baseline, line accuracy and signal detection on existing records; reasoning passthrough in the client
2026-10-29 06:54 UTC | c-CRAB numbered-diff rerun: records, analyses, chance baseline, line accuracy, hand-label sample
2026-10-29 06:54 UTC | ccrab-numbered README: mean findings from the records
2026-10-29 07:18 UTC | gemini-2.5-flash partial runs (key cap at $5 stopped them): c-CRAB A/B on 60 tasks, v3 neutral 80 defects + 80 twins, with chance baseline and d'/c
2026-10-29 07:41 UTC | Pre-register the final c-CRAB run (PLAN s11): plain code-block context, callers-first walk without test files, class-seed rule, delivered-id logging, evidence recall; primary subset ids committed before the run
2026-10-29 08:05 UTC | PLAN s11 amendment before the first call: C and Cx draw from the same test-free pool as B's walk
2026-10-29 08:05 UTC | test: drop a dead line
2026-10-29 10:00 UTC | c-CRAB final pre-registered run (PLAN s11): records, primary-subset result, chance baseline, line accuracy, evidence recall
2026-10-30 05:55 UTC | Paper: ceiling claim qualified by prompt (95.5 presuming, 30 neutral); c-CRAB section reports all four runs with chance baseline, line accuracy, final-run primary subset as a lead; d'/c analysis; cite Shahriar et al. 2026; method-key limitation; Zenodo sentence removed; figures 1 and 2 redrawn
2026-11-01 09:48 UTC | Pre-register the deepseek-v3.2 replication of the final c-CRAB run (PLAN s12): primary and loose subset ids committed before the run, launcher with $5 stop
2026-11-01 09:54 UTC | PLAN s12 amendment: first launch crashed on a broken interpreter after one call; launcher points at the project venv; restart from zero
2026-11-03 10:36 UTC | PLAN §12: amendment after the deepseek run — one resume relaunch for the 15 unscored calls
2026-11-03 10:59 UTC | ccrab-deepseek: replication of run 4 on deepseek-v3.2 — primary B − Cx −7.7 [−17.8, +3.6], does not replicate
2026-11-03 13:55 UTC | Paper: report the deepseek-v3.2 replication of run 4 (primary −7.7 [−17.8, +3.6], lead does not hold); Figure 2 gains the replication group
2026-11-03 13:58 UTC | PLAN §13: pre-register the neutral-prompt defects on deepseek-v3.2 (d′/c on a second model); launcher
2026-11-03 14:00 UTC | Run 4: 50-hit hand-label sheet with the reference comment beside each matched finding, and the labelling guide
2026-11-04 09:41 UTC | Neutral-prompt defects on deepseek-v3.2 (PLAN §13, stopped at 244 of 277): criterion −0.43, d′ 0.00 on a second model; paper 4.3, abstract, discussion, artifact
2026-11-05 04:39 UTC | paper: 4.5 primary subset spans 35 repositories, not 34
2026-11-05 04:40 UTC | results: 50-hit hand-label sheet (blank) and LLM labels
2026-11-06 06:19 UTC | results: author's hand labels (44 of 50 received), agreement summary; one labeller only (PLAN §14)
2026-11-06 07:43 UTC | results: hand labels complete (50 of 50), summary rerun
2026-11-06 16:43 UTC | paper: pre-register condition E, CIS context on c-CRAB, before any model call
2026-11-06 17:20 UTC | condition E: CIS context extracted, coverage reported, amendment before any model call
2026-11-06 20:17 UTC | PREREG-E second amendment before any model call: file pool clarified, size-matched control CxE
2026-11-09 10:57 UTC | paper: pre-register run F, graded confidence and ROC per arm on kind-matched default flips, before any model call
2026-11-09 11:00 UTC | run F code (paper/PREREG-F.md): --confidence and --kinds in run_structure, ROC analysis, launchers
2026-11-10 10:01 UTC | Table 2 analysis: kind-matched signal detection script (default-flip defects vs default-flip twins) and its output
2026-11-10 10:14 UTC | run F amended code (paper/PREREG-F.md, Amendment 1): --hunk-ratings, hunk-score ROC analysis, 5-run launcher
2026-11-10 10:15 UTC | PREREG-F Amendment 1 before any model call of run F: hunk-rating AUC primary, margin 0.10, surface-match gate, five runs and caps
2026-11-10 10:23 UTC | run F (gpt4omini): records, analysis and README as recorded (finished)
2026-11-10 11:33 UTC | PREREG-F Amendment 2 during run 2, before its cap: deepseek caps raised for 2x longer replies (cost log only, no result seen), run 5 dropped
2026-11-10 11:34 UTC | launch_roc.sh per PREREG-F Amendment 2: deepseek caps 1.85 and 1.45, no run 5, finished runs skipped, interrupted logs kept
2026-11-10 12:39 UTC | run F (deepseek): records, analysis and README as recorded (finished)
2026-11-10 12:45 UTC | run F (gpt4omini-auth): records, analysis and README as recorded (finished)
2026-11-10 13:04 UTC | run F (deepseek-auth): records, analysis and README as recorded (finished)
2026-11-10 13:06 UTC | run F notes: deepseek restart under Amendment 2, overwritten smoke log, reply-length switch with a post hoc descriptive split
2026-11-10 13:55 UTC | run F controlled deepseek reruns (paper/PREREG-F.md, Amendment 3): reasoning off, one pinned provider
2026-11-10 13:56 UTC | PREREG-F Amendment 3 before any call of the controlled deepseek reruns (post hoc: reasoning off, one fp8 provider); Table 2 reply-length split
2026-11-10 14:23 UTC | run F (deepseek-ctrl): records, analysis and README as recorded (finished)
2026-11-10 14:42 UTC | run F (deepseek-auth-ctrl): records, analysis and README as recorded (finished)
2026-11-10 17:36 UTC | PREREG-F Amendment 4 before any call of run 2t (post hoc: deepseek-v3.2 with reasoning on, pinned provider, 1-diff and 5-attributed, mixed shuffled shards, run F limit $4.90, cap $2.30); its code
2026-11-10 18:00 UTC | run F 2t (Amendment 4): smoke usage objects, finish reasons and projection, before the launch
2026-11-10 19:21 UTC | run F 2t (Amendment 4): records, analysis, between-run comparison and README as recorded (stopped by an Amendment 4 abort rule (not restarted))
2026-11-10 19:22 UTC | run F 2t: README notes (pre-launch push delay, GMICloud fallback, max_tokens not enforced, partial run, unrecorded spend)
2026-11-10 19:48 UTC | PREREG-F Amendment 5 before any call under it (post hoc, after run 2t's partial results): complete run 2t and add 7-random on GMICloud; runaway calls logged as failed; cap $1.40; its code
2026-11-11 06:53 UTC | run F 2t completed with 7-random (Amendment 5): records, analysis, between-run comparison and README as recorded (finished)
2026-11-11 09:06 UTC | PREREG-F Amendment 5 addendum before the retry of 4 calls that got HTTP 400 in both passes; llm.py logs the HTTP error body
2026-11-11 09:13 UTC | run F 2t complete: retry of the 4 HTTP 400 calls (all recorded), analysis and compare-2c rerun on 846 records, README notes; Amendment 5 addendum time corrected to 12:06 (commit time)
2026-11-11 10:02 UTC | PREREG-F Amendment 6 before any call of run 2g (post hoc, after runs 2c and 2t): deepseek reasoning off on GMICloud, 3 arms; secondary 2t vs 2g and descriptive 2g vs 2c; cap $0.60; its code
2026-11-11 10:11 UTC | run F 2g (Amendment 6): did not start (smoke test failed: FAIL struc ch.py::verify_evidence::default_flip::32 reasoning_tokens 5444; struc ch.py::verify_evidence::default_flip::32 output tokens 5674; struc ::jobs_list_str::default_flip::745::safe reasoning_tokens 3076; struc ::jobs_list_str::default_flip::745::safe output tokens 3316; struc r.py::create_html_repr::default_flip::94 reasoning_tokens 1651; struc r.py::create_html_repr::default_flip::94 output tokens 1881; struc _list_repr_html::default_flip::857::safe reasoning_tokens 5654; struc _list_repr_html::default_flip::857::safe output tokens 5887; struc y::prepare_table_data::default_flip::157 reasoning_tokens 1887; struc y::prepare_table_data::default_flip::157 output tokens 2112; struc testation_token::default_flip::135::safe reasoning_tokens 7983; struc testation_token::default_flip::135::safe output tokens 8107; manip ch.py::verify_evidence::default_flip::32 reasoning_tokens 120)
2026-11-11 12:11 UTC | PREREG-F Amendment 6 addendum before any probe call: smoke test failed (GMICloud reasoned with enabled false); probe up to 3 other reasoning-off settings on GMICloud (cap $0.01), run 2g as planned if one passes; missing hunk ratings counted, not a smoke failure; its code
2026-11-11 12:13 UTC | run F 2g (Amendment 6 addendum): reasoning-off probes on GMICloud (none passed)
2026-11-14 10:15 UTC | Robustness checks behind specific paper sentences (re-analysis of committed records, no API calls)
```
