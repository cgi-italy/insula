
.. _insula_ai:

Insula AI
=========

Insula AI is an advanced machine learning component built on Kubeflow, designed to streamline the deployment, scaling, and management of AI workflows. Currently in its beta phase, Insula AI brings cutting-edge capabilities to Insula instances (see :ref:`insula_instances`), enabling seamless integration of Kubeflow's powerful features with Insula's robust ecosystem.

Kubeflow is an open-source framework designed to automate, simplify and standardize machine/deep learning (ML/DL) workflows, including model development, training, deployment, and monitoring. Being deployed to a Kubernetes cluster, regardless of the cloud computing (private or public), it leverages its hardware capabilities (GPU, AMD, etc.), scalability and portability. Its supports a variety of tools to help managing the complete ML/DL lifecycle:

* `Kubeflow Notebooks <https://www.kubeflow.org/docs/components/notebooks/overview/>`_, provides web-based development environments (`JupyterLab <https://github.com/jupyterlab/jupyterlab>`_, `RStudio <https://github.com/rstudio/rstudio>`_, `Visual Studio Code <https://github.com/cdr/code-server>`_) allowing data scientists and ML engineers to interactively explore data, build models, and prototype workflows;
* `Kubeflow Pipelines <https://www.kubeflow.org/docs/components/pipelines/overview/>`_, allows users to define, deploy, and monitor ML pipelines that can include data preprocessing, model training, evaluation, and deployment steps;
* `Tensorboard <https://www.tensorflow.org/tensorboard/get_started>`_, is a tool to visualize metrics and statistics related to model training, such as loss and accuracy curves, histograms, and activation maps. In Kubeflow, it is integrated to provide real-time insights into training jobs;
* `Katib Experiments <https://www.kubeflow.org/docs/components/katib/overview/>`_, allows users to optimize their models by automatically searching for the best hyperparameters through techniques like grid search, random search, and Bayesian optimization;
* `KServe Endpoints <https://www.kubeflow.org/docs/external-add-ons/kserve/introduction/>`_, allows users to deploy, scale, and manage ML/DL models in production, providing features such as autoscaling, versioning, and monitoring;

Run your first "Hello world!" pipeline following this `tutorial <https://github.com/cgi-italy/notebooks/blob/main/Kubeflow_Hello_world.ipynb>`_.

Stay tuned as we rapidly evolve Insula AI to support more use cases and enhance its functionality across diverse Insula environments!

.. image:: ../images/insula_ai_1.png
   :alt: Insula AI welcome page
