# Wprm System

Sistema unificado para atender vários públicos.


# Submodules Flow

```sh
# Clone with submodules
git clone --recurse-submodules git://github.com/foo/bar.git

# Get submodules after clone
git submodule update --init --recursive

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