================
torchtune.models
================

.. currentmodule:: torchtune.models

llama2
------

All models from the `Llama2 family <https://llama.meta.com/llama2/>`_.

Pre-trained models can be downloaded from the Hugging Face Hub with the following command:

.. code-block:: bash

    tune download meta-llama/Llama-2-7b-hf --hf-token <ACCESS_TOKEN>

.. autosummary::
    :toctree: generated/
    :nosignatures:

    llama2.llama2_7b
    llama2.lora_llama2_7b
    llama2.qlora_llama2_7b
    llama2.llama2_13b
    llama2.lora_llama2_13b
    llama2.qlora_llama2_13b

mistral
-------

All models from `Mistral AI family <https://mistral.ai/technology/#models>`_.

Pre-trained models can be downloaded from the Hugging Face Hub with the following command:

.. code-block:: bash

    tune download mistralai/Mistral-7B-v0.1

.. autosummary::
    :toctree: generated/
    :nosignatures:

    mistral.mistral_7b
    mistral.lora_mistral_7b
    mistral.qlora_mistral_7b

gemma
-----

All models from the `Gemma family <https://blog.google/technology/developers/gemma-open-models/>`_.

Pre-trained models can be downloaded from the Hugging Face Hub with the following command:

.. code-block:: bash

    tune download google/gemma-2b --hf-token <ACCESS_TOKEN> --ignore-patterns ""

.. autosummary::
    :toctree: generated/
    :nosignatures:

    gemma.gemma_2b
