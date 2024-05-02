# Wprm System

Sistema unificado para atender vários públicos.


# Submodules Flow
```sh
# Add submodule
git submodule add https://github.com/wprm-system/public-assets.git ./assets

# Update all submodules to last commit
git submodule update --remote --merge
git add .
git commit -m "Update submodules to latest commit"
git push

# Get last changes root and all submodules
git pull
git submodule update
```