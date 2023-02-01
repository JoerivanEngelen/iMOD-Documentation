.. _deltaforge-install:

***********************************
Install iMOD Python with Deltaforge
***********************************

What is Deltaforge?
-------------------

Deltaforge is a python distribution which includes iMOD Python and all its
dependencies. It is provided as an installer and makes installing iMOD Python
easy.You can download the Deltaforge installer 
`via this link <https://download.deltares.nl/en/download/imod-suite/>`_.
If the subscription worked correctly, 
you will receive a download link via e-mail within only a few minutes.

Installation
------------

To install Deltaforge, double-click the executable, this will open the
installation Wizard. You will be greeted with the welcome screen.

.. figure:: screenshots/deltaforge/1_welcome_screen.png

   The welcome screen

Click "Next", and then "I agree" in the license agreement.

.. figure:: screenshots/deltaforge/2_license.png

   License agreement screen

Next, you get to decide what type of installation you want. On your local
machine it suffices to select `Just me`. If you are an admin of a server and you
want to let others enjoy the Deltaforge installation as well, click `All Users`.

.. figure:: screenshots/deltaforge/3_installation_type.png

   The installation type screen

Next you get to decide where the python environment is installed.
The default location is usually fine.

.. figure:: screenshots/deltaforge/4_install_location.png

   The location of the python installation

Finally, some further configuration is possible. The screenshots contains the
options we recommend.

.. figure:: screenshots/deltaforge/5_installation_options.png

   Installation options with the recommended options selected.

Using Deltaforge
----------------

The easiest way to start your environment is by pressing the Windows Key and
start typing `deltaforge`. This will let you select the `Deltaforge Prompt`.
Select this.

.. figure:: screenshots/deltaforge/6_deltaforge_start_menu.png

   The Deltaforge Prompt should be findable in the Windows start menu

This will start a command prompt screen (``cmd.exe``), where at startup the
Deltaforge python environment is activated. 

.. figure:: screenshots/deltaforge/7_deltaforge_prompt.png

    The Deltaforge prompt. You can type ``mamba list`` to view all the packages
    installed.

To view all the packages installed in the environment you can type ``mamba
list`` and press Enter. This will list all packages installed in the
environment. If you want to start coding, you can type ``spyder``, which will
start Spyder, a Python scientific development environment.