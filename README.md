- 👋 Hi, I’m @ak3605424
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
from __future__ import print_function
    import configparser
except ImportError:
    import ConfigParser as configparser
import errno
import json
import os
import re
import subprocess
import sys
class VersioneerConfig:
    """Container for Versioneer configuration parameters."""


def get_root():
    """Get the project root directory.
    We require that all commands are run from the project root, i.e. the
    directory that contains setup.py, setup.cfg, and versioneer.py .
    """
    root = os.path.realpath(os.path.abspath(os.getcwd()))
    setup_py = os.path.join(root, "setup.py")
    versioneer_py = os.path.join(root, "versioneer.py")
    if not (os.path.exists(setup_py) or os.path.exists(versioneer_py)):
        # allow 'python path/to/setup.py COMMAND'
        root = os.path.dirname(os.path.realpath(os.path.abspath(sys.argv[0])))
        setup_py = os.path.join(root, "setup.py")
        versioneer_py = os.path.join(root, "versioneer.py")
    if not (os.path.exists(setup_py) or os.path.exists(versioneer_py)):
        err = ("Versioneer was unable to run the project root directory. "
               "Versioneer requires setup.py to be executed from "
               "its immediate directory (like 'python setup.py COMMAND'), "
               "or in a way that lets it use sys.argv[0] to find the root "
               "(like 'python path/to/setup.py COMMAND').")
        raise VersioneerBadRootError(err)
<!---
ak3605424/ak3605424 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
