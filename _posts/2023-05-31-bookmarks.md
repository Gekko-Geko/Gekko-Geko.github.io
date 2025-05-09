---
layout: post
author: Gekko Geko
tags: [bookmarks, tools]
---

Some bookmarks

## List

- [AdGuardHome](https://github.com/AdguardTeam/AdGuardHome)
- [Apt fast](https://github.com/ilikenwf/apt-fast)
- [Bashly](https://github.com/DannyBen/bashly)
- [Bfg repo cleaner](https://github.com/rtyley/bfg-repo-cleaner)
- [CrowdSec](https://github.com/crowdsecurity/crowdsec)
- [Desec dns](https://desec.io/)
- [Diun](https://github.com/crazy-max/diun)
- [Dokku](https://github.com/dokku/dokku/)
- [FreshRSS](https://github.com/FreshRSS/FreshRSS)
- [Goaccess](https://github.com/allinurl/goaccess)
- [Heimdall](https://github.com/linuxserver/Heimdall)
- [Homer](https://github.com/bastienwirtz/homer)
- [HRConvert2](https://github.com/zelon88/HRConvert2)
- [Invidious](https://github.com/iv-org/invidious)
- [Keybr](https://www.keybr.com/)
- [Kompose](https://github.com/kubernetes/kompose)
- [Lazydocker](https://github.com/jesseduffield/lazydocker)
- [Lazygit](https://github.com/jesseduffield/lazygit)
- [Link ace](https://github.com/Kovah/LinkAce)
- [Linux server](https://www.linuxserver.io/)
- [Maglit](https://maglit.me/)
- [Monkeytype](https://monkeytype.com/)
- [Nginx proxy manager](https://github.com/NginxProxyManager/nginx-proxy-manager)
- [Ninite](https://ninite.com/)
- [Notica](https://notica.us/?d2M_wT)
- [Onionshare](https://github.com/onionshare/onionshare)
- [Pacstall](https://github.com/pacstall/pacstall)
- [Pissmail](https://pissmail.com/)
- [Pure sh bible](https://github.com/dylanaraps/pure-sh-bible)
- [Python anti formatter](https://github.com/LeviBorodenko/lancer)
- [Reconftw](https://github.com/six2dez/reconftw)
- [SearXNG](https://github.com/searxng/searxng)
- [Snyk](https://snyk.io/)
- [Sshmon](https://github.com/hpello/sshmon)
- [Tiny tiny rss](https://git.tt-rss.org/fox/tt-rss.git)
- [Tinywow](https://tinywow.com/)
- [Uselessweb](https://theuselessweb.com/)
- [Ventoy](https://www.ventoy.net/en/index.html)
- [Wireguard ui](https://github.com/ngoduykhanh/wireguard-ui)

## AdGuardHome

AdGuard Home is a network-wide software for blocking ads and tracking. After you set it up, it'll cover ALL your home devices, and you don't need any client-side software for that.

[github](https://github.com/AdguardTeam/AdGuardHome)

## Apt fast

apt-fast is a shellscript wrapper for apt-get and aptitude that can drastically improve apt download times by downloading packages in parallel, with multiple connections per package.

[github](https://github.com/ilikenwf/apt-fast)

## Bashly

Bashly is a command line application (written in Ruby) that lets you generate feature-rich bash command line tools.

[github](https://github.com/DannyBen/bashly)

## Bfg repo cleaner

The BFG is a simpler, faster alternative to git-filter-branch for cleansing bad data out of your Git repository history:

  - Removing Crazy Big Files
  - Removing Passwords, Credentials & other Private data

[github](https://github.com/rtyley/bfg-repo-cleaner)

## CrowdSec

CrowdSec is a free, modern & collaborative behavior detection engine, coupled with a global IP reputation network. It stacks on fail2ban's philosophy but is IPV6 compatible and 60x faster (Go vs Python), it uses Grok patterns to parse logs and YAML scenarios to identify behaviors.

[github](https://github.com/crowdsecurity/crowdsec)

## Desec dns

deSEC is a free DNS hosting service, designed with security in mind. 

[homepage](https://desec.io/)

## Diun

Docker Image Update Notifier is a CLI application written in Go and delivered as a single executable (and a Docker image) to receive notifications when a Docker image is updated on a Docker registry.

[github](https://github.com/crazy-max/diun)

## Dokku

Docker powered mini-Heroku. The smallest PaaS implementation you've ever seen.

[github](https://github.com/dokku/dokku/)

## FreshRSS

FreshRSS is a self-hosted RSS feed aggregator. It is lightweight, easy to work with, powerful, and customizable.

[github](https://github.com/FreshRSS/FreshRSS)

## Goaccess

GoAccess is an open source real-time web log analyzer and interactive viewer that runs in a terminal on *nix systems or through your browser.

[github](https://github.com/allinurl/goaccess)

## Heimdall

Heimdall Application Dashboard is a dashboard for all your web applications. It doesn't need to be limited to applications though, you can add links to anything you like.

[github](https://github.com/linuxserver/Heimdall)

## Homer

A dead simple static HOMepage for your servER to keep your services on hand, from a simple yaml configuration file.

[github](https://github.com/bastienwirtz/homer)

## HRConvert2

A self-hosted drag-and-drop file conversion server & file sharing tool that supports 86 file formats with 4 color schemes & 13 end-user selctable languages.

[github](https://github.com/zelon88/HRConvert2)

## Invidious

An open source alternative front-end to YouTube.

[github](https://github.com/iv-org/invidious)

## Keybr

Take a typing test, practice typing lessons, learn to type faster.

[homepage](https://www.keybr.com/)

## Kompose

kompose is a tool to help users who are familiar with docker-compose move to Kubernetes. kompose takes a docker-compose file and translates it into Kubernetes resources.

[github](https://github.com/kubernetes/kompose)

## Lazydocker

Simple terminal UI for both docker and docker-compose, written in Go with the gocui library.

[github](https://github.com/jesseduffield/lazydocker)

## Lazygit

A simple terminal UI for git commands, written in Go with the gocui library.

```bash
#!/usr/bin/env bash

LAZYGIT_VERSION=$(curl -s "https://api.github.com/repos/jesseduffield/lazygit/releases/latest" | grep -Po '"tag_name": "v\K[^"]*')
curl -Lo /tmp/lazygit.tar.gz "https://github.com/jesseduffield/lazygit/releases/latest/download/lazygit_${LAZYGIT_VERSION}_Linux_x86_64.tar.gz"
cd /tmp; tar xf lazygit.tar.gz lazygit
sudo install lazygit /usr/local/bin
```

[github](https://github.com/jesseduffield/lazygit)

## Link ace

LinkAce is a self-hosted archive to collect links of your favorite websites. Save articles to read them later, tools to use them in your next project, or historic content to archive it for the long term. LinkAce comes with a lot of features while keeping a clean and minimal interface.

[github](https://github.com/Kovah/LinkAce)

## Linux server

A group of like-minded enthusiasts from across the world who build and maintain the largest collection of Docker images on the web, and at our core are the principles behind Free and Open Source Software.

[homepage](https://www.linuxserver.io/)

## Maglit

Privacy Respecting Encrypted Link Shortener.

[homepage](https://maglit.me/)

## Monkeytype

Monkeytype is a minimalistic and customizable typing test. It features many test modes, an account system to save your typing speed history...

[homepage](https://monkeytype.com/)

## Nginx proxy manager

This project comes as a pre-built docker image that enables you to easily forward to your websites running at home or otherwise, including free SSL, without having to know too much about Nginx or Letsencrypt.

[github](https://github.com/NginxProxyManager/nginx-proxy-manager)

## Ninite

Ninite is a package management system for automatically installing popular applications for the Windows operating system. It enables users to make a selection from a list of applications and bundles the selection into a single installer package. 

[homepage](https://ninite.com/)

## Notica

Notica sends a notification to a tab in your browser when ran. It works over SSH and to your phone.

[homepage](https://notica.us/?d2M_wT)

## Onionshare

OnionShare is an open source tool that lets you securely and anonymously share files, host websites, and chat with friends using the Tor network.

[github](https://github.com/onionshare/onionshare)

## Pacstall

Pacstall is the AUR Ubuntu wishes it had. It takes the concept of the AUR and puts a spin on it, making it easier to install programs without scouring github repos and the likes.

[github](https://github.com/pacstall/pacstall)

## Pissmail

Handing out free email addresses on edgy/based/cringe domain names since 2021.

[homepage](https://pissmail.com/)

## Pure sh bible

A collection of pure POSIX sh alternatives to external processes.

[github](https://github.com/dylanaraps/pure-sh-bible)

## Python anti formatter

Ever heard of Black? This is the opposite. A tool to turn your clean python code into a hideous (working) mess.

[github](https://github.com/LeviBorodenko/lancer)

## Reconftw

reconFTW automates the entire process of reconnaissance for you. It outperforms the work of subdomain enumeration along with various vulnerability checks and obtaining maximum information about your target.

[github](https://github.com/six2dez/reconftw)

## SearXNG

Privacy-respecting, hackable metasearch engine.

[github](https://github.com/searxng/searxng)

## Snyk

Snyk is a developer security platform. Integrating directly into development tools, workflows, and automation pipelines, Snyk makes it easy for teams to find, prioritize, and fix security vulnerabilities in code, dependencies, containers, and infrastructure as code.

[homepage](https://snyk.io/)

## Sshmon

SSHMon is a program designed to manage and monitor ssh connections. It has been tested on Linux and OSX with SSH ≥ 6.7.

[github](https://github.com/hpello/sshmon)

## Tiny tiny rss

Tiny Tiny RSS is a free and open source web-based news feed (RSS/Atom) reader and aggregator.

[git](https://git.tt-rss.org/fox/tt-rss.git)


## Tinywow

We offer PDF, video, image and other online tools to make your life easier

[homepage](https://tinywow.com/)

## Uselessweb

Take me to a useless website.

[homepage](https://theuselessweb.com/)

## Ventoy

Ventoy is a free and open-source utility used for writing image files such as .iso, .wim, .img, .vhd(x), and .efi files onto storage media to create bootable USB flash drives. Once Ventoy is installed onto a USB drive, there is no need to reformat the disk to update it with new installation files; it is enough to copy the .iso, .wim, .img, .img(x), or .efi file(s) to the USB drive and boot from them directly. Ventoy will present the user with a boot menu to select one of these files.

[homepage](https://www.ventoy.net/en/index.html)

## Wireguard ui

A web user interface to manage your WireGuard setup.

[github](https://github.com/ngoduykhanh/wireguard-ui)

