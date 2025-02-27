## Install Conda and Unsloth
- wget https://repo.anaconda.com/archive/Anaconda3-2024.10-1-Linux-x86_64.sh
- bash Anaconda3-2024.10-1-Linux-x86_64.sh
- restart terminal
- conda create --name unsloth_env python=3.11 pytorch-cuda=12.1 pytorch cudatoolkit xformers -c pytorch -c nvidia -c xformers -y
- conda activate unsloth_env
- pip install "unsloth[colab-new] @ git+https://github.com/unslothai/unsloth.git"
- pip install --no-deps trl peft accelerate bitsandbytes
