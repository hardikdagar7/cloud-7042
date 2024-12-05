Latest Logs From Latest Build
==============================

Generated On: 2024-12-05 16:48:58 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/hardikdagar7/raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-12-05_16:47:00] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-12-05_16:47:02] STEP 2: Create topics started

  [INFO 2024-12-05_16:47:13] STEP 2: Completed

  [INFO 2024-12-05_16:47:17] STEP 3: producing data started

  [INFO 2024-12-05_16:47:20] STEP 4: Preprocessing started

  [INFO 2024-12-05_16:47:20] MQTT connection established...

  [INFO 2024-12-05_16:47:22] STEP 4: Preprocessing started

  [INFO 2024-12-05_16:47:22] STEP 7: Visualization started

  [INFO 2024-12-05_16:47:28] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-12-05_16:47:36] STEP 8: Starting docker push for: hardikdagar0207/cloud-7042-amd64

  [INFO 2024-12-05_16:47:40] STEP 9: Success starting Qdrant.  Here is the run command: docker run -d -p 6333:6333 -v $(pwd)/qdrant_storage:/qdrant/storage:z qdrant/qdrant

  [INFO 2024-12-05_16:47:45] STEP 9: Starting privateGPT

  [INFO 2024-12-05_16:47:55] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --env PORT=8001 --env GPU=0 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-no-gpu-amd64

  [INFO 2024-12-05_16:48:00] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit fad1848d3763 hardikdagar0207/cloud-7042-amd64 - message=0

  [INFO 2024-12-05_16:48:52] STEP 8: Successfully ran Docker push: docker push hardikdagar0207/cloud-7042-amd64 - message=0

  [INFO 2024-12-05_16:48:57] STEP 10: Started to build the documentation

  [INFO 2024-12-05_16:48:58] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


