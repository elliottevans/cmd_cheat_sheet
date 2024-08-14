Useful Terminal Commands
=========================

Docker
^^^^^^

* ``docker login []``
* ``docker image prune --all``

  - Deletes all local image caches
* ``docker run -it --entrypoint bash <image_id>``

  - Run bash under built image

General
^^^^^^^

* ``xattr -d com.apple.quarantine [path to avenue binary]``
  - Remove apple security block for a file you trust
* Monitor memory usage: ``top``
* Monitor GPU usage: ``watch -n0.1 nvidia-smi``
* Monitor filesystem usage: ``watch -n0.1 df -h``
* Redirect script output: ``nohup python my_script.py --some_var=val > log_file.out &``
* Kill all python processes: ``pkill -9 python``
* Get all defunct processes: ``ps -ef | grep defunct``
* Get all processes: ``ps aux``
* Keep machine from sleeping: ``caffeinate -d -i -w $$``

Conda
^^^^^^^

* Create a new conda environment with Python 3.12: ``conda create -n {environment_name} python=3.12``
* Remove a conda environment: ``conda remove -n {environment_name}``
* List available conda environments: ``conda env list``

Setting Up Git
^^^^^^^^^^^^^^
* `Set up Git / Connecting over SSH <https://docs.github.com/en/get-started/getting-started-with-git/set-up-git#connecting-over-ssh>`_
* `Generating a new SSH key <https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent#generating-a-new-ssh-key>`_



