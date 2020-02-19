# reproducibility-tutorial
FOSS 2020
## Clone the github repo
    5  git clone https://github.com/goalmeida/reproducibility-tutorial.git
## Install conda
   19  wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
   20  bash Miniconda3-latest-Linux-x86_64.sh -b -p /opt/conda
## Create Links
   32  ln -s /opt/conda/pkgs/*/bin/* /bin
   33  ln -s /opt/conda/pkgs/*/lib/* /usr/lib
   34  ln -s /opt/conda/pkgs/*/lib/* /usr/lib
   35  ln -s /opt/conda/pkgs/*/lib/* /usr/lib
   36  ln -s /opt/conda/pkgs/*/lib/* /usr/lib
   37  conda install -c conda-forge -y jupyterlab=1.2.3
   38  /opt/conda/bin/conda install -c conda-forge -y jupyterlab=1.2.3
   39  /opt/conda/bin/conda install -c conda-forge -y nodejs=10.13.0
   40  ls
   41  ls -l
   42  /opt/conda/bin/pip install bash_kernel
   43  /opt/conda/bin/pip install ipykernel
   44  /opt/conda/bin/python3 -m bash_kernel.install
   45  cls
   46  clear
   47  /opt/conda/bin/conda search htseq
   48  /opt/conda/bin/conda search -c bioconda htseq
   49  find conda
   50  /opt/conda/bin/conda search -c bioconda htseq
   51  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   52  /opt/conda/bin/conda search -c bioconda snakemake
   53  /opt/conda/bin/conda install -c bioconda -c conda-forge -y snakemake=5.8.1
   54  ln -s /opt/conda/bin/* /bin
   55  ln -s /opt/conda/lib/* /usr/lib
   56  snakemake --version
   57  sudo apt-get update
   58  sudo apt-get update
   59  sudo apt-get update
   60  sudo apt-get install -y apt-transport-https ca-certificates curl gnupg-agent software-properties-common
   61  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
   62  sudo add-apt-repository  "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
 $(lsb_release -cs) \
 stable"
   63  sudo apt-get update
   64  sudo apt-get install -y docker-ce docker-ce-cli containerd.io
   65  docker run hello-world
   66  ls
   67  cd reproducibility-tutorial/
   68  ls
   69  ls -l
   70  history 
   71  history >> README.md 
