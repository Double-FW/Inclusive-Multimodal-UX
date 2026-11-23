# GitHub to Hugging Face dataset sync

Source: https://github.com/Double-FW/Inclusive-Multimodal-UX  
Destination: https://huggingface.co/datasets/GarethFW/Inclusive_Multimodal_UX

## One-time owner setup

The workflow needs a Hugging Face token with write access to this dataset. Do not share the token in chat or put it in a file.

1. In Hugging Face token settings, create a fine-grained token for only `GarethFW/Inclusive_Multimodal_UX` and grant read and write access. A token scoped only to another dataset will not work.
2. In the GitHub source repository, open **Settings → Secrets and variables → Actions → New repository secret**.
3. Name the secret `HF_TOKEN`, paste the token into the secret value, and save.
4. Confirm this setup has been merged into the default `main` branch.
5. Open **Actions → Sync Inclusive Multimodal UX dataset → Run workflow**, select `main`, and inspect the result.
6. Confirm the run succeeds and check the Hugging Face dataset’s **Files and versions** page for the source revision.

The destination is fixed in the reviewed export configuration. The workflow writes only to this dataset.

## Ongoing behaviour

- A push to `main` that changes an approved source document, exporter, configuration, README, licence, or workflow triggers a sync.
- A scheduled sync also runs every Monday at 07:23 UTC. GitHub may delay scheduled runs.
- A manual workflow run is available.
- Pull requests do not publish; publication is restricted to the default branch.
- If no managed files changed, the workflow creates no Hugging Face commit.
- One commit updates the dataset card, MIT licence copy, full-document and section JSONL files, provenance, schema, and export manifest. Unrelated destination files and dataset visibility are preserved.
- The export contains README and AGENTS as context plus four active guidance documents. The full-document and section views overlap by design; migration notices and specialist-owned content are not separately duplicated.
- The GitHub source must remain public. The workflow uses GitHub’s read-only token to check that status; `HF_TOKEN` is available only to the publishing step.

If a run fails, read its workflow log. Common causes include a missing or incorrectly scoped token, an uninitialised destination, or a changed source allowlist. Never paste credentials into an issue, commit, log, or chat.
