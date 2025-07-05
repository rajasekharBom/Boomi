# GitHub → Boomi Trigger Integration

This repo uses GitHub Actions to trigger a Boomi AtomSphere process using the ProcessExecution REST API.

## Usage

1. Go to Actions → Run workflow.
2. Enter:
   - Environment (`DEV`, `QA`, `PROD`)
   - Run ID (any string like `build-20250627`)
3. Click Run Workflow

## Secrets

Make sure these secrets are added under repository settings:

- BOOMI_USERNAME
- BOOMI_PASSWORD
- BOOMI_ACCOUNT_ID
- BOOMI_ATOM_ID
- BOOMI_PROCESS_ID
