# Solidproject.org

Official website of the Solid Project

## App inclusion and exclusion criteria for Solid App Listing

The criteria for an app to be Solid-compatible are:
* If identifying users is necessary, they must be able to log in using their WebID and pointing to the Identity Provider of their choice
* Data consumed by the app should be fetched from Solid Pods if possible
* Data generated by the app should be stored in Solid Pods
* The interaction between the app, pods, and Identity Provider(s) must be compliant with the Solid specification

Please note that apps falling into the following categories will not be listed on this page, even if they match the criteria above:
* Apps intentionally or indirectly causing harm to anyone
* Apps with a purpose that could be widely considered unethical
* Apps designed to enable the generation and/or dissemination of hate speech
* Apps encouraging stereotypes or violent behaviours towards any person or group
* Apps having malicious intent, such as data theft
* Apps designed to fulfill illegal purposes, such as drug traffic, stolen information exchange, extorsion...
* Apps sharing user information with any third-party without user consent
* Apps that have been reported to have important technical or security issues that compromise its users' Pods

Want to add an eligible Solid-compatible app to this list? Contact the Solid Manager via info@solidproject.org or [submit a pull request](https://github.com/solid/solidproject.org/edit/main/pages/use-solid/apps.md).

## Local Environment Setup

This website is built using [Jekyll](https://jekyllrb.com/), a static
site generator.

If you have [Docker Compose](https://docs.docker.com/compose/) installed, view `docker-compose up` to start a local server to view the website.

Alternatively, you can install and run the required tooling manually as follows:
1. [Install](https://jekyllrb.com/docs/installation/) Ruby and Jekyll
1. `$ git clone https://github.com/solid/solidproject.org.git`
1. `$ cd solidproject.org` 
1. `$ bundle install`
1. `$ bundle exec jekyll serve --livereload`
