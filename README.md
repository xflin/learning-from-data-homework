# "Learning From Data" Homeworks

Parts of my "Learning from Data" homework exercises using Jupyter IPython Notebooks.

## Jupyter Installation (on Mac OS X)

### Install Homebrew
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

### Install Everything Else (to ~/jupyter)
```
export VENVPATH=~/jupyter

brew install python3 --framework
pip3 install --upgrade pip setuptools wheel
virtualenv $VENVPATH
source $VENVPATH/bin/activate
pip install jupyter pandas

Install matplotlib:
# Issue as documented: https://github.com/matplotlib/matplotlib/issues/3029
brew install freetype pkg-config
pip install matplotlib

# Install SciPy
brew install gcc
pip install scipy

pip install scikit-learn
```
