# Script & Switch

A working toolkit of IT automation scripts, sysadmin utilities, and infrastructure tooling — built while solving real problems on the job, cleaned up, and shared so other small IT teams don't have to start from zero.

**Live site:** https://blackfish-sudo.github.io/scriptandswitch/#toolkit

---

## What's in here

This repo currently hosts the portfolio site itself (`index.html`). The individual script templates referenced on the site are shared on request — see [Getting a template](#getting-a-template) below.

| Project | Status | Stack |
|---|---|---|
| Drive ownership transfer + reversal | Live | Apps Script, GWS Admin |
| Software renewal reminders | Live | Apps Script |
| Exit / offboarding ID cleanup | Live | Apps Script |
| GWS group + member fetch | Live | Apps Script, GWS Admin |
| PXE zero-touch OS deployment | Flagship | Windows Server, PXE, imaging |
| People-connect tracker | Shelved (governance) | Apps Script, Google Sheets |

## Why this exists

Most of what's here started as a script written to fix one annoying recurring task — a license renewal nobody tracked, an offboarding step that got missed, an admin console with no bulk view. Once something proved useful more than once, it got cleaned up enough to hand to someone else.

This isn't a product company or an agency. It's one engineer's working notebook, published in case the same problem is eating someone else's Tuesday too.

## Getting a template

Templates aren't bundled as ready-to-run files in this repo yet — most ship as a copyable Google Sheet with a bound Apps Script, since that's the easiest way to hand off something that "just works" without a build step.

To request one:
1. Check the live site's toolkit section for the project that matches your problem
2. Reach out via the contact link on the site
3. Expect to adjust column names, auth scopes, or paths for your own environment — nothing here is plug-and-play out of the box

## Local development

This is a single static HTML file with no build step.

```bash
git clone https://github.com/blackfish-sudo/scriptandswitch.git
cd scriptandswitch
open index.html
```

To deploy changes, push to `main` — GitHub Pages rebuilds automatically within a minute or two.

## License

Free to use and adapt for personal or internal business use. Attribution appreciated but not required. Not warrantied for production use — test in your own environment first.

---

Built and maintained by [Black Fish](https://www.linkedin.com/in/divakar-r-b5466b27a/) · IT automation, one script at a time.
