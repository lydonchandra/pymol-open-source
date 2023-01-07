# Ubuntu Build Extra steps

1. `sudo apt-get install git build-essential python3-dev libglew-dev \
  libpng-dev libfreetype6-dev libxml2-dev \
  libmsgpack-dev python3-pyqt5.qtopengl libglm-dev libnetcdf-dev`
2. `pip install pyqt5`
3. `export PREFIX_PATH="/usr"`
4. `prefix=$HOME/pymol-open-source-build`
5. `python3 setup.py build install --home=$prefix`