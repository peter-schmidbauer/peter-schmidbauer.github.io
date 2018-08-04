# PSDS (Peter's Blog)

## Publishing

All work needs to be done on the `dev` branch. 
When you want to publish your results, use the following commands:

    pelican content -s publishconf.py
    ghp-import output -b master
    git push origin --all
    
This should trigger a build and publish your site on https://peter-schmidbauer.github.io.


## Theme

The theme I'm using currently is maintained by Jody Frankowski, 
you can find it at https://github.com/jody-frankowski/blue-penguin.