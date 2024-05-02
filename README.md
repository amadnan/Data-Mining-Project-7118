# Data-Mining-Project-7118
Course Project
All the required libraries can be installed from code command
# Special Note
For Prophet python==3.8, pystan==2.19 
still facing issues try this:
""
!wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
# Download Miniconda installer for Linux
!wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh

# Install Miniconda silently (-b: batch mode, -p: prefix/path)
!chmod +x Miniconda3-latest-Linux-x86_64.sh
!bash ./Miniconda3-latest-Linux-x86_64.sh -b -f -p /usr/local

# Update the path environment variable
import sys
sys.path.append('/usr/local/lib/python3.8/site-packages/')

# Install Python 3.8 using conda
!conda install -c anaconda python=3.8 -y

# Verify the Python version
!python --version
!pip install ephem
!pip install prophet
import sys
sys.path.append('/usr/local/lib/python3.8/site-packages/')

""

Dataset:
Change file path accordingly ( I did this on google colab so remove those lines if you are running on local host)
