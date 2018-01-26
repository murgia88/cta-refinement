This tool implements the theory of "Compositional asynchronous timed refinement"
by Massimo Bartoletti, Laura Bocchi and Maurizio Murgia.

(1) Installation instructions (Ubuntu only)
-------------------------------------------

(a) Install the python DBM binding, following the instructions 
in http://people.cs.aau.dk/~adavid/UDBM/python.html. 

Tips:
When installing the required Uppaal DBM Library (http://people.cs.aau.dk/~adavid/UDBM/), call: 
AR=ar ./configure
instead of ./configure.
For 64 bit architectures only, add the flag -fPIC to 
export CFLAGS :=  -DBOOST_DISABLE_THREADS in the makefile.

(b) Install Parglare (https://github.com/igordejanovic/parglare), running:
pip install parglare

(c) Install Graphviz (https://www.graphviz.org/), running:
sudo apt-get install graphviz

(d) Install graphviz (http://graphviz.readthedocs.io/en/stable/index.html), running:
pip install graphviz


(2) Running the tool
--------------------

The tool can be run with command: ./run.py <script_name>.
# cta-refinement
