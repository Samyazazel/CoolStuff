# CoolStuff

Copies of other people's GitHub projects worth keeping.

Each project keeps its own history. Its branches are stored here as `<project>/<branch>` and its
tags as `<project>/<tag>`. This `main` branch holds only this index.

## Get one project

```powershell
git clone -b rea/main --single-branch https://github.com/Samyazazel/CoolStuff.git rea
```

## Update a copy

```bash
git fetch https://github.com/morluto/rea "refs/heads/main:refs/heads/rea/main" "refs/tags/*:refs/tags/rea/*"
git push origin "refs/heads/rea/main" "refs/tags/rea/*"
```

Run it in a clone of this repo. Only branches and tags are copied; releases, issues and pull
requests stay on the original.

## Projects

| Project | Source | License | Branches | Tags |
|---|---|---|---|---|
| `rea` | [morluto/rea](https://github.com/morluto/rea) | MIT | `rea/main` | all 40 upstream tags as `rea/<tag>`, e.g. `rea/rea-agents-6.8.0` |
