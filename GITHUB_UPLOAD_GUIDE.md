# GitHub upload guide

## Create the repository

1. Sign in to GitHub.
2. Select **New repository**.
3. Use the repository name `cell-migration-surrogate-models`.
4. Add the description: `Probabilistic neural and structured hybrid surrogates for phenotype-aware cell migration under interstitial flow.`
5. Choose **Public**.
6. Do not initialize the repository with another README, license, or `.gitignore`; they are already included here.
7. Select **Create repository**.

## Upload the files in the browser

1. On the empty repository page, select **uploading an existing file**.
2. Open the extracted `cell-migration-surrogate-models` folder.
3. Drag all files and folders into the GitHub upload window.
4. Use the commit message `Add surrogate modeling project`.
5. Select **Commit changes**.

## Verify the repository

Confirm that GitHub displays:

- `README.md`
- `surrogate_digital_twin.ipynb`
- `figures/hybrid_colony_validation.png`
- the two CSV files under `outputs/`
- `requirements.txt`
- `CITATION.cff`
- `LICENSE`

Do not upload `.pt` checkpoint files through the standard browser uploader. They are excluded by `.gitignore`. If public checkpoint distribution becomes necessary, attach them to a versioned GitHub Release and include checksums.

