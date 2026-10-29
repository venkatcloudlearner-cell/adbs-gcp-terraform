# Oracle ADB-S on Google Cloud with Terraform

Terraform configuration for the VPC, ODB network/client subnet, Autonomous AI Database, and private SQL client VM.

Terraform CLI: 1.16.6. Google provider: 8.9.0.

Use the same private GCS backend for this existing deployment. Never initialize CI with empty state. Provide bucket and prefix during terraform init. Keep credentials, passwords, wallets, state and plans out of Git.

GitHub Actions setup is being added step by step. No deployment workflow is enabled yet.
