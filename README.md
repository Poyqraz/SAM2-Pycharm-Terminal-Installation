# META's SAM2-Pycharm-Terminal-Installation

First we need a env.
  python -m venv sam
Windows: sam\Scripts\activate
macOS ve Linux: source sam/bin/activate

  pip install -r requirements.txt
  pip install setuptools
  pip install wheel
  pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu124
  pip install --no-build-isolation -e .
