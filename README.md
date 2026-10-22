# Awesome Code Session To Post

A list of essays, examples and tools for turning normal coding work (commits, experiments, debugging, AI agent sessions) into small public notes, without making writing a second job.

Collected 2026-10-22. Every link was opened when collected. Know something that belongs here? Open an issue or a pull request.

## Contents

- [Why write small](#why-write-small)
- [AI coding sessions as raw material](#ai-coding-sessions-as-raw-material)
- [Dev activity into posts](#dev-activity-into-posts)
- [Publishing and distribution](#publishing-and-distribution)

## Why write small

### Essays on working and learning in public
- [Learn in Public (swyx)](https://www.swyx.io/learn-in-public) - Shawn Wang's essay asking developers to publish what they learn as they learn it, which is the founding text for turning everyday work into public notes.
- [Show Your Work! (Austin Kleon)](https://austinkleon.com/show-your-work/) - Book page for Kleon's guide to sharing your process in small daily pieces instead of waiting for a finished product.
- [Work with the garage door up (Andy Matuschak)](https://notes.andymatuschak.org/Work_with_the_garage_door_up) - A short working note arguing that creative people should share unfinished and failing work day after day instead of only announcing finished projects.
- [What to blog about (Simon Willison)](https://simonwillison.net/2022/Nov/6/what-to-blog-about/) - Names two low-effort post types, TILs and a few paragraphs plus a screenshot about each project, and treats "write about it" as part of finishing the work.
- [Coping strategies for the serial project hoarder (Simon Willison)](https://simonwillison.net/2022/Nov/26/productivity/) - Talk write-up where he says no project of his is finished until he has told people about it, and links TILs to his day-to-day workflow.
- [Blogging principles I use (Julia Evans)](https://jvns.ca/blog/2017/03/20/blogging-principles/) - Write for your past self, cover what you just learned, and accept small public mistakes instead of faking expertise.
- [Some blogging myths (Julia Evans)](https://jvns.ca/blog/2023/06/05/some-blogging-myths/) - Pushes back on beliefs that stop developers from posting, such as needing to be an expert or needing to be original.

### Essays arguing for small posts over big articles
- [Announcing a New Section: TIL (Hynek Schlawack)](https://hynek.me/articles/til/) - Hynek says his main blog had become too high-effort, so he added a TIL section for quick, unpolished "how do I X" answers.
- [Trying out logs and TILs (Erethon)](https://blog.erethon.com/blog/2024/12/03/trying-out-logs-and-tils) - A developer with long essays half-finished for years switches to short logs and TILs to get things published.
- [Want to write as a coder? Start with TIL posts (Cesar Aguirre)](https://dev.to/canro91/want-to-write-as-a-coder-start-with-til-posts-1l3j) - Tells new coding bloggers to skip deep dives and start with short TIL posts that need no long intro or conclusion.
- [How to Achieve Ultimate Blog Success In One Easy Step (Jeff Atwood)](https://blog.codinghorror.com/how-to-achieve-ultimate-blog-success-in-one-easy-step/) - Argues that sticking to a sustainable posting schedule for a year matters more than writing big posts.
- [Do they deserve the gift of your keystrokes? (Scott Hanselman)](https://www.hanselman.com/blog/do-they-deserve-the-gift-of-your-keystrokes) - Make answers you already type into emails public (for example as blog posts) so the effort reaches more people.
- [Small b blogging (Tom Critchlow)](https://tomcritchlow.com/2018/02/23/small-b-blogging/) - Makes the case for low-stakes blogging aimed at a small network of peers rather than a big audience.
- [dev log (ratfactor)](https://ratfactor.com/cards/dev-log) - Describes keeping an append-only dev log as breadcrumbs for your future self, which let the author pick a project back up after five months away.

### TIL repos and micro-notebooks from coding
- [jbranchaud/til](https://github.com/jbranchaud/til) - Josh Branchaud's long-running repo of short write-ups on small things that "don't really warrant a full blog post" (about 14,160 stars and 1,890 TILs when checked).
- [How I Built a Learning Machine (Josh Branchaud)](https://dev.to/jbranchaud/how-i-built-a-learning-machine-45k9) - The essay his TIL README links to, explaining the learning-in-public habit behind the repo.
- [simonw/til](https://github.com/simonw/til) - Simon Willison's TIL repo, which its README says was inspired by jbranchaud/til and which had 583 entries when checked.
- [Simon Willison: TIL](https://til.simonwillison.net/) - The searchable site built from that repo, showing how a pile of small notes becomes a findable public archive.
- [Using a self-rewriting README powered by GitHub Actions (Simon Willison)](https://simonwillison.net/2020/Apr/20/self-rewriting-readme/) - Explains the automation that rebuilds the TIL index on every commit, so publishing a note costs almost nothing.
- [Julia Evans TIL](https://jvns.ca/til/) - Her short-post section, which she says exists because publishing to the blog is her only way of saving bookmarks.
- [Hashrocket TIL](https://til.hashrocket.com/) - A whole company's team posts its daily small findings in one public feed.
- [thoughtbot/til](https://github.com/thoughtbot/til) - thoughtbot's shared TIL repo, another team-level version of the habit.
- [GitHub topic: til](https://github.com/topics/til) - GitHub's index of public repos tagged "til", for finding more personal TIL collections.

### Digital gardens and weekly notes
- [A Brief History and Ethos of the Digital Garden (Maggie Appleton)](https://maggieappleton.com/garden-history) - Essay on the digital garden idea, where unfinished notes are published and improved over time instead of being polished first.
- [The Garden and the Stream (Mike Caulfield)](https://hapgood.us/2015/10/17/the-garden-and-the-stream-a-technopastoral/) - The 2015 essay behind the garden-versus-stream framing for publishing notes that keep growing.
- [Hamel Husain: Notes](https://hamel.dev/notes/) - An index of his personal technical notes (Docker, Kubernetes, LLM evals, RAG), published as-is next to his longer blog posts.
- [Simon Willison: weeknotes tag](https://simonwillison.net/tags/weeknotes/) - His weekly notes on what he worked on, a low-bar routine that comes straight out of his coding work.
- [Register Spill (Thorsten Ball)](https://registerspill.thorstenball.com/) - Thorsten Ball's newsletter of regular informal programming notes and links.

## AI coding sessions as raw material

### Exporters and viewers
- [claude-code-transcripts](https://github.com/simonw/claude-code-transcripts) - Simon Willison's Python CLI that turns Claude Code sessions into paginated HTML transcripts and can publish them as GitHub Gists, which makes a coding session something you can link to.
- [A new way to extract detailed transcripts from Claude Code](https://simonwillison.net/2025/Dec/25/claude-code-transcripts/) - Willison's launch post for that tool, covering why he publishes his sessions and the `--gist` sharing workflow.
- [claude-code-log](https://github.com/daaain/claude-code-log) - Python CLI and TUI that converts the Claude Code JSONL files in `~/.claude/projects` into readable HTML and Markdown, with project index pages and token usage.
- [cc2md](https://github.com/magarcia/cc2md) - Converts Claude Code session logs into clean GFM Markdown through an interactive picker, so a session can be pasted into a README, issue or post.
- [claude-conversation-extractor](https://github.com/ZeroSumQuant/claude-conversation-extractor) - Pulls clean conversation logs out of Claude Code's internal storage as Markdown, JSON or HTML.
- [claude-JSONL-browser](https://github.com/withLinda/claude-JSONL-browser) - Web tool that converts Claude Code JSONL logs into readable Markdown, with a file explorer for working through many logs.
- [claude-replay](https://github.com/es617/claude-replay) - Turns sessions from Claude Code, Cursor, Codex, Gemini, OpenCode and others into self-contained, embeddable HTML replays that drop into a blog post.
- [shiplog](https://github.com/HabibPro1999/shiplog) - Turns AI coding sessions into self-contained HTML documents, aimed at showing what you built to a team, a manager or a portfolio.
- [codex-session-export](https://github.com/MeXenon/codex-session-export) - Interactive terminal tool that exports Codex CLI session chats to Markdown.
- [Cursor Chronicle](https://github.com/mikhailsal/cursor-chronicle) - Reads Cursor's local databases for full-text search, chat extraction, usage stats and Markdown export of Cursor conversations.
- [SpecStory](https://github.com/specstoryai/getspecstory) - Local-first extensions and a CLI wrapper that save Cursor, Claude Code, Codex and Gemini CLI chats as Markdown in `.specstory/history/` inside the project, with secret redaction, per its [FAQ](https://docs.specstory.com/faqs).
- [Aider chat history file](https://aider.chat/docs/config/options.html) - Aider's `--chat-history-file` option (default `.aider.chat.history.md`) writes every session as a running Markdown log, so the raw material exists out of the box.

### Search and archives
- [memex (nicosuave)](https://github.com/nicosuave/memex) - Searches Claude Code, Codex, Pi, OpenCode, GitHub Copilot and Cursor transcripts, and can also resume sessions and track tokens, which helps when looking for the session worth writing up.
- [memex (vimo-ai)](https://github.com/vimo-ai/memex) - A separate project that keeps one uncompacted, searchable memory across agent CLIs, with exact search exposed over MCP.
- [Sharing Claude transcripts](https://lethain.com/sharing-claude-transcripts/) - Will Larson describes an internal SSO-protected archive of Claude Code sessions, built on claude-code-transcripts, with a share command, so teams learn from each other's prompts.
- [Keep Claude Code logs past 30 days](https://simonwillison.net/2025/Oct/22/claude-code-logs/) - Short Willison note on raising `cleanupPeriodDays` so Claude Code stops deleting your session logs, the precondition for mining them later.

### Sessions into posts, commits and devlogs
- [Vibing a Non-Trivial Ghostty Feature](https://mitchellh.com/writing/non-trivial-vibing) - Mitchell Hashimoto writes up shipping a Ghostty feature and links every agentic session along the way, unedited and in full (Willison's commentary is [here](https://simonwillison.net/2025/Oct/11/vibing-a-non-trivial-ghostty-feature/)).
- [Amp thread sharing](https://ampcode.com/docs/threads) - Amp threads can be set to Unlisted so anyone with the link can read them, the feature Hashimoto used to publish his sessions.
- [session-to-post (claude-night-market scribe)](https://github.com/athola/claude-night-market) - Claude Code plugin skill (`plugins/scribe/skills/session-to-post`) that turns a session into a blog post, case study or social thread, using git history and conversation context.
- [devlog](https://github.com/varunr89/devlog) - Claude Code plugin that writes daily dev log entries from coding sessions on its own.
- [CodeStory](https://github.com/itsBrianCreates/CodeStory) - Agent skill that notes moments worth sharing during a Claude Code session and drafts social media posts from them.
- [git-memento](https://github.com/mandel-macaque/memento) - Git extension that attaches the AI session transcript (Codex and Claude Code) to each commit as git notes.
- [cnotes](https://github.com/imjasonh/cnotes) - Uses Claude Code hooks to save the conversation behind each commit as git notes, giving every change a readable "why".
- [The session is the commit message](https://blakecrosley.com/blog/session-is-the-commit-message) - Blake Crosley's essay (March 2026) arguing that agent transcripts hold the reasoning behind a change and belong next to the commit.

### Redaction before sharing
- [redacted](https://github.com/svn-arv/redacted) - A proxy that strips secrets from what AI coding assistants see, so they never land in transcripts you might publish.
- [dotenvx for Claude Code](https://dotenvx.com/docs/claude/) - Lets Claude Code use real secrets while redacting them from output, terminals and agent transcripts.

## Dev activity into posts

### Changelog and release-note generators
- [release-please](https://github.com/googleapis/release-please) - Google's tool that reads Conventional Commits and opens a release PR with a generated changelog, so release notes come out of ordinary commit messages.
- [git-cliff](https://github.com/orhun/git-cliff) - A customizable Rust changelog generator that turns Conventional Commit history into templated release notes ready to publish.
- [changesets](https://github.com/changesets/changesets) - Contributors add a small markdown note with each PR and changesets collects them into versioned changelogs, so the writing happens during normal PR work.
- [semantic-release](https://github.com/semantic-release/semantic-release) - Fully automated versioning and publishing that writes release notes from commit messages on every merge.
- [release-drafter](https://github.com/release-drafter/release-drafter) - A GitHub Action that keeps a draft of the next release's notes up to date as PRs are merged, grouped by label.
- [conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) - The long-running library behind many tools that turn commit metadata into changelogs and release notes.
- [GitHub automatically generated release notes](https://docs.github.com/en/repositories/releasing-projects-on-github/automatically-generated-release-notes) - GitHub's built-in feature that writes a release body from merged PRs and contributors, configurable in `.github/release.yml`.

### Posting releases and commits to social
- [GoReleaser announce](https://goreleaser.com/customization/announce/) - GoReleaser's announce step posts each release to Bluesky, Mastodon, X, LinkedIn, Reddit, Discord, Slack, Telegram and others as part of the release pipeline.
- [JReleaser announcers](https://jreleaser.org/guide/latest/reference/announce/index.html) - A JVM-focused release tool with about 20 announcers, including Bluesky, Mastodon, LinkedIn and an "Article" announcer that writes a post.
- [cbrgm/mastodon-github-action](https://github.com/cbrgm/mastodon-github-action) - A maintained GitHub Action that sends a toot with optional media from any workflow, often on `release: published`.
- [myConsciousness/bluesky-post](https://github.com/myConsciousness/bluesky-post) - A GitHub Action that posts to Bluesky from a workflow, used to announce releases or deploys.
- [OpenTweet GitHub releases workflow](https://opentweet.io/workflows/github-releases-to-bluesky-and-linkedin) - A ready-made workflow (commercial service) that sends each published GitHub release to X, Bluesky and LinkedIn.
- [buildinpublic-x](https://github.com/rav4nn/buildinpublic-x) - Reads your daily commits and uses an LLM to write and schedule a nightly build-in-public thread for X or Bluesky (tiny project).

### Standups, weekly reports and brag docs from git history
- [git-standup](https://github.com/nilbuild/git-standup) - A classic CLI that shows what you or your team committed on the last working day, as raw material for an update (activity slowing).
- [gitglimpse](https://github.com/dino-zecevic/gitglimpse) - A Python CLI that pulls structured context out of git history to write standups, weekly reports and PR descriptions, with an optional LLM mode.
- [mornin](https://pypi.org/project/mornin/) - A small standup CLI that summarizes your recent git activity with a local LLM through Ollama.
- [Reflect](https://github.com/bostonaholic/reflect) - Collects your GitHub contributions and writes a brag document and summary from them.
- [BragDoc](https://www.bragdoc.ai) - A product with a local CLI that pulls achievements out of git commits and turns them into performance reviews and manager reports.
- [bragbot](https://github.com/naamanu/bragbot) - A TypeScript tool, inspired by Julia Evans' brag documents post, that writes brag documents from git history.
- [promoteme](https://github.com/g4rcez/promoteme) - A Rust CLI that reads your PRs through the GitHub CLI and drafts a brag document with an LLM.

## Publishing and distribution

### Syndication (POSSE) plumbing
- [POSSE (IndieWeb wiki)](https://indieweb.org/POSSE) - The IndieWeb definition of "Publish on your Own Site, Syndicate Elsewhere": the post lives on your own site first and copies go out to social networks.
- [Bridgy](https://brid.gy/) - Sends likes, replies and reposts from social networks back to your site as webmentions, and can also publish your posts out to those networks.
- [Bridgy Fed](https://fed.brid.gy/) - Bridges a plain website into the fediverse and Bluesky, so people can follow a static blog from Mastodon or Bluesky without you running a server.
- [EchoFeed](https://echofeed.app/) - A hosted service that cross-posts an RSS feed to Mastodon, Bluesky, Micro.blog, Discord and more, so you never post to those places by hand.
- [Feed to Bluesky (GitHub Action)](https://github.com/marketplace/actions/feed-to-bluesky) - A GitHub Action that pushes new ATOM/RSS feed items to Bluesky, so a scheduled workflow next to your repo handles syndication.
- [Feed to Mastodon (GitHub Action)](https://github.com/marketplace/actions/feed-to-mastodon) - The Mastodon version of the same idea: new feed entries get posted from GitHub Actions.
- [Send Bluesky Post (GitHub Action)](https://github.com/marketplace/actions/send-bluesky-post) - A GitHub Action that posts to Bluesky from a workflow, so a merge or release can trigger a short post.

### Minimal micro-blog and notes hosting
- [GitHub Pages](https://pages.github.com/) - Free static hosting straight from a repo, the usual zero-cost base for a blog that is just a folder of markdown files.
- [Jekyll](https://jekyllrb.com/) - The static site generator built into GitHub Pages, which turns markdown posts in a repo into a blog with no separate build server.
- [Minima](https://github.com/jekyll/minima) - Jekyll's default theme for writers, enough for a plain notes blog without any design work.
- [Hugo](https://gohugo.io/) - A fast single-binary static site generator that suits a large, growing pile of short notes.
- [Eleventy RSS plugin](https://www.11ty.dev/docs/plugins/rss/) - Eleventy's official feed plugin; the feed is what all the syndication tools above read from.
- [Micro.blog](https://micro.blog/) - A hosted micro-blogging platform built around short posts on your own domain, with cross-posting to other networks ([docs](https://help.micro.blog/t/cross-posting-to-other-services/45)).
- [Bear Blog](https://bearblog.dev/) - A very small hosted blogging platform with no-frills markdown posts, for people who want nothing to maintain.
- [Mataroa](https://mataroa.blog/) - A "blogging platform for minimalists" with markdown posts; its source code is open on GitHub.
- [prose.sh](https://prose.sh/) - "A blog platform for hackers" where you publish markdown files from the terminal over SSH/rsync, which fits a coding workflow.
- [Obsidian Digital Garden](https://github.com/oleeskild/obsidian-digital-garden) - An Obsidian plugin that publishes selected notes from your vault to a public website.
- [Quartz](https://quartz.jzhao.xyz/) - A static site generator that turns a folder of markdown notes (such as an Obsidian vault) into a linked, searchable website.
- [Obsidian Publish](https://obsidian.md/publish) - Obsidian's paid hosted option for publishing notes straight from the vault.
- [Blog software (Tech Notes, neugierig.org)](https://neugierig.org/software/blog/2022/10/blog-software.html) - A short post on running a blog on "aggressively boring technology": a few templates, a tree of markdown files, static hosting for about 50 cents a month.

### Making notes findable by LLMs and AI search
- [llms.txt](https://llmstxt.org/) - The proposed spec for a `/llms.txt` markdown file that gives language models a clean, curated map of a site's content.
- [/llms.txt proposal (Answer.AI)](https://www.answer.ai/posts/2024-09-03-llmstxt.html) - Jeremy Howard's original 2024 post explaining why the file exists, with the spec repo at [AnswerDotAI/llms-txt](https://github.com/AnswerDotAI/llms-txt).
- [GEO: Generative Engine Optimization (Aggarwal et al.)](https://arxiv.org/abs/2311.09735) - The paper that coined GEO, measuring which content changes (such as adding citations, quotes and statistics) make a source more visible in generative engine answers; the project site is [generative-engines.com](https://generative-engines.com/).
- [Generative Engine Optimization: How to Dominate AI Search (Chen et al. 2025)](https://arxiv.org/abs/2509.08919) - Controlled experiments finding that AI search engines strongly favor third-party "earned" sources over brand-owned and social content, which matters if your notes only live on your own site.
