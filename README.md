FCIQMC interface
================

2021-02-27

* Version 0.1

Install
-------
* Install to python site-packages folder
```
pip install git+https://github.com/pyscf/fciqmcscf
```

* Install in a custom folder for development
```
git clone https://github.com/pyscf/fciqmcscf /home/abc/local/path

# Set pyscf extended module path
echo 'export PYSCF_EXT_PATH=/home/abc/local/path:$PYSCF_EXT_PATH' >> ~/.bashrc
```

You can find more details of extended modules in the document
[extension modules](https://pyscf.org/install.html#extension-modules)

* Using FCIQMC as the FCI solver for CASSCF. The FCIQMC program is maintained by
  Booth group at Cambridge

      NECI (https://github.com/ghb24/NECI_STABLE)

  After installing the NECI, the path of its binary file needs to be added to
  pyscf/fciqmcscf/settings.py
