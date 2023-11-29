# LLMOps Workshop

Learn how to build solutions with Large Language Models 
in a day. This includes learning Azure Machine Learning
Prompt Flow, Content Safety, Azure OpenAI, LLMs 
solutions Evaluation and Monitoring.

## Contents

[Workshop contents](TOC.md)

## Requirements

<!-- - Workstation

    - [Azure CLI](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli)
    - [Anaconda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html)
    - [VS Code](https://code.visualstudio.com/)

- Cloud -->

* [Github.com Account](https://github.com).
* GitHub as the source control repository.
* [Azure Subscription](https://azure.com).
* An Azure Machine Learning workspace.

## First Steps

1. Create an AzureML workspace in your subscription.

2. Open your workspace in AzureML Studio: [https://ml.azure.com/](https://ml.azure.com/)

3. In you AzureML workspace create a compute to use during the workshop.

    Compute > Compute Instances > New

3. Open terminal:
    
    Notebooks > Terminal

4. Clone this repository.

```
    git clone https://github.com/placerda/llmops-workshop.git
```

1. Open terminal to create and activate conda environment
```
conda create -n workshop python=3.10
```
1. Open the directory where the repository was cloned in terminal.
```
    cd llmops-workshop
```
1. Install the required python libraries.
```
    pip install -r requirements.txt
```
1. Add nbstripout git filter to avoid saving notebooks output.
```
nbstripout --install
```
1. Open VS Code.
```
    code .
```

7. Go to the [VS Code setup](first_steps/vs_code_setup.md) instructions.
