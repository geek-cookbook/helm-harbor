
[cookbookurl]: https://geek-cookbook.funkypenguin.co.nz
[discourseurl]: https://discourse.geek-kitchen.funkypenguin.co.nz
[discordurl]: http://chat.funkypenguin.co.nz
[patreonurl]: https://patreon.com/funkypenguin
[blogurl]: https://www.funkypenguin.co.nz
[twitchurl]: https://www.twitch.tv/funkypenguinz
[twitterurl]: https://twitter.com/funkypenguin
[dockerurl]: https://geek-cookbook.funkypenguin.co.nz/ha-docker-swarm/design
[k8surl]: https://geek-cookbook.funkypenguin.co.nz/kubernetes/start

<div align="center">

[![geek-cookbook](https://raw.githubusercontent.com/geek-cookbook/autopenguin/master/images/readme_header.png)][cookbookurl]
[![Discord](https://img.shields.io/discord/396055506072109067?color=black&label=Hot%20Sweaty%20Geeks&logo=discord&logoColor=white&style=for-the-badge)][discordurl]
[![Forums](https://img.shields.io/discourse/topics?color=black&label=Forums&logo=discourse&logoColor=white&server=https%3A%2F%2Fdiscourse.geek-kitchen.funkypenguin.co.nz&style=for-the-badge)][discourseurl]
[![Cookbook](https://img.shields.io/badge/Recipes-44-black?style=for-the-badge&color=black)][cookbookurl]
[![Twitch Status](https://img.shields.io/twitch/status/funkypenguinnz?style=for-the-badge&label=LiveGeeking&logoColor=white&logo=twitch)][twitchurl]

:wave: Welcome, traveller!
> The [Geek Cookbook][cookbookurl] is a collection of geek-friendly "recipes" to run popular applications on [Docker Swarm][dockerurl] or [Kubernetes][k8surl], in a progressive, easy-to-follow format.  ***Come and [join us][discordurl], fellow geeks!*** :neckbeard:
</div>

 
# Contents

1. [What is this?](#what-is-this)
2. [Why it exists?](#why-it-exists)


# Why should I use this chart?

For one thing, it's known to be syntactically correct, thanks to the wonders of CI:

![Linting](https://github.com/geek-cookbook/.penguin/workflows/Linting/badge.svg)
![Testing](https://github.com/geek-cookbook/.penguin/workflows/Testing/badge.svg)


 
# How to use it?

Use helm to add the repo:

```
helm repo add geek-cookbook https://geek-cookbook.github.io/charts/
```

Then simply install using helm, for example

```
kubectl create namespace .penguin
helm upgrade --install --namespace .penguin geek-cookbook/.penguin
```




# What is this?

This is a helm chart

# Why it exists?

Details about the meaning of life go here :)


