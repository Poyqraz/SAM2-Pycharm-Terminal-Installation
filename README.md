# META's SAM2-Pycharm-Terminal-Installation


    $ python -m venv sam
  
    Windows: $ sam\Scripts\activate

    macOS ve Linux: $  source sam/bin/activate

    $ pip install -r requirements.txt
  
    $ pip install setuptools
  
    $ pip install wheel
  
    $ pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu124
  
    $ pip install --no-build-isolation -e .

Download and Install Microsoft Visual C++ Build Tools: https://visualstudio.microsoft.com/tr/visual-cpp-build-tools/

    Install Ninja (Optional but Recommended) Ninja is a small build system with a focus on speed: $ pip install ninja

    $ python setup.py build_ext --inplace

    $ pip install supervision
