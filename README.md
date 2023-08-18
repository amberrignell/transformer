# transformer
first pass at building a simple transformer from scratch

1. Install miniconda
```sh
$ wget -P ~/ https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
$ chmod +x ~/Miniconda3-latest-Linux-x86_64.sh
$ ~/Miniconda3-latest-Linux-x86_64.sh -b
$ export PATH=~/miniconda3/bin:$PATH
$ conda init
# IMPORTANT: close and start a new session
$ conda config --set auto_activate_base false
```

2. Check it works
```sh
$ conda env list
$ conda create --name tiny python=3.8 -y
$ conda activate tiny
$ conda install -y pytorch torchvision cpuonly -c pytorch
```

3. Install requirements
`$ pip install -r requirements.txt`
