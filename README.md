# AI DevOps Platform

A self-hosted AI platform built using Infrastructure as Code principles.

## Goals

* Deploy and manage open-source LLM infrastructure
* Automate deployments using Ansible
* Maintain configuration in Git
* Integrate with operational tooling such as n8n, Prometheus, and Grafana
* Build a searchable engineering knowledge base using retrieval-augmented generation (RAG)

## Initial Stack

* Ollama
* Open WebUI
* Docker Compose
* Ansible

## Future Enhancements

* Qdrant
* n8n AI workflows
* Prometheus monitoring
* Grafana dashboards
* GitHub Actions CI/CD
* Kubernetes deployment

## Architecture

Workstation → Git → Ansible → VPS → Docker → AI Services

## Status

Phase 1: Repository Initialization
