# Awesome Heroku [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/brandonhimpfen/awesome-lists)

[![DOI](https://zenodo.org/badge/1115457144.svg)](https://doi.org/10.5281/zenodo.19673377)  
[![GitHub Sponsor](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/brandonhimpfen) &nbsp; 
[![Buy Me a Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://buymeacoffee.com/brandonhimpfen) &nbsp; 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/brandonhimpfen) &nbsp; 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://paypal.me/brandonhimpfen)

📌 This repository is archived with Zenodo and can be cited using the DOI above.

> A curated list of platforms, tools, buildpacks, add-ons, workflows, and learning resources for building, deploying, and scaling applications on **Heroku**.

_Support ongoing maintenance and curation via [GitHub Sponsors](https://github.com/sponsors/brandonhimpfen)._

## Contents

- [Official Resources](#official-resources)
- [CLI, Tooling & Workflow](#cli-tooling--workflow)
- [Buildpacks & Runtimes](#buildpacks--runtimes)
- [Databases & Storage Add-ons](#databases--storage-add-ons)
- [Caching, Queues & Messaging](#caching-queues--messaging)
- [Monitoring, Logging & Observability](#monitoring-logging--observability)
- [Security, Auth & Compliance](#security-auth--compliance)
- [CI/CD & Automation](#cicd--automation)
- [Frameworks & Starters](#frameworks--starters)
- [Scaling & Performance](#scaling--performance)
- [Learning Resources](#learning-resources)
- [Related Awesome Lists](#related-awesome-lists)

## Official Resources

- [Heroku Platform](https://www.heroku.com/) – Cloud platform for deploying, managing, and scaling applications.
- [Heroku Dev Center](https://devcenter.heroku.com/) – Official documentation for Heroku features and workflows.
- [Heroku Status](https://status.heroku.com/) – Real-time service status and incident reporting.
- [Heroku Changelog](https://devcenter.heroku.com/changelog) – Updates and changes to the Heroku platform.
- [Heroku Architecture](https://devcenter.heroku.com/articles/heroku-architecture) – Overview of dynos, routing, and platform design.

## CLI, Tooling & Workflow

- [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli) – Command-line interface for managing apps, add-ons, and deployments.
- [Heroku Dashboard](https://dashboard.heroku.com/) – Web UI for app configuration, logs, and metrics.
- [Heroku Git](https://devcenter.heroku.com/articles/git) – Native Git-based deployment workflow.
- [Heroku Pipelines](https://devcenter.heroku.com/articles/pipelines) – Promotion-based workflow for staging and production.
- [Review Apps](https://devcenter.heroku.com/articles/github-integration-review-apps) – Automatic ephemeral environments for pull requests.

## Buildpacks & Runtimes

- [Heroku Buildpacks](https://devcenter.heroku.com/articles/buildpacks) – Scripts for compiling apps into runnable slugs.
- [Heroku Node.js Buildpack](https://github.com/heroku/heroku-buildpack-nodejs) – Official buildpack for Node.js applications.
- [Heroku Python Buildpack](https://github.com/heroku/heroku-buildpack-python) – Official buildpack for Python and Django/Flask apps.
- [Heroku Ruby Buildpack](https://github.com/heroku/heroku-buildpack-ruby) – Buildpack for Ruby and Rails applications.
- [Heroku Java Buildpack](https://github.com/heroku/heroku-buildpack-java) – Buildpack for Java, Spring Boot, and JVM apps.
- [Heroku PHP Buildpack](https://github.com/heroku/heroku-buildpack-php) – Official PHP runtime for Heroku.
- [Container Registry & Runtime](https://devcenter.heroku.com/articles/container-registry-and-runtime) – Docker-based deployment support.

## Databases & Storage Add-ons

- [Heroku Postgres](https://www.heroku.com/postgres) – Managed PostgreSQL database with backups and scaling.
- [Heroku Data for Redis](https://elements.heroku.com/addons/heroku-redis) – Managed Redis for caching and queues.
- [Apache Kafka on Heroku](https://www.heroku.com/kafka) – Fully managed Kafka service for event streaming.
- [Heroku Data for Memcached](https://elements.heroku.com/addons/memcachier) – Distributed caching using Memcached.
- [Amazon S3 Add-ons](https://elements.heroku.com/) – Third-party integrations for object storage.

## Caching, Queues & Messaging

- [Heroku Redis](https://elements.heroku.com/addons/heroku-redis) – In-memory data store for caching and background jobs.
- [Sidekiq](https://sidekiq.org/) – Background job processing for Ruby apps using Redis.
- [Celery](https://docs.celeryq.dev/) – Distributed task queue commonly used with Python apps on Heroku.
- [RQ](https://github.com/rq/rq) – Simple Redis-backed job queue for Python.
- [Apache Kafka](https://www.heroku.com/kafka) – Event streaming platform for real-time data pipelines.

## Monitoring, Logging & Observability

- [Heroku Logs](https://devcenter.heroku.com/articles/logging) – Centralized logging system accessible via CLI and add-ons.
- [Heroku Metrics](https://devcenter.heroku.com/articles/metrics) – Built-in application and system metrics.
- [Papertrail](https://elements.heroku.com/addons/papertrail) – Log aggregation and search for Heroku apps.
- [Datadog](https://elements.heroku.com/addons/datadog) – Monitoring and observability platform with Heroku integration.
- [New Relic](https://elements.heroku.com/addons/newrelic) – Application performance monitoring for Heroku-hosted apps.
- [Sentry](https://elements.heroku.com/addons/sentry) – Error tracking and performance monitoring.

## Security, Auth & Compliance

- [Heroku SSL](https://devcenter.heroku.com/articles/ssl) – Automated SSL certificate management for custom domains.
- [Config Vars](https://devcenter.heroku.com/articles/config-vars) – Environment variable management for secrets and settings.
- [Heroku Shield](https://www.heroku.com/shield) – Compliance-focused platform for HIPAA and PCI workloads.
- [OAuth on Heroku](https://devcenter.heroku.com/articles/oauth) – Secure authorization for Heroku Platform API access.
- [Auth0 Add-on](https://elements.heroku.com/addons/auth0) – Authentication and authorization for Heroku applications.

## CI/CD & Automation

- [Heroku CI](https://devcenter.heroku.com/articles/heroku-ci) – Built-in continuous integration for Heroku apps.
- [GitHub Integration](https://devcenter.heroku.com/articles/github-integration) – Automatic deploys from GitHub repositories.
- [Heroku API](https://devcenter.heroku.com/articles/platform-api-reference) – Programmatic management of apps and resources.
- [Terraform Heroku Provider](https://registry.terraform.io/providers/heroku/heroku/latest) – Infrastructure as code for Heroku resources.
- [GitHub Actions for Heroku](https://github.com/marketplace?query=heroku) – CI/CD workflows deploying directly to Heroku.

## Frameworks & Starters

- [Rails on Heroku](https://devcenter.heroku.com/categories/ruby-support) – Official guidance for deploying Rails applications.
- [Django on Heroku](https://devcenter.heroku.com/articles/django-app-configuration) – Best practices for Django deployment.
- [Flask on Heroku](https://devcenter.heroku.com/articles/getting-started-with-python) – Guide for deploying Flask apps.
- [Node.js on Heroku](https://devcenter.heroku.com/articles/getting-started-with-nodejs) – Starter guide for Node.js applications.
- [Spring Boot on Heroku](https://devcenter.heroku.com/articles/deploying-spring-boot-apps-to-heroku) – Java application deployment patterns.

## Scaling & Performance

- [Dynos](https://devcenter.heroku.com/articles/dynos) – Isolated containers for running application processes.
- [Horizontal Scaling](https://devcenter.heroku.com/articles/scaling) – Scale apps by increasing dyno count.
- [Autoscaling](https://devcenter.heroku.com/articles/autoscaling) – Automatically adjust dynos based on load.
- [Performance Dynos](https://www.heroku.com/dynos) – Dedicated compute dynos for production workloads.
- [Preboot](https://devcenter.heroku.com/articles/preboot) – Zero-downtime deploys for web applications.

## Learning Resources

### Tutorials
- [Getting Started on Heroku](https://devcenter.heroku.com/start) – Official quickstarts for supported languages.
- [Heroku Dev Center Tutorials](https://devcenter.heroku.com/categories/tutorials) – Step-by-step guides for common tasks.
- [Deploying with Docker on Heroku](https://devcenter.heroku.com/articles/container-registry-and-runtime) – Guide for container-based deployments.

### Guides
- [Heroku Best Practices](https://devcenter.heroku.com/articles/best-practices) – Recommendations for secure and scalable apps.
- [Twelve-Factor App](https://12factor.net/) – Methodology that inspired Heroku’s platform design.
- [Heroku Security Guide](https://devcenter.heroku.com/articles/security) – Security concepts and platform protections.

### Courses
- *Deploying Production Apps on Heroku* – Practical course on Heroku workflows.
- *Rails + Heroku in Production* – Course focused on Ruby on Rails deployment.
- *Python Web Apps on Heroku* – End-to-end Flask/Django deployment training.

## Related Awesome Lists

- [Awesome Cloud](https://github.com/brandonhimpfen/awesome-cloud)
- [Awesome SaaS](https://github.com/brandonhimpfen/awesome-saas)
- [Awesome Rails](https://github.com/brandonhimpfen/awesome-rails)
- [Awesome Flask](https://github.com/brandonhimpfen/awesome-flask)
- [Awesome Docker](https://github.com/brandonhimpfen/awesome-docker)

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
