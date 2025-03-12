MoExLLaMA

MoExLLaMA is an innovative project that integrates a Mixture-of-Experts (MoE) architecture with Meta's LLaMA language model. By combining the efficiency and dynamic routing of MoE with the robust language capabilities of LLaMA, this project aims to deliver improved performance and scalability for natural language processing tasks.
Overview

MoExLLaMA leverages a hybrid design where multiple expert sub-models are dynamically selected based on the input, ensuring that the most relevant processing paths are utilized. This approach provides:

    Efficiency: Reduce computational overhead by routing inputs to specialized experts.
    Scalability: Easily scale up the model with additional experts without a proportional increase in computation.
    Performance: Enhance language understanding and generation tasks by leveraging the state-of-the-art LLaMA model.

Features

    Hybrid Architecture: Combines MoE dynamic routing with the powerful LLaMA model.
    Dynamic Expert Selection: Automatically selects expert modules based on input characteristics.
    Flexible Integration: Designed to integrate with existing NLP pipelines and frameworks.
    Customizable Configuration: Easily adjust model parameters, expert numbers, and routing logic.

Getting Started
Prerequisites

    Python: Version 3.8 or higher.
    PyTorch: Version compatible with your CUDA version (if using GPU acceleration).
    Transformers: Hugging Face Transformers library.
    Additional dependencies listed in the requirements.txt file.
