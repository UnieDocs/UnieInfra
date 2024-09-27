.. _installation:

Installation
============

UnieInfra is the AI platform developed by UnieAI.

Requirements
------------

* **OS**: Linux
* **Python**: 3.8
* **GPU**: compute capability 7.0 or higher (e.g., V100, T4, RTX20xx, A100, L4, H100, etc.)
* **Network**: Ensure your environment can access the public network. After successfully deploying UnieInfra, the service can operate in a private network environment.

Pull Docker Images
~~~~~~~~~~~~~~~~~~

UnieInfra offers official Docker images for deployment.
The image can be used to run OpenAI compatible server and is available on Docker Hub as `unieinfra <https://hub.docker.com/repositories/unieai>`_.

.. code-block:: console

    $ docker image pull unieai/unie_license
    $ docker image pull unieai/unie_controller
    $ docker image pull unieai/unie_api_server
    $ docker image pull unieai/unie_worker

.. note::

    You will require a license key to operate the UnieInfra platform.
    The license key follows the format ``UUUUUU-NNNNNN-IIIIII-EEEEEE-XXXXXX-AI``.
