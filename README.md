![Decap CMS](/img/decap.svg)

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/decaporg/decap-cms/blob/master/LICENSE) [![Netlify Status](https://api.netlify.com/api/v1/badges/8b87160b-0a11-4f75-8050-1d21bc1cff8c/deploy-status)](https://app.netlify.com/sites/decap-www/deploys) [![npm version](https://img.shields.io/npm/v/decap-cms.svg?style=flat)](https://www.npmjs.com/package/decap-cms) [![Build Status](https://github.com/decaporg/decap-cms/workflows/Node%20CI/badge.svg)](https://github.com/decaporg/decap-cms/actions?query=branch%3Amaster+workflow%3A%22Node+CI%22) [![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fdecaporg%2Fdecap-cms.svg?type=shield&issueType=license)](https://app.fossa.com/projects/git%2Bgithub.com%2Fdecaporg%2Fdecap-cms?ref=badge_shield) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/decaporg/decap-cms/blob/master/CONTRIBUTING.md)

[decapcms.org](https://www.decapcms.org/) 

A CMS for static site generators. Give users a simple way to edit
and add content to any site built with a static site generator.

## Community Chat

<a href="https://decapcms.org/chat">Join us on Discord</a>

## How It Works

Decap CMS is a single-page app that you pull into the `/admin` part of your site.

It presents a clean UI for editing content stored in a Git repository.

You setup a YAML config to describe the content model of your site, and typically
tweak the main layout of the CMS a bit to fit your own site.

When a user navigates to `/admin/` they'll be prompted to log in, and once authenticated
they'll be able to create new content or edit existing content.

Read more about Decap CMS [Core Concepts](https://www.decapcms.org/docs/intro/).

## Installation and Configuration

The Decap CMS can be used in two different ways.

* A Quick and easy install, that requires you to create a single HTML file and a configuration file. All the CMS JavaScript and CSS are loaded from a CDN.
  To learn more about this installation method, refer to the [Quick Start Guide](https://www.decapcms.org/docs/quick-start/)
* A complete, more complex install, that gives you more flexibility but requires that you use a static site builder with a build system that supports npm packages.

## Contributing

New contributors are always welcome! Check out [CONTRIBUTING.md](https://github.com/decaporg/decap-cms/blob/master/CONTRIBUTING.md) to get involved.

## Change Log

This project adheres to [Semantic Versioning](http://semver.org/).
Every release is documented on the Github [Releases](https://github.com/decaporg/decap-cms/releases) page.

## License

Decap CMS is released under the [MIT License](LICENSE).
Please make sure you understand its [implications and guarantees](https://writing.kemitchell.com/2016/09/21/MIT-License-Line-by-Line.html).

## Maintainers

Maintained with care by <a href="https://techhub.p-m.si/">PM</a> & friends.
