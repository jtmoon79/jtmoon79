<!-- omit in toc -->
# Hello

I am James Thomas Moon. 👋
I am a software engineer. 🤓
Most of my experience is within testing and tools. 👷

---

<!-- Table Of Contents created by VS Code extension Markdown All In One -->

- [My Open-Source Work Samples](#my-open-source-work-samples)
  - [github Projects](#github-projects)
  - [Continuous Integration and Code Coverage](#continuous-integration-and-code-coverage)
    - [Azure Pipelines](#azure-pipelines)
    - [CircleCI](#circleci)
    - [codecov.io](#codecovio)
    - [Github Actions](#github-actions)
    - [Travis CI](#travis-ci)
  - [StackExchange Questions and Answers](#stackexchange-questions-and-answers)
  - [Bug Reports and Feature Requests](#bug-reports-and-feature-requests)
  - [Pull Requests](#pull-requests)
  - [github Forum Posts](#github-forum-posts)
  - [Other Links](#other-links)
- [Contributing to Open Source](#contributing-to-open-source)
- [Recommended podcasts](#recommended-podcasts)

---

## My Open-Source Work Samples

The following lists are pubicly available examples of my work:

<!--
Thread on linking to icons: https://github.com/simple-icons/simple-icons/discussions/6895
-->

### github Projects

- <img height="12" width="12" src="https://api.iconify.design/simple-icons/rust.svg?color=maroon"/> [`jtmoon79/super-speedy-syslog-searcher`](https://github.com/jtmoon79/super-speedy-syslog-searcher)<br/>_Speedily search and merge log files by datetime._
- <img height="12" width="12" src="https://api.iconify.design/simple-icons/rust.svg?color=maroon"/> [`jtmoon79/si_trace_print`](https://github.com/jtmoon79/si_trace_print)<br/>_stack indented trace printing; a rust library to print messages indented to stack depth optionally preceded by the function name._
- <img height="12" width="12" src="https://api.iconify.design/simple-icons/python.svg?color=yellow"/> [`jtmoon79/goto_http_redirect_server`](https://github.com/jtmoon79/goto_http_redirect_server)<br/>_The "Go To" HTTP Redirect Server for sharing dynamic shortcut URLs on your network._
- <img height="12" width="12" src="https://api.iconify.design/simple-icons/python.svg?color=yellow"/> [`jtmoon79/coverlovin2`](https://github.com/jtmoon79/coverlovin2)<br/>_Add music album images to your music file directories._
- <img height="12" width="12" src="https://api.iconify.design/simple-icons/powershell.svg?color=lightblue"/> <img height="12" width="12" src="https://api.iconify.design/simple-icons/python.svg?color=yellow"/> [`jtmoon79/PythonEmbed4Win`](https://github.com/jtmoon79/PythonEmbed4Win)<br/>_Easily create a standalone Python embed.zip local environment in Windows._
- <img height="12" width="12" src="https://api.iconify.design/simple-icons/debian.svg?color=darkred"/> <img height="12" width="12" src="https://api.iconify.design/simple-icons/openbsd.svg?color=lightyellow"/> [`jtmoon79/openssh-latest-build-install.md`](https://gist.github.com/jtmoon79/745e6df63dd14b9f2d17a662179e953a)<br/>_Build, install, and run the latest OpenSSH Server as a systemd service._
- <img height="12" width="12" src="https://api.iconify.design/simple-icons/wireguard.svg?color=red"/> [`jtmoon79/wireguard-site-to-site.sh`](https://gist.github.com/jtmoon79/c951f81f621bb87ddb60836245aca4ff) _Wireguard Site to Site generator._<br/>
<img height="12" width="12" src="https://api.iconify.design/simple-icons/wireguard.svg?color=red"/> [`jtmoon79/wireguard-client-to-site.sh`](https://gist.github.com/jtmoon79/217e55272c55631ba6025c9f890b3dde) _Wireguard Client to Site generator._
- <img height="12" width="12" src="https://api.iconify.design/simple-icons/gnubash.svg?color=lightblue"/> [`jtmoon79/dotfiles`](https://github.com/jtmoon79/dotfiles)<br/>_Putting the . in ._<br/>Miscellaneous user dot files for consistent user shell environments. Also a place to store various small scripts for various tasks.

### Continuous Integration and Code Coverage

I've used several Continuous Integration (CI) services for the sake of learning about them. Here are example runs of each.

The <sup>_archived_</sup> links are provided because most CI Service providers expire detailed records.

#### Azure Pipelines

- <img height="12" width="12" src="https://api.iconify.design/simple-icons/azurepipelines.svg?color=lightblue"/> [Azure Pipelines workflow](https://dev.azure.com/jtmmoon/goto_http_redirect_server/_build/results?buildId=430) <sup>[archived](https://archive.ph/dvIOY)</sup> for my project [`goto_http_redirect_server`](https://github.com/jtmoon79/goto_http_redirect_server/blob/1.2.1/.azure-pipelines/azure-pipelines.yml)
- <img height="12" width="12" src="https://api.iconify.design/simple-icons/azurepipelines.svg?color=lightblue"/> [Azure Pipelines Code Coverage report](https://dev.azure.com/jtmmoon/goto_http_redirect_server/_build/results?buildId=430&view=codecoverage-tab) <sup>[archived](https://archive.ph/BNE9h)</sup> for my project [`goto_http_redirect_server`](https://github.com/jtmoon79/goto_http_redirect_server/blob/1.2.1/.azure-pipelines/azure-pipelines.yml#L150-L188)

#### CircleCI

- <img height="12" width="12" src="https://api.iconify.design/simple-icons/circleci.svg?color=white"/> [CircleCI workflow](https://app.circleci.com/pipelines/github/jtmoon79/coverlovin2) <sup>[archived](https://archive.ph/y8Esh)</sup> for my project [`CoverLovin2`](https://github.com/jtmoon79/coverlovin2/blob/0.7.3/.circleci/config.yml)
- <img height="12" width="12" src="https://api.iconify.design/simple-icons/circleci.svg?color=white"/> [CircleCI workflow](https://app.circleci.com/pipelines/github/jtmoon79/goto_http_redirect_server) <sup>[archived](https://archive.ph/RPgft)</sup> for my project [`goto_http_redirect_server`](https://github.com/jtmoon79/goto_http_redirect_server/blob/1.2.1/.circleci/config.yml)

#### codecov.io

- <img height="12" width="12" src="https://api.iconify.design/simple-icons/codecov.svg?color=purple"/> [codecov.io Code Coverage report](https://app.codecov.io/gh/jtmoon79/super-speedy-syslog-searcher/commit/66d4f28e831648077c89707232380dd107f043c5/tree) <sup>[archived](https://archive.ph/uLFRE)</sup> for my project [`super-speedy-syslog-searcher`](https://github.com/jtmoon79/super-speedy-syslog-searcher/blob/0.2.48/.github/workflows/rust.yml#L301-L336)
- <img height="12" width="12" src="https://api.iconify.design/simple-icons/codecov.svg?color=purple"/> [codecov.io Code Coverage report](https://app.codecov.io/gh/jtmoon79/si_trace_print/commit/5c6108e30f0ab7407e1736f187d643b1cbce6723/tree/src) <sup>[archived](https://archive.ph/CPYB7)</sup> for my project [`si_trace_print`](https://github.com/jtmoon79/si_trace_print/blob/0.3.9/.codecov.yml)
- <img height="12" width="12" src="https://api.iconify.design/simple-icons/codecov.svg?color=purple"/> [codecov.io Code Coverage report](https://app.codecov.io/gh/jtmoon79/coverlovin2) <sup>[archived](https://archive.ph/CR5C4)</sup> for my project [`CoverLovin2`](https://github.com/jtmoon79/coverlovin2/blob/0.7.3/.coveragerc)

#### Github Actions

- <img height="12" width="12" src="https://api.iconify.design/simple-icons/github.svg?color=black"/> [Github Actions workflow](https://github.com/jtmoon79/super-speedy-syslog-searcher/actions/runs/3927952485) <sup>[archived](https://archive.ph/bAiws)</sup> for project [`super-speedy-syslog-searcher`](https://github.com/jtmoon79/super-speedy-syslog-searcher/blob/0.2.48/.github/workflows/rust.yml)
- <img height="12" width="12" src="https://api.iconify.design/simple-icons/github.svg?color=black"/> [Github Actions workflow](https://github.com/jtmoon79/si_trace_print/actions/runs/3937216916) <sup>[archived](https://archive.ph/Q1NmW)</sup> for my project [`si_trace_print`](https://github.com/jtmoon79/si_trace_print/blob/0.3.9/.github/workflows/rust.yml)

#### Travis CI

- <img height="12" width="12" src="https://api.iconify.design/simple-icons/travisci.svg?color=green"/> [Travis CI workflow](https://app.travis-ci.com/github/jtmoon79/coverlovin2) <sup>[archived](https://archive.ph/QicYs)</sup> for my project [`CoverLovin2`](https://github.com/jtmoon79/coverlovin2/blob/0.7.3/.travis.yml)

### StackExchange Questions and Answers

Some of my favorite StackExchange posts:

- [_How can I use journalctl to time-filter and view non-journal files?_](https://unix.stackexchange.com/a/734044/21203) (_Answer_)
- [_DNS Server Search order in Windows 10 and VPNs_](https://serverfault.com/questions/1069162/dns-server-search-order-in-windows-10-and-vpns/1069163) (_Question + Answer_)
- [_What is the password for Windows 10 Sandbox Administrator?_](https://superuser.com/questions/1682686/) (_Question + Answer_)
- [_What is the list of python settings that affect encoding, decoding, and printing?_](https://stackoverflow.com/questions/54625182/) (_Question + Answer_)
- [_Python Windows embeddable package fails to run "No module named pip" "The system cannot find the path specified: 'C:\\python-3.9.6-embed-amd64\\DLLs'"_](https://stackoverflow.com/questions/68958635/python-windows-embeddable-package-fails-to-run-no-module-named-pip-the-system/68958636#68958636) (_Question + Answer_)
- [_rustdoc force for private function_](https://stackoverflow.com/questions/73316135) (_Question_)
- [_Python send email with "quoted-printable" transfer-encoding and "utf-8" content-encoding_](https://stackoverflow.com/questions/31714221) (_Question + Answer_)
- [_access return code of a function from within the trap RETURN handler \[bash\]_](https://stackoverflow.com/questions/32086595/access-return-code-of-a-function-from-within-the-trap-return-handler) (_Question + Answer_)
- [_rustdoc link to enum variant_](https://stackoverflow.com/questions/73316074/rustdoc-link-to-enum-variant/73316075#73316075) (_Question + Answer_)
- [_Is the MIME type 'image/jpg' the same as 'image/jpeg'?_](https://stackoverflow.com/questions/33692835/is-the-mime-type-image-jpg-the-same-as-image-jpeg/54488403#54488403) (_Answer_)
- [_select code based on cfg attribute not true \[rust\]_](https://stackoverflow.com/questions/71699737/select-code-based-on-cfg-attribute-not-true-rust/71699738#71699738) (_Question + Answer_)
- [_find all hard linked files between two directories_](https://unix.stackexchange.com/questions/275868) (_Question + Answer_)
- [_what is difference in \`declare -r\` and \`readonly\` in bash?_](https://stackoverflow.com/a/30362832/471376) (_Question + Answer_)
- [_On Linux, how do I the check CPU affinity of a process and its threads?_](https://serverfault.com/questions/462454/on-linux-how-do-i-the-check-cpu-affinity-of-a-process-and-its-threads/462455#462455) (_Question + Answer_)
- [_What Ethernet twisted pair cable is best with a particular Ethernet switch_](https://serverfault.com/questions/1089864) (_Question_)
- [_How to list all \`env\` properties within jenkins pipeline job?_](https://stackoverflow.com/questions/37083285) (_Question_)
- [_error [E0716]: temporary value dropped while borrowed \[rust\]_](https://stackoverflow.com/questions/71626083/) (_Question_)
- [_solving "argument requires that \`x\` is borrowed for \`'y\`" \[rust\]_](https://stackoverflow.com/questions/71774794/solving-argument-requires-that-x-is-borrowed-for-y) (_Question_)

### Bug Reports and Feature Requests

Some bug reports and feature requests I have made:

- [DD-WRT bug `#7622` _datetime timezone is different among processes, causes ambiguous syslog message datetimestamps_](https://svn.dd-wrt.com/ticket/7622)

<br/>

- [JetBrains PyCharm `PY-38692` _Python debugger breakpoint and symlinked paths can get confused during debugger pause_](https://youtrack.jetbrains.com/issue/PY-38692)
- [JetBrains PyCharm `PY-40521` _PyCharm cannot create virtualenv based on PyPy3.6_](https://youtrack.jetbrains.com/issue/PY-40521)

<br/>

- [`pypa/pipenv` Issue #4906 _pipenv install fails if subdirectory cannot be traversed_](https://github.com/pypa/pipenv/issues/4906)
- [`gerbera/gerbera` Issue #2675 *confusing nginx.conf docs example; use both ngx_http_subs_filter_module and ngx_http_sub_module*](https://github.com/gerbera/gerbera/issues/2675)
- [`yt-dlp/yt-dlp` Issue #3514 _set Windows NTFS file datetime-related attributes from other available information_](https://github.com/yt-dlp/yt-dlp/issues/3514)
- [`jeffparsons/rangemap` Issue #42 _[Feature Request] allow optional "no coalescing"_](https://github.com/jeffparsons/rangemap/issues/42)
- [`yuk7/AlpineWSL` Issue #26 _installer should set Name alpine versioned, e.g. "Alpine-3.15.0"_](https://github.com/yuk7/AlpineWSL/issues/26)
- [`Entware/Entware` Issue #716 _opkg program does not allow changing lockfile location; cannot run if /opt is readonly_](https://github.com/Entware/Entware/issues/716)
- [`microsoft/WSL` Issue #5650 _How to update the WSL2 kernel on current Windows 10_](https://github.com/microsoft/WSL/issues/5650#issuecomment-933138034)

<br/>

- [Synology Community: NAS _BUG: Hyper Backup dialog stuck when editing long-running paused task_](https://community.synology.com/enu/forum/1/post/155131)

<br/>

- [Launchpad `systemd` Bug `#1470399` _udev duplicates entries in 70-persistent-net.rules_](https://bugs.launchpad.net/ubuntu/+source/systemd/+bug/1470399) (see ad-hoc section _Original description of the problem_)

### Pull Requests

My other github commits:

- <img height="12" width="12" src="https://api.iconify.design/simple-icons/rust.svg?color=maroon"/> [`chronotope/chrono` various commits](https://github.com/chronotope/chrono/commits?author=jtmoon79)
- <img height="12" width="12" src="https://api.iconify.design/simple-icons/python.svg?color=yellow"/> [`emc-isilon/pike` various commits](https://github.com/emc-isilon/pike/commits?author=jtmoon79)
- <img height="12" width="12" src="https://api.iconify.design/simple-icons/python.svg?color=yellow"/> [`NeilGirdhar/ipromise` PR #9 _Readme tools samples_](https://github.com/NeilGirdhar/ipromise/pull/9)
- <img height="12" width="12" src="https://api.iconify.design/simple-icons/rust.svg?color=maroon"/> [`build-trust/ockam` PR #3710 _Codespell fixes_](https://github.com/build-trust/ockam/pull/3710)
- <img height="12" width="12" src="https://api.iconify.design/simple-icons/rust.svg?color=maroon"/> [`Stebalien/tempfile` PR #184 _doc clarify statics may leak_](https://github.com/Stebalien/tempfile/pull/184)

### github Forum Posts

My favorite github forum posts:

- [`clap-rs/clap` Discussion #3593 _how to control OPTIONS listing ordering?_](https://github.com/clap-rs/clap/discussions/3593)

### Other Links

- My [gist.github profile](https://gist.github.com/jtmoon79)
- My [StackExchange profile](https://stackexchange.com/users/216253/)
- My [gitlab profile](https://gitlab.com/jtmoon101)

## Contributing to Open Source

- [opencollective.com](https://opencollective.com/james-thomas-moon)
- [ko-fi](https://ko-fi.com/jamesthomasmoon85055)
- see my _Sponsors_ section on github

Among many other software projects and organizations that I have voluntarily donated!

## Recommended podcasts

Software-oriented podcasts that I listen to irregularly.

- [Business Wars](https://wondery.com/shows/business-wars/) (abbreviated histories of business competition)
- [Changelog](https://changelog.com/podcast)
- [Crypto-Gram Security](https://crypto-gram.libsyn.com/)
- [CyberWire Daily](https://thecyberwire.com/podcasts/daily-podcast)
- [Python Bytes](https://pythonbytes.fm/)
- [Rustacean Station](https://rustacean-station.org/)
- [Security Now](https://www.grc.com/SecurityNow.htm)
- [Software Engineering Daily](https://softwareengineeringdaily.com/)
- [Software Engineering Radio](https://www.se-radio.net/)
- [Test & Code](https://testandcode.com/)

---

<a href="https://stackexchange.com/users/216253/"><img src="https://stackexchange.com/users/flair/216253.png" width="208" height="58" alt="profile for @JamesThomasMoon on Stack Exchange, a network of free, community-driven Q&amp;A sites" title="profile for @JamesThomasMoon on Stack Exchange, a network of free, community-driven Q&amp;A sites" /></a>
