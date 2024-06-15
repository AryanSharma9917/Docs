# Codewise-CLI Docs

## Introduction

Codewise-CLI is a CLI tool that provides a basic set of commands to perform tedious tasks such as converting YAML to JSON or JSON to YAML directly from your terminal. It's built with Go, Cobra, Viper, etc.

## Getting Started

For installation, updating, and usage instructions, see the [Getting Started](getting-started.md) page.

## Documentation

We have broken down the documentation into multiple sections for different commands for better understanding.

### Commands

#### YTJ - YAML to JSON

It will convert YAML to JSON. It takes a YAML file as input and converts it to JSON and saves the output in a file in the current directory.

Check out the [YTJ](docs/ytj.md) page for a detailed explanation.

#### JTY - JSON to YAML

It will convert JSON to YAML. It takes a JSON file as input and converts it to YAML and saves the output in a file in the current directory.

Check out the [JTY](docs/jty.md) page for a detailed explanation.

#### KVTJ - Key Value to JSON

It will convert Key-Value pair to JSON. It takes a Key Value file as input and converts it to JSON and saves the output in a file in the current directory.

Check out the [KVTJ](docs/kvtj.md) page for a detailed explanation.

#### docker

It will provide a set of commands to perform Docker-related tasks, like generating Dockerfile, docker-compose file, etc.

Check out the [docker](docs/docker.md) page for a detailed explanation.

#### k8s - Kubernetes

It will provide a set of commands to perform Kubernetes-related tasks, like generating deployment, service, etc.

Check out the [k8s](docs/k8s.md) page for a detailed explanation.
