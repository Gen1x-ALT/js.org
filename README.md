[![JS.ORG](https://img.shields.io/badge/js.org-+-FFE70B.svg?style=flat-square)](http://js.org)
[![PRs](https://img.shields.io/github/issues-pr-closed-raw/js-org/js.org.svg?style=flat-square&colorB=FFE70B&label=pull%20requests)](https://github.com/js-org/js.org/pulls?q=is%3Apr+is%3Aclosed+label%3Aadd)
[![Contributors](https://img.shields.io/github/contributors-anon/js-org/js.org?color=FFE70B&style=flat-square)](https://github.com/js-org/js.org/graphs/contributors)
[![Activity](https://img.shields.io/github/commit-activity/m/js-org/js.org?color=FFE70B&style=flat-square)](https://github.com/js-org/js.org/pulse/monthly)
[![Donate](https://img.shields.io/badge/Donate-for_registrar_fees-1F87FF.svg?style=flat-square&logo=open-collective&logoColor=fff)](https://opencollective.com/js-org)

---

## GitHub Pages

To get a short and sleek subdomain for your own GitHub Pages site from JS.ORG follow these 4 steps:

### Step 1

If you haven't already, log in to your GitHub account and set up your GitHub Pages site following [their instructions](https://pages.github.com). **Make sure to add some reasonable content to your new page**.

### Step 2

Now determine your JS.ORG subdomain: either choose your username or the name of your repository according to the existing GitHub Pages URL (for `http://foo.github.io/bar`, either `foo.js.org` or `bar.js.org` would be possible). More details are available in the [wiki](https://github.com/js-org/js.org/wiki).

### Step 3

Add a file named `CNAME` to your repo (in the `gh-pages` branch for project pages, or the branch that you've set as your GitHub Pages source) with a single line matching the domain you have chosen (e.g. `foo.js.org`). If you prefer a web interface form, have a look at [GitHub Pages Help](https://help.github.com/articles/adding-or-removing-a-custom-domain-for-your-github-pages-site).

### Step 4

To finish the procedure, make a pull request in this GitHub repository that adds your subdomain to the [subdomains list](https://github.com/js-org/js.org/blob/master/cnames_active.js) of existing JS.ORG domains. Your new URL should go live within 24 hours (keep an eye on your pull request in case of a naming conflict or if there are requested changes).

---

## Content Rules

### No-Content Rules
**Websites must be *directly* related to the JavaScript ecosystem/community (such a NPM packages / JS tools)**
- No placeholder pages. Websites must contain substantive content relevant to their purpose.
- No automatic redirects away from the **js.org** domain. Redirects must require user interaction.
- No unrelated content. Websites must stay focused on their intended topic or purpose.
- No personal pages/portfolios

---

Thanks to **[Cloudflare](https://www.cloudflare.com)** for their awesome DNS service that makes this service possible. While JS.ORG is using their free plan - to a shameless extent - they helped us more than once with some flexible solutions and extended quotas. Many thanks!
