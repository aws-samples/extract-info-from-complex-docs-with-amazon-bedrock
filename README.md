# Extracting Information From Complex Documents with Amazon Bedrock

This hands-on workshop, aimed at developers and solution builders, introduces how to leverage foundation models (FMs) through [Amazon Bedrock](https://aws.amazon.com/bedrock/) to extract information from custom documents and organize it in a structured database.

**Please follow the prerequisites notebooks or ask your AWS workshop instructor how to get started.**

Amazon Bedrock is a fully managed service that provides access to FMs from third-party providers and Amazon; available via an API. With Bedrock, you can choose from a variety of models to find the one that’s best suited for your use case.


## Getting started

### Choose a notebook environment

This workshop is presented as a series of **Python notebooks**, which you can run from the environment of your choice:

- For a fully-managed environment with rich AI/ML features, we'd recommend using [SageMaker Studio](https://aws.amazon.com/sagemaker/studio/). To get started quickly, you can refer to the [instructions for domain quick setup](https://docs.aws.amazon.com/sagemaker/latest/dg/onboard-quick-start.html).
- For a fully-managed but more basic experience, you could instead [create a SageMaker Notebook Instance](https://docs.aws.amazon.com/sagemaker/latest/dg/howitworks-create-ws.html).
- If you prefer to use your existing (local or other) notebook environment, make sure it has [credentials for calling AWS](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-configure.html).


### Use the notebooks

Start with [00_prerequisites.ipynb](00_prerequisites.ipynb) for details on how to install the Bedrock SDKs, create a client, and start calling the APIs from Python.

Next, go through the other notebooks one by one.


## License

The original source of PDFs in `demo-files` folder is:
- https://arxiv.org/abs/2302.13971
- https://arxiv.org/abs/2310.06825

The PDF files are distributed under CC BY 4.0 license (https://creativecommons.org/licenses/by/4.0/).
