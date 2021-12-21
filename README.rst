.. image:: https://img.shields.io/pypi/l/colin-mico.svg
    :target: https://github.com/jupiters1117/ConeOpt/master/LICENSE
    :alt: License

ConeOpt: Counterfactual Explanations with Optimization
------------------------------------------------------
**ConeOpt** is a Python package that implements an optimization based conterfactual explanations for any machine learning estimator.

Installation
------------

1. Create a Python env adn then activate it.

.. code-block:: bash

    conda create -p ./env39 python=3.9 --yes
    conda activate ./env39    

2. To install reuqired packages, use:

.. code-block:: bash

    pip install -r requirements.txt

3. To test **ConeOpt**, run notebook and open the file: ``POC2.ipynb``.

.. code-block:: bash

    jupyter notebook

4. To test **Alibi**, follow the instruction `here <https://docs.seldon.io/projects/alibi/en/latest/overview/getting_started.html>`_ to install the package. Then open ``alibi/examples/cfproto_mnist.ipynb``to test the Counterfactual Analysis. Detailed explanation of the implementaiton can be found `here <https://docs.seldon.io/projects/alibi/en/latest/methods/CFProto.html>`_.

Other related documentations can be found `here <https://arxiv.org/search/cs?searchtype=author&query=Van+Looveren%2C+A>`_.