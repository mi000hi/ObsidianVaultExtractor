# ObsidianVaultExtractor
Extracts all linked files and attachments from an obsidian vault when providing a master markdown file

## Usage
- install `jupyter` using `pip install jupyter`
- run `jupyter-notebook`
- customize the variables in the second to last cell
- execute the cells in the notebook

## Settings

**parent_directory**: the absolute path to the vault directory, only files from this directory are copied  
**new_location**: the absolute path to the newly created sub-vault directory  
**root_markdown**: MD filename of the root file to search for linked files  
**ignore_files**: MD filenames that are ignored and not searched nor copied  
**ignore_prefixes**: Trailing 10 (by default) characters before a filelink, that if present, do not search nor copy the following linked file

## Disclaimer

In case of doubt, ask :) You could easily mess up your Obsidian Vault if the `new_location` path is set inappropriate. I do not take any responsibility. Make sure this path points to outside of the existing Vault!
