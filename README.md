# IPFS Add Folder

Recursively upload a folder to IPFS.

## Usage

```
npx ipfs-add-folder <project-directory> <ipfs-node-url> 
```

### Pinning Files & Folders

If you wish to `pin` the added files and folders you can use the `--pin` (or `-p`) option:

```
npx ipfs-add-folder <project-directory> <ipfs-node-url> --pin
```

### Quiet Execution

When the root hash created by the `add` operation is required for later operations (such as registering it in IPNS), you can use the `--quiet` (or `-q`) option:

```
npx ipfs-add-folder <project-directory> <ipfs-node-url> --quiet
```