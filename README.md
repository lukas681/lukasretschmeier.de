# lukasretschmeier.de
My Homepage, www.lukasretschmeier.de

# Cloning the Repo

Make sure to clone the repo with the corresponding submodule correspondingly

     git clone --recurse-submodules https://github.com/lukas681/lukasretschmeier.de

# Updating submodule

In order to fetch the latest submodule, clone the repo and call git

    cd themes
    git submodule sync
    git submodule update --recursive --remote --force
    git add *
    git commit -m "Updated Modules"
    git push
  
 
