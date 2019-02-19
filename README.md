# Bunch of linux helpers/stuff

## Including custom file in .bashrc

    if [ -f $HOME/.bashrc-custom ]; then
        source $HOME/.bashrc-custom
    fi
