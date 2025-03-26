.. meta::
  :description: introduction to the hipSPARSE documentation and API reference library
  :keywords: hipSPARSE, rocSPARSE, ROCm, API, documentation

.. _hipsparse:

********************************************************************
hipSPARSE documentation
********************************************************************

hipSPARSE provides basic linear algebra subroutines
for sparse computation. It's written in :doc:`HIP <hip:index>`, implemented on top
of the AMD ROCm runtime and toolchains, and optimized for AMD discrete GPUs.
hipSPARSE is a SPARSE marshalling library that supports both :doc:`rocSPARSE <rocsparse:index>` and NVIDIA CUDA cuSPARSE as backends.
For more information, see :doc:`What is hipSPARSE? <./what-is-hipsparse>`

The hipSPARSE public repository is located at `<https://github.com/ROCm/hipSPARSE>`_.

.. grid:: 2
  :gutter: 3

  .. grid-item-card:: Install
  
    * :doc:`Installation guide <./install/install>`
  
  .. grid-item-card:: How to
  
    * :doc:`Use hipSPARSE <./howto/using-hipsparse>`

  .. grid-item-card:: Examples

    * `Client samples <https://github.com/ROCm/hipSPARSE/tree/develop/clients/samples>`_

  .. grid-item-card:: API reference
  
    * :doc:`Exported functions <./reference/api>`
    * :doc:`hipSPARSE datatypes <./reference/types>`
    * :doc:`Sparse auxiliary functions <./reference/auxiliary>`
    * :doc:`Sparse level 1 functions <./reference/level1>`
    * :doc:`Sparse level 2 functions <./reference/level2>`
    * :doc:`Sparse level 3 functions <./reference/level3>`
    * :doc:`Sparse extra functions <./reference/extra>`
    * :doc:`Preconditioner functions <./reference/precond>`
    * :doc:`Sparse conversion functions <./reference/conversion>`
    * :doc:`Sparse reordering functions <./reference/reorder>`
    * :doc:`Sparse generic functions <./reference/generic>`

To contribute to the documentation, see `Contributing to ROCm <https://rocm.docs.amd.com/en/latest/contribute/contributing.html>`_.

You can find licensing information on the `Licensing <https://rocm.docs.amd.com/en/latest/about/license.html>`_ page.


