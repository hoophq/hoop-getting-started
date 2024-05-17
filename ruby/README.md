# README

This example contains a quick start of how to run Hoop with a Ruby on Rails application.

See more details in the following documentation:

- https://hoop.dev/docs/connections/ruby-on-rails
- https://hoop.dev/docs/quickstarts/compose-with-rails

## Rails Console Access

It creates a Hoop connection resource with name `railsc-demo`

```sh
export HOOP_KEY=<YOUR_KEY>
docker compose -f docker-compose.yaml up
```

## Rails Ad Hoc Executions

It creates a Hoop connection resource with name `rails-adhoc-demo`

```sh
export HOOP_KEY=<YOUR_KEY>
docker compose -f docker-compose.yaml up
```

## Agent Embedded with Rails Application

It creates a Hoop connection resource with name `railsc-embedded-demo`

```sh
export HOOP_KEY=<YOUR_KEY>
docker compose -f docker-compose-embedded.yaml up
```
