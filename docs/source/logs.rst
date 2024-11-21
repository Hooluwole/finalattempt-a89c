Latest Logs From Latest Build
==============================

Generated On: 2024-11-21 00:40:08 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/Hooluwole/raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-11-21_00:37:33] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-11-21_00:37:36] STEP 2: Create topics started

  [INFO 2024-11-21_00:37:54] STEP 2: Completed

  [INFO 2024-11-21_00:38:05] STEP 3: producing data started

  [INFO 2024-11-21_00:38:08] MQTT connection established...

  [INFO 2024-11-21_00:38:09] STEP 4: Preprocessing started

  [INFO 2024-11-21_00:38:13] STEP 4: Preprocessing started

  [INFO 2024-11-21_00:38:15] STEP 7: Visualization started

  [INFO 2024-11-21_00:38:22] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 59517

  [INFO 2024-11-21_00:38:30] STEP 9: Starting privateGPT

  [INFO 2024-11-21_00:38:38] STEP 8: Starting docker push for: hooluwole70/finalattempt-a89c-amd64

  [INFO 2024-11-21_00:38:46] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --env PORT=8001 --env GPU=0 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-no-gpu-amd64

  [INFO 2024-11-21_00:39:05] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit 819f3465418f hooluwole70/finalattempt-a89c-amd64 - message=0

  [INFO 2024-11-21_00:39:44] STEP 8: Successfully ran Docker push: docker push hooluwole70/finalattempt-a89c-amd64 - message=0

  [INFO 2024-11-21_00:40:07] STEP 10: Started to build the documentation

  [INFO 2024-11-21_00:40:09] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


