.. _update-neuron-tensorflow:

Update to latest Neuron TensorFlow
===============================

.. include:: /neuron-intro/install-templates/note-setup-cntr.rst


.. contents::
   :local:
   :depth: 2


Develop on AWS ML accelerator instance
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. include:: /neuron-intro/install-templates/develop_mode.rst

.. include :: /neuron-intro/install-templates/note-setup-libnrt-warning.rst


.. tabs::

   .. group-tab:: TensorFlow 2.8.0

      .. tabs::

         .. group-tab:: Ubuntu AMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=develop --ami=non-dlami --os=ubuntu

         .. group-tab:: Amazon Linux AMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=develop --ami=non-dlami --os=amazonlinux

         .. group-tab:: Ubuntu DLAMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=develop --ami=dlami --os=ubuntu

         .. group-tab:: Amazon Linux DLAMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=develop --ami=dlami --os=amazonlinux


   .. group-tab:: TensorFlow 2.7.1

      .. tabs::

         .. group-tab:: Ubuntu AMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=develop --ami=non-dlami --os=ubuntu --framework-version=tensorflow-2.7.1

         .. group-tab:: Amazon Linux AMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=develop --ami=non-dlami --os=amazonlinux --framework-version=tensorflow-2.7.1

         .. group-tab:: Ubuntu DLAMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=develop --ami=dlami --os=ubuntu --framework-version=tensorflow-2.7.1

         .. group-tab:: Amazon Linux DLAMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=develop --ami=dlami --os=amazonlinux --framework-version=tensorflow-2.7.1


   .. group-tab:: TensorFlow 2.6.3

      .. tabs::

         .. group-tab:: Ubuntu AMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=develop --ami=non-dlami --os=ubuntu --framework-version=tensorflow-2.6.3

         .. group-tab:: Amazon Linux AMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=develop --ami=non-dlami --os=amazonlinux --framework-version=tensorflow-2.6.3

         .. group-tab:: Ubuntu DLAMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=develop --ami=dlami --os=ubuntu --framework-version=tensorflow-2.6.3

         .. group-tab:: Amazon Linux DLAMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=develop --ami=dlami --os=amazonlinux --framework-version=tensorflow-2.6.3


   .. group-tab:: TensorFlow 2.5.3

      .. tabs::

         .. group-tab:: Ubuntu AMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=develop --ami=non-dlami --os=ubuntu --framework-version=tensorflow-2.5.3

         .. group-tab:: Amazon Linux AMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=develop --ami=non-dlami --os=amazonlinux --framework-version=tensorflow-2.5.3

         .. group-tab:: Ubuntu DLAMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=develop --ami=dlami --os=ubuntu --framework-version=tensorflow-2.5.3

         .. group-tab:: Amazon Linux DLAMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=develop --ami=dlami --os=amazonlinux --framework-version=tensorflow-2.5.3




   .. group-tab:: TensorFlow 1.15.5

      .. tabs::

         .. group-tab:: Ubuntu AMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=develop --ami=non-dlami --os=ubuntu --framework-version=tensorflow-1.15.5

         .. group-tab:: Amazon Linux AMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=develop --ami=non-dlami --os=amazonlinux --framework-version=tensorflow-1.15.5

         .. group-tab:: Ubuntu DLAMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=develop --ami=dlami --os=ubuntu --framework-version=tensorflow-1.15.5

         .. group-tab:: Amazon Linux DLAMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=develop --ami=dlami --os=amazonlinux --framework-version=tensorflow-1.15.5    
         

Compile on compute instance
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. include:: /neuron-intro/install-templates/compile_mode.rst


.. tabs::

   .. group-tab:: TensorFlow 2.8.0

      .. tabs::

         .. group-tab:: Ubuntu AMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=compile --ami=non-dlami --os=ubuntu

         .. group-tab:: Amazon Linux AMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=compile --ami=non-dlami --os=amazonlinux

         .. group-tab:: Ubuntu DLAMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=compile --ami=dlami --os=ubuntu

         .. group-tab:: Amazon Linux DLAMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=compile --ami=dlami --os=amazonlinux

   .. group-tab:: TensorFlow 2.7.1

      .. tabs::

         .. group-tab:: Ubuntu AMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=compile --ami=non-dlami --os=ubuntu --framework-version=tensorflow-2.7.1

         .. group-tab:: Amazon Linux AMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=compile --ami=non-dlami --os=amazonlinux --framework-version=tensorflow-2.7.1

         .. group-tab:: Ubuntu DLAMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=compile --ami=dlami --os=ubuntu --framework-version=tensorflow-2.7.1

         .. group-tab:: Amazon Linux DLAMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=compile --ami=dlami --os=amazonlinux --framework-version=tensorflow-2.7.1


   .. group-tab:: TensorFlow 2.6.3

      .. tabs::

         .. group-tab:: Ubuntu AMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=compile --ami=non-dlami --os=ubuntu --framework-version=tensorflow-2.6.3

         .. group-tab:: Amazon Linux AMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=compile --ami=non-dlami --os=amazonlinux --framework-version=tensorflow-2.6.3

         .. group-tab:: Ubuntu DLAMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=compile --ami=dlami --os=ubuntu --framework-version=tensorflow-2.6.3

         .. group-tab:: Amazon Linux DLAMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=compile --ami=dlami --os=amazonlinux --framework-version=tensorflow-2.6.3


   .. group-tab:: TensorFlow 2.5.3

      .. tabs::

         .. group-tab:: Ubuntu AMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=compile --ami=non-dlami --os=ubuntu --framework-version=tensorflow-2.5.3

         .. group-tab:: Amazon Linux AMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=compile --ami=non-dlami --os=amazonlinux --framework-version=tensorflow-2.5.3

         .. group-tab:: Ubuntu DLAMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=compile --ami=dlami --os=ubuntu --framework-version=tensorflow-2.5.3

         .. group-tab:: Amazon Linux DLAMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=compile --ami=dlami --os=amazonlinux --framework-version=tensorflow-2.5.3



   .. group-tab:: TensorFlow 1.15.5

      .. tabs::

         .. group-tab:: Ubuntu AMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=compile --ami=non-dlami --os=ubuntu --framework-version=tensorflow-1.15.5

         .. group-tab:: Amazon Linux AMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=compile --ami=non-dlami --os=amazonlinux --framework-version=tensorflow-1.15.5

         .. group-tab:: Ubuntu DLAMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=compile --ami=dlami --os=ubuntu --framework-version=tensorflow-1.15.5

         .. group-tab:: Amazon Linux DLAMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=compile --ami=dlami --os=amazonlinux --framework-version=tensorflow-1.15.5   



Deploy on AWS ML accelerator instance
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. include:: /neuron-intro/install-templates/deploy_mode.rst

.. include :: /neuron-intro/install-templates/note-setup-libnrt-warning.rst


.. tabs::

   .. group-tab:: TensorFlow 2.8.0

      .. tabs::

         .. group-tab:: Ubuntu AMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=deploy --ami=non-dlami --os=ubuntu

         .. group-tab:: Amazon Linux AMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=deploy --ami=non-dlami --os=amazonlinux

         .. group-tab:: Ubuntu DLAMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=deploy --ami=dlami --os=ubuntu

         .. group-tab:: Amazon Linux DLAMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=deploy --ami=dlami --os=amazonlinux


   .. group-tab:: TensorFlow 2.7.1

      .. tabs::

         .. group-tab:: Ubuntu AMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=deploy --ami=non-dlami --os=ubuntu --framework-version=tensorflow-2.7.1

         .. group-tab:: Amazon Linux AMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=deploy --ami=non-dlami --os=amazonlinux --framework-version=tensorflow-2.7.1

         .. group-tab:: Ubuntu DLAMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=deploy --ami=dlami --os=ubuntu --framework-version=tensorflow-2.7.1

         .. group-tab:: Amazon Linux DLAMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=deploy --ami=dlami --os=amazonlinux --framework-version=tensorflow-2.7.1


   .. group-tab:: TensorFlow 2.6.3

      .. tabs::

         .. group-tab:: Ubuntu AMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=deploy --ami=non-dlami --os=ubuntu --framework-version=tensorflow-2.6.3

         .. group-tab:: Amazon Linux AMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=deploy --ami=non-dlami --os=amazonlinux --framework-version=tensorflow-2.6.3

         .. group-tab:: Ubuntu DLAMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=deploy --ami=dlami --os=ubuntu --framework-version=tensorflow-2.6.3

         .. group-tab:: Amazon Linux DLAMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=deploy --ami=dlami --os=amazonlinux --framework-version=tensorflow-2.6.3


   .. group-tab:: TensorFlow 2.5.3

      .. tabs::

         .. group-tab:: Ubuntu AMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=deploy --ami=non-dlami --os=ubuntu --framework-version=tensorflow-2.5.3

         .. group-tab:: Amazon Linux AMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=deploy --ami=non-dlami --os=amazonlinux --framework-version=tensorflow-2.5.3

         .. group-tab:: Ubuntu DLAMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=deploy --ami=dlami --os=ubuntu --framework-version=tensorflow-2.5.3

         .. group-tab:: Amazon Linux DLAMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=deploy --ami=dlami --os=amazonlinux --framework-version=tensorflow-2.5.3



   .. group-tab:: TensorFlow 1.15.5

      .. tabs::

         .. group-tab:: Ubuntu AMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=deploy --ami=non-dlami --os=ubuntu --framework-version=tensorflow-1.15.5

         .. group-tab:: Amazon Linux AMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=deploy --ami=non-dlami --os=amazonlinux --framework-version=tensorflow-1.15.5

         .. group-tab:: Ubuntu DLAMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=deploy --ami=dlami --os=ubuntu --framework-version=tensorflow-1.15.5

         .. group-tab:: Amazon Linux DLAMI

            .. include :: /neuron-intro/install-templates/note-setup-general.rst

            .. program-output:: python3 src/helperscripts/neuronsetuphelper.py --file src/helperscripts/neuron-releases-manifest.json --update tensorflow --mode=deploy --ami=dlami --os=amazonlinux --framework-version=tensorflow-1.15.5   





