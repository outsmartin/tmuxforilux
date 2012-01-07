    git clone https://outsmartin@github.com/outsmartin/tmuxforilux.git local

put the export in your .bashrc or something similar:

    echo 'export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:$HOME/local/lib' >> ~/.profile

    echo 'export PATH=$HOME/local/bin:$PATH' >> ~/.profile

