# bin

Personal CLI utilities.

## declutter

Force-deletes all local git branches except `main` and `demo`.

```bash
# Delete everything except main and demo
declutter

# Keep additional branches
declutter --keep feature-x --keep hotfix
```

### Options

| Flag | Description |
|------|-------------|
| `--keep <branch>` | Protect an additional branch from deletion. Can be used multiple times. |

`main` and `demo` are always protected and do not need to be specified.
