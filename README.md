# Awesome Nomad with stars

A curated list of amazingly awesome Nomad tools and shiny things.

Pull requests with additional tools and projects are more than welcome!

## User interfaces

* [hashicorp/damon](https://github.com/hashicorp/damon) ⭐ 488 | 🐛 10 | 🌐 Go | 📅 2026-08-24 - An early stage terminal dashboard for Nomad.
* [robinovitch61/wander](https://github.com/robinovitch61/wander) ⭐ 481 | 🐛 4 | 🌐 Go | 📅 2024-06-18 - A terminal UI for Nomad.

## Autoscaling

* [hashicorp/nomad-autoscaler](https://github.com/hashicorp/nomad-autoscaler/) ⭐ 477 | 🐛 73 | 🌐 Go | 📅 2026-09-14 - HashiCorp's official Nomad Autoscaler. Supports scaling allocations within Nomad and scaling nodes on AWS, Azure, GCP, or arbitrary infrastructure via plugins.
* [lucretius/nomad-elastigroup-autoscaler](https://github.com/lucretius/nomad-elastigroup-autoscaler) ⭐ 1 | 🐛 0 | 🌐 Go | 📅 2021-07-28 - Nomad Autoscaler plugin for [Spot.io Elastigroup](https://spot.io/products/elastigroup/).

## CI / CD

* [hashicorp/levant](https://github.com/hashicorp/levant) ⚠️ Archived - A templating and deployment tool for HashiCorp Nomad jobs that provides realtime feedback and detailed failure messages upon deployment issues.
* [nomad-ops/nomad-ops](https://github.com/nomad-ops/nomad-ops) ⭐ 113 | 🐛 10 | 🌐 TypeScript | 📅 2025-06-10 - A simple way to deploy workloads via GitOps. Similar to ArgoCD with a UI.
* [jenkinsci/nomad-plugin](https://github.com/jenkinsci/nomad-plugin) ⭐ 59 | 🐛 21 | 🌐 Java | 📅 2024-02-12 - Jenkins plugin to allow using Nomad Jobs to scale out Jenkins build slaves.
* [sunshard-prism/prism-nomad)](https://github.com/sunshard-prism/prism-nomad) ⭐ 18 | 🐛 0 | 🌐 Go | 📅 2025-02-28 - Prism is a tool that simplifies the creation of Nomad job configuration templates and deploys them to a remote cluster.
* [gerrowadat/nomad-gitops](https://github.com/gerrowadat/nomad-gitops) ⭐ 1 | 🐛 1 | 🌐 Go | 📅 2026-09-16 - Another implementation of 'gitops' style drift detection and deployment for Nomad.
* [getnelson/nelson](https://getnelson.io/) - Lights-out deployment and lifecycle manager for Nomad (and other pluggable schedulers). Fully integrated with Vault and Consul. Optionally can act as a control plane for your traffic routing teir.
* [hashicorp/setup-nomad-pack](https://github.com/marketplace/actions/setup-hashicorp-nomad-pack) - HashiCorp-maintained GitHub Action for `nomad-pack`.

## Plugins

* [Roblox/nomad-driver-containerd](https://github.com/Roblox/nomad-driver-containerd) ⭐ 242 | 🐛 29 | 🌐 Go | 📅 2025-07-23 - A nomad task driver for [containerd](https://containerd.io). Documentation on [`nomadproject.io`](https://www.nomadproject.io/docs/drivers/external/containerd).
* [Roblox/nomad-driver-iis](https://github.com/Roblox/nomad-driver-iis) ⭐ 62 | 🐛 13 | 🌐 Go | 📅 2025-07-23 - A nomad task driver to run [windows IIS](https://www.iis.net/) tasks.
* [JanMa/nomad-driver-nspawn](https://github.com/JanMa/nomad-driver-nspawn) ⭐ 60 | 🐛 8 | 🌐 Go | 📅 2026-01-05 - A nomad task driver to run containers with [systemd-nspawn](https://www.freedesktop.org/software/systemd/man/systemd-nspawn.html).
* [sevensolutions/nomad-iis](https://github.com/sevensolutions/nomad-iis) ⭐ 26 | 🐛 6 | 🌐 C# | 📅 2026-09-14 - A nomad task driver to run [windows IIS](https://www.iis.net/) tasks.
* [sorenisanerd/nomad-docker-driver-external](https://github.com/sorenisanerd/nomad-docker-driver-external) ⭐ 6 | 🐛 0 | 🌐 Go | 📅 2024-02-01 - External version of the docker driver for Nomad.
* [CarbonCollins/nomad-usb-device-plugin](https://gitlab.com/CarbonCollins/nomad-usb-device-plugin) - A USB device plugin for nomad deployments.
* [Deuxfleurs/nomad-driver-nix2](https://git.deuxfleurs.fr/Deuxfleurs/nomad-driver-nix2) - A driver to run Nix jobs on Nomad.

## Self Service

* TODO

## Job Files and Packs

* [perrymanuk/hashi-homelab](https://github.com/perrymanuk/hashi-homelab) ⭐ 364 | 🐛 8 | 🌐 HCL | 📅 2026-09-16 Job files for a small lightweight homelab based on nomad and consul from hashicorp.
* [hashicorp/nomad-pack-community-registry](https://github.com/hashicorp/nomad-pack-community-registry) ⭐ 242 | 🐛 50 | 🌐 HCL | 📅 2026-07-27 - The official community registry for Nomad Pack templates.

## Utilities

* [jsiebens/hashi-up](https://github.com/jsiebens/hashi-up) ⭐ 694 | 🐛 7 | 🌐 Go | 📅 2023-12-18 - A lightweight utility to install Nomad (and other HashiCorp tools) on any remote Linux host.
* [hashicorp/nomad-pack](https://github.com/hashicorp/nomad-pack) ⭐ 447 | 🐛 60 | 🌐 Go | 📅 2026-09-17 - An official templating tool and package manager for Nomad, currently a Tech Preview.
* [ngine-io/chaotic](https://github.com/ngine-io/chaotic) ⭐ 74 | 🐛 5 | 🌐 Python | 📅 2026-09-16 - Chaos monkey with integrated nomad support. Runs as batch job or service and kills allocations periodically and randomly.
* [mr-karan/nomad-events-sink](https://github.com/mr-karan/nomad-events-sink) ⭐ 55 | 🐛 5 | 🌐 Go | 📅 2023-06-21 - Ships nomad event logs to dedicated sinks
* [Roblox/nomad-node-problem-detector](https://github.com/Roblox/nomad-node-problem-detector) ⭐ 52 | 🐛 0 | 🌐 Go | 📅 2025-07-23 - A tool used to detect problems on Nomad nodes based on user-defined health checks.
* [koyeb/kreconciler](https://github.com/koyeb/kreconciler) ⭐ 51 | 🐛 1 | 🌐 Go | 📅 2026-08-18 - A library for building operators and reconcilers on top of Nomad (or other schedulers).
* [kamilcuk/nomad-tools](https://github.com/Kamilcuk/nomad-tools) ⭐ 43 | 🐛 4 | 🌐 Python | 📅 2026-03-24 - `docker run` for Nomad, watch all logs and events of a job in the terminal, copy files to/from host and allocations, manage Nomad variables as files, list ports associated with job, implementation of [custom `gitlab-runner` executor](https://docs.gitlab.com/runner/executors/custom.html) that executes Gitlab CI/CD jobs as Nomad jobs.
* [mr-karan/nomcfg](https://github.com/mr-karan/nomcfg) ⭐ 18 | 🐛 2 | 🌐 HTML | 📅 2024-07-11 - A ui for generating nomad job specs
* [axsuul/nomad-event-streamer](http://github.com/axsuul/nomad-event-streamer) ⭐ 15 | 🐛 0 | 🌐 Ruby | 📅 2023-08-22 - A tool for sending Nomad events to your favorite destinations like Discord and Slack.
* [let-sh/nomad-deploy-result-action](https://github.com/let-sh/nomad-deploy-result-action) ⭐ 11 | 🐛 1 | 🌐 JavaScript | 📅 2025-02-14 - A GitHub action for automating Nomad deploys with GitOps.
* [dmaes/nomad-logger](https://github.com/dmaes/nomad-logger) ⚠️ Archived - Watch Nomad allocations and update logshipper config.
* [Deuxfleurs/albatros](https://git.deuxfleurs.fr/Deuxfleurs/albatros) - A lightweight and (quasi-)stateless CI built on top of Nomad.

## Tutorials

* [kelseyhightower/hashiconf-eu-2016](https://github.com/kelseyhightower/hashiconf-eu-2016) ⭐ 106 | 🐛 1 | 🌐 Shell | 📅 2016-09-08 - Repo from a talk on building out a deployment with GCE/Consul/Nomad/Fabio loadbalancer. Check out the talk on youtube: <https://www.youtube.com/watch?v=Nosa5-xcATw>
* [anubhavmishra/envoy-consul-sds](https://github.com/anubhavmishra/envoy-consul-sds) ⭐ 67 | 🐛 3 | 🌐 Go | 📅 2023-05-05 - A tutorial on how to get Envoy running on Nomad and using Envoy's SDS(Service Discovery Service) to access Consul API.

## Examples / Demos

* [fhemberger/nomad-demo](https://github.com/fhemberger/nomad-demo) ⚠️ Archived - Vagrant based demo setup for running Hashicorp Consul, Nomad and Vault, including sample apps for Docker, JRE and a basic monitoring setup. Uses Traefik as load balancer to pick up services directly from Consul catalog.
* [pete0emerson/hashipoc](https://github.com/pete0emerson/hashipoc) ⭐ 50 | 🐛 5 | 🌐 Shell | 📅 2022-12-08 - A Vagrant driven example of getting Consul / Vault / Nomad up and running with a sample app deployed

## Other

* [prabirshrestha/synology-nomad](https://github.com/prabirshrestha/synology-nomad) ⭐ 30 | 🐛 3 | 🌐 Shell | 📅 2026-09-10 - HashiCorp Nomad Package for Synology DSM 7+. Includes client and server.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-17._
