# Docker grafana official + prometheus on alpine

Prometheus build in Alpine 3.16.
Graffana official image

## Install

### Step 1: Change config

Change configuration in ``prometheus/prometheus.yml`` for your targets.

### Step 2: Build configuration

Install make.

Build configuraion with command ``make build``.

## Step 3: Configure and manage

Use ``make help`` for display all supported commands.