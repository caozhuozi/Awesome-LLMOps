# Awesome-LLMOps [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

🎉 An awesome &amp; curated list of best LLMOps tools. But more about LLMOps.

## Table of Contents

- [LLMOps](#llmops)
- [MLOps](#mlops)
- [Inference](#inference)
- [Training](#training)
- [FineTune](#finetune)
- [Agent](#agent)
- [Evaluation](#evaluation)
- [DB Store](#db-store)
- [Observation](#observation)
- [Alignment](#alignment)
- [Outputs](#outputs)

## LLMOps

| Name | Stars | Release | Contributors | About | Tag |
| ---- | ---- | ---- | ---- | ---- | --- |
| **[BentoML](https://github.com/bentoml/BentoML)** | ![Stars](https://img.shields.io/github/stars/bentoml/bentoml.svg) | ![Release](https://img.shields.io/github/release/bentoml/bentoml) | ![Contributors](https://img.shields.io/github/contributors/bentoml/bentoml) | Build Production-Grade AI Applications | |
| **[Dify](https://github.com/langgenius/dify)** | ![Stars](https://img.shields.io/github/stars/langgenius/dify.svg) | ![Release](https://img.shields.io/github/release/langgenius/dify) | ![Contributors](https://img.shields.io/github/contributors/langgenius/dify) | One API for plugins and datasets, one interface for prompt engineering and visual operation, all for creating powerful AI applications | |
| **[FastChat](https://github.com/lm-sys/FastChat)** | ![Stars](https://img.shields.io/github/stars/lm-sys/fastchat.svg) | ![Release](https://img.shields.io/github/release/lm-sys/fastchat) | ![Contributors](https://img.shields.io/github/contributors/lm-sys/fastchat) | An open platform for training, serving, and evaluating large language models. Release repo for Vicuna and Chatbot Arena. | |
| **[Flowise](https://github.com/FlowiseAI/Flowise)** | ![Stars](https://img.shields.io/github/stars/flowiseai/flowise.svg) | ![Release](https://img.shields.io/github/release/flowiseai/flowise) | ![Contributors](https://img.shields.io/github/contributors/flowiseai/flowise) | Drag & drop UI to build your customized LLM flow | |
| **[Haystack](https://github.com/deepset-ai/haystack)** | ![Stars](https://img.shields.io/github/stars/deepset-ai/haystack.svg) | ![Release](https://img.shields.io/github/release/deepset-ai/haystack) | ![Contributors](https://img.shields.io/github/contributors/deepset-ai/haystack) | 🔍 LLM orchestration framework to build customizable, production-ready LLM applications. Connect components (models, vector DBs, file converters) to pipelines or agents that can interact with your data. With advanced retrieval methods, it's best suited for building RAG, question answering, semantic search or conversational agent chatbots. | |
| **[LangChain](https://github.com/langchain-ai/langchain)** | ![Stars](https://img.shields.io/github/stars/langchain-ai/langchain.svg) | ![Release](https://img.shields.io/github/release/langchain-ai/langchain) | ![Contributors](https://img.shields.io/github/contributors/langchain-ai/langchain) | ⚡ Building applications with LLMs through composability ⚡ | |
| **[LiteLLM](https://github.com/BerriAI/litellm)** | ![Stars](https://img.shields.io/github/stars/berriai/litellm.svg) | ![Release](https://img.shields.io/github/release/berriai/litellm) | ![Contributors](https://img.shields.io/github/contributors/berriai/litellm) | lightweight package to simplify LLM API calls - Azure, OpenAI, Cohere, Anthropic, Replicate. Manages input/output translation | |
| **[LLaMa-Factory](https://github.com/hiyouga/LLaMA-Factory)** | ![Stars](https://img.shields.io/github/stars/hiyouga/llama-factory.svg) | ![Release](https://img.shields.io/github/release/hiyouga/llama-factory) | ![Contributors](https://img.shields.io/github/contributors/hiyouga/llama-factory) | Easy-to-use LLM fine-tuning framework (LLaMA, BLOOM, Mistral, Baichuan, Qwen, ChatGLM) | |
| **[LlamaIndex](https://github.com/run-llama/llama_index)** | ![Stars](https://img.shields.io/github/stars/run-llama/llama_index.svg) | ![Release](https://img.shields.io/github/release/run-llama/llama_index) | ![Contributors](https://img.shields.io/github/contributors/run-llama/llama_index) | LlamaIndex is a data framework for your LLM applications | |
| **[Mem0](https://github.com/mem0ai/mem0)** | ![Stars](https://img.shields.io/github/stars/mem0ai/mem0.svg) | ![Release](https://img.shields.io/github/release/mem0ai/mem0) | ![Contributors](https://img.shields.io/github/contributors/mem0ai/mem0) | The memory layer for Personalized AI | |
| **[Open WebUI](https://github.com/open-webui/open-webui)** | ![Stars](https://img.shields.io/github/stars/open-webui/open-webui.svg) | ![Release](https://img.shields.io/github/release/open-webui/open-webui) | ![Contributors](https://img.shields.io/github/contributors/open-webui/open-webui) | User-friendly WebUI for LLMs (Formerly Ollama WebUI) | |
| **[PrivateGPUT](https://github.com/zylon-ai/private-gpt)** | ![Stars](https://img.shields.io/github/stars/zylon-ai/private-gpt.svg) | ![Release](https://img.shields.io/github/release/zylon-ai/private-gpt) | ![Contributors](https://img.shields.io/github/contributors/zylon-ai/private-gpt) | Interact with your documents using the power of GPT, 100% privately, no data leaks | |

## MLOps

| Name                                                 | Stars                                                               | Release | Contributors | About                                                                                                        | Tag   |
|------------------------------------------------------|---------------------------------------------------------------------| ---- | ---- |--------------------------------------------------------------------------------------------------------------|-------|
| **[Flyte](https://github.com/flyteorg/flyte)**       | ![Stars](https://img.shields.io/github/stars/flyteorg/flyte.svg)    | ![Release](https://img.shields.io/github/release/flyteorg/flyte) | ![Contributors](https://img.shields.io/github/contributors/flyteorg/flyte) | Scalable and flexible workflow orchestration platform that seamlessly unifies data, ML and analytics stacks. |       |
| **[Kubeflow](https://github.com/kubeflow/kubeflow)** | ![Stars](https://img.shields.io/github/stars/kubeflow/kubeflow.svg) | ![Release](https://img.shields.io/github/release/kubeflow/kubeflow) | ![Contributors](https://img.shields.io/github/contributors/kubeflow/kubeflow) | Machine Learning Toolkit for Kubernetes                                                                      | cloud |
| **[Metaflow](https://github.com/Netflix/metaflow)**  | ![Stars](https://img.shields.io/github/stars/netflix/metaflow.svg)  | ![Release](https://img.shields.io/github/release/netflix/metaflow) | ![Contributors](https://img.shields.io/github/contributors/netflix/metaflow) | 🚀 Build and manage real-life data science projects with ease!                                               |       |
| **[MLflow](https://github.com/mlflow/mlflow)**       | ![Stars](https://img.shields.io/github/stars/mlflow/mlflow.svg)     | ![Release](https://img.shields.io/github/release/mlflow/mlflow) | ![Contributors](https://img.shields.io/github/contributors/mlflow/mlflow) | Open source platform for the machine learning lifecycle                                                      |       |
| **[Seldon-Core](https://github.com/SeldonIO/seldon-core)** | ![Stars](https://img.shields.io/github/stars/SeldonIO/seldon-core.svg) | ![Release](https://img.shields.io/github/release/SeldonIO/seldon-core) | ![Contributors](https://img.shields.io/github/contributors/SeldonIO/seldon-core) | An MLOps framework to package, deploy, monitor and manage thousands of production machine learning models. | cloud |
| **[ZenML](https://github.com/zenml-io/zenml)**       | ![Stars](https://img.shields.io/github/stars/zenml-io/zenml.svg)    | ![Release](https://img.shields.io/github/release/zenml-io/zenml) | ![Contributors](https://img.shields.io/github/contributors/zenml-io/zenml) | ZenML 🙏: Build portable, production-ready MLOps pipelines. <https://zenml.io>.                              |       |

## Inference

| Name                                                                                      | Stars                                                                                   | Release | Contributors | About | Tag |
|-------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------| ---- | ---- | ---- | ---- |
| **[DeepSpeed-MII](https://github.com/microsoft/DeepSpeed-MII)**                           | ![Stars](https://img.shields.io/github/stars/microsoft/deepspeed-mii.svg)               | ![Release](https://img.shields.io/github/release/microsoft/deepspeed-mii) | ![Contributors](https://img.shields.io/github/contributors/microsoft/deepspeed-mii) | MII makes low-latency and high-throughput inference possible, powered by DeepSpeed. | |
| **[ipex-llm](https://github.com/intel-analytics/ipex-llm)**                               | ![Stars](https://img.shields.io/github/stars/intel-analytics/ipex-llm.svg)              | ![Release](https://img.shields.io/github/release/intel-analytics/ipex-llm) | ![Contributors](https://img.shields.io/github/contributors/intel-analytics/ipex-llm) | Accelerate local LLM inference and finetuning (LLaMA, Mistral, ChatGLM, Qwen, Baichuan, Mixtral, Gemma, Phi, MiniCPM, etc.) on Intel CPU and GPU (e.g., local PC with iGPU, discrete GPU such as Arc, Flex and Max); seamlessly integrate with llama.cpp, Ollama, HuggingFace, LangChain, LlamaIndex, GraphRAG, DeepSpeed, vLLM, FastChat, Axolotl, etc. | edge |
| **[llmaz](https://github.com/InftyAI/llmaz)**                                             | ![Stars](https://img.shields.io/github/stars/inftyai/llmaz.svg)                         | ![Release](https://img.shields.io/github/release/inftyai/llmaz) | ![Contributors](https://img.shields.io/github/contributors/inftyai/llmaz) | ☸️ Effortlessly serve state-of-the-art LLMs on Kubernetes. | |
| **[LMDeploy](https://github.com/InternLM/lmdeploy)**                                      | ![Stars](https://img.shields.io/github/stars/internlm/lmdeploy.svg)                     | ![Release](https://img.shields.io/github/release/internlm/lmdeploy) | ![Contributors](https://img.shields.io/github/contributors/internlm/lmdeploy) | LMDeploy is a toolkit for compressing, deploying, and serving LLMs. | |
| **[llama.cpp](https://github.com/ggerganov/llama.cpp)**                                   | ![Stars](https://img.shields.io/github/stars/ggerganov/llama.cpp.svg)                   | ![Release](https://img.shields.io/github/release/ggerganov/llama.cpp) | ![Contributors](https://img.shields.io/github/contributors/ggerganov/llama.cpp) | LLM inference in C/C++ | edge |
| **[MInference](https://github.com/microsoft/minference)**                                 | ![Stars](https://img.shields.io/github/stars/microsoft/minference.svg)                  | ![Release](https://img.shields.io/github/release/microsoft/minference) | ![Contributors](https://img.shields.io/github/contributors/microsoft/minference) | To speed up Long-context LLMs' inference, approximate and dynamic sparse calculate the attention, which reduces inference latency by up to 10x for pre-filling on an A100 while maintaining accuracy. | |
| **[MLC LLM](https://github.com/mlc-ai/mlc-llm)**                                          | ![Stars](https://img.shields.io/github/stars/mlc-ai/mlc-llm.svg)                        | ![Release](https://img.shields.io/github/release/mlc-ai/mlc-llm) | ![Contributors](https://img.shields.io/github/contributors/mlc-ai/mlc-llm) | Universal LLM Deployment Engine with ML Compilation | |
| **[MLServer](https://github.com/SeldonIO/MLServer)**                                             | ![Stars](https://img.shields.io/github/stars/SeldonIO/MLServer.svg)                         | ![Release](https://img.shields.io/github/release/SeldonIO/MLServer) | ![Contributors](https://img.shields.io/github/contributors/SeldonIO/MLServer) | MLServer aims to provide an easy way to start serving your machine learning models through a REST and gRPC interface, fully compliant with KFServing's V2 Dataplane spec. | |
| **[Ollama](https://github.com/ollama/ollama)**                                            | ![Stars](https://img.shields.io/github/stars/ollama/ollama.svg)                         | ![Release](https://img.shields.io/github/release/ollama/ollama) | ![Contributors](https://img.shields.io/github/contributors/ollama/ollama) | Get up and running with Llama 3, Mistral, Gemma 2, and other large language models. | edge |
| **[OpenLLM](https://github.com/bentoml/OpenLLM)**                                         | ![Stars](https://img.shields.io/github/stars/bentoml/openllm.svg)                       | ![Release](https://img.shields.io/github/release/bentoml/openllm) | ![Contributors](https://img.shields.io/github/contributors/bentoml/openllm) | Operating LLMs in production | |
| **[OpenVINO](https://github.com/openvinotoolkit/openvino)**                               | ![Stars](https://img.shields.io/github/stars/openvinotoolkit/openvino.svg)              | ![Release](https://img.shields.io/github/release/openvinotoolkit/openvino) | ![Contributors](https://img.shields.io/github/contributors/openvinotoolkit/openvino) | OpenVINO™ is an open-source toolkit for optimizing and deploying AI inference | |
| **[RayServe](https://github.com/ray-project/ray)**                                        | ![Stars](https://img.shields.io/github/stars/ray-project/ray.svg)                       | ![Release](https://img.shields.io/github/release/ray-project/ray) | ![Contributors](https://img.shields.io/github/contributors/ray-project/ray) | Ray is a unified framework for scaling AI and Python applications. Ray consists of a core distributed runtime and a set of AI Libraries for accelerating ML workloads. | |
| **[RouteLLM](https://github.com/lm-sys/routellm)**                                        | ![Stars](https://img.shields.io/github/stars/lm-sys/routellm.svg)                       | ![Release](https://img.shields.io/github/release/lm-sys/routellm) | ![Contributors](https://img.shields.io/github/contributors/lm-sys/routellm) | A framework for serving and evaluating LLM routers - save LLM costs without compromising quality. | cost |
| **[SGLang](https://github.com/sgl-project/sglang)**                                       | ![Stars](https://img.shields.io/github/stars/sgl-project/sglang.svg)                    | ![Release](https://img.shields.io/github/release/sgl-project/sglang) | ![Contributors](https://img.shields.io/github/contributors/sgl-project/sglang) | SGLang is a structured generation language designed for large language models (LLMs). It makes your interaction with models faster and more controllable. | |
| **[Triton Inference Server](https://github.com/triton-inference-server/server)**          | ![Stars](https://img.shields.io/github/stars/triton-inference-server/server.svg)        | ![Release](https://img.shields.io/github/release/triton-inference-server/server) | ![Contributors](https://img.shields.io/github/contributors/triton-inference-server/server) | The Triton Inference Server provides an optimized cloud and edge inferencing solution. | |
| **[Text Generation Inference](https://github.com/huggingface/text-generation-inference)** | ![Stars](https://img.shields.io/github/stars/huggingface/text-generation-inference.svg) | ![Release](https://img.shields.io/github/release/huggingface/text-generation-inference) | ![Contributors](https://img.shields.io/github/contributors/huggingface/text-generation-inference) | Large Language Model Text Generation Inference | |
| **[vLLM](https://github.com/vllm-project/vllm)**                                          | ![Stars](https://img.shields.io/github/stars/vllm-project/vllm.svg)                     | ![Release](https://img.shields.io/github/release/vllm-project/vllm) | ![Contributors](https://img.shields.io/github/contributors/vllm-project/vllm) | A high-throughput and memory-efficient inference and serving engine for LLMs | |

## Training

| Name | Stars | Release | Contributors | About | Tag |
| ---- | ---- | ---- | ---- | ---- | ---- |
| **[ColossalAI](https://github.com/hpcaitech/ColossalAI)** | ![Stars](https://img.shields.io/github/stars/hpcaitech/ColossalAI.svg) | ![Release](https://img.shields.io/github/release/hpcaitech/ColossalAI) | ![Contributors](https://img.shields.io/github/contributors/hpcaitech/ColossalAI) | Making large AI models cheaper, faster and more accessible | |
| **[Ludwig](https://github.com/ludwig-ai/ludwig)** | ![Stars](https://img.shields.io/github/stars/ludwig-ai/ludwig.svg) | ![Release](https://img.shields.io/github/release/ludwig-ai/ludwig) | ![Contributors](https://img.shields.io/github/contributors/ludwig-ai/ludwig) | Low-code framework for building custom LLMs, neural networks, and other AI models | |
| **[MLX](https://github.com/ml-explore/mlx)** | ![Stars](https://img.shields.io/github/stars/ml-explore/mlx.svg) | ![Release](https://img.shields.io/github/release/ml-explore/mlx) | ![Contributors](https://img.shields.io/github/contributors/ml-explore/mlx) | MLX: An array framework for Apple silicon | |

## FineTune

| Name | Stars | Release | Contributors | About | Tag |
| ---- | ---- | ---- | ---- | ---- | ---- |
| **[Axolotl](https://github.com/axolotl-ai-cloud/axolotl)** | ![Stars](https://img.shields.io/github/stars/axolotl-ai-cloud/axolotl.svg) | ![Release](https://img.shields.io/github/release/axolotl-ai-cloud/axolotl) | ![Contributors](https://img.shields.io/github/contributors/axolotl-ai-cloud/axolotl) | Go ahead and axolotl questions | |
| **[torchtune](https://github.com/pytorch/torchtune)** | ![Stars](https://img.shields.io/github/stars/pytorch/torchtune.svg) | ![Release](https://img.shields.io/github/release/pytorch/torchtune) | ![Contributors](https://img.shields.io/github/contributors/pytorch/torchtune) | A Native-PyTorch Library for LLM Fine-tuning | |
| **[unsloth](https://github.com/unslothai/unsloth)** | ![Stars](https://img.shields.io/github/stars/unslothai/unsloth.svg) | ![Release](https://img.shields.io/github/release/unslothai/unsloth) | ![Contributors](https://img.shields.io/github/contributors/unslothai/unsloth) | Finetune Llama 3, Mistral, Phi & Gemma LLMs 2-5x faster with 80% less memory | |

## Agent

| Name | Stars | Release | Contributors | About | Tag |
| ---- | ---- | ---- | ---- | ---- | ---- |
| **[AutoGPT](https://github.com/Significant-Gravitas/AutoGPT)** | ![Stars](https://img.shields.io/github/stars/Significant-Gravitas/AutoGPT.svg) | ![Release](https://img.shields.io/github/release/Significant-Gravitas/AutoGPT) | ![Contributors](https://img.shields.io/github/contributors/Significant-Gravitas/AutoGPT) | An experimental open-source attempt to make GPT-4 fully autonomous. | |
| **[MetaGPT](https://github.com/geekan/MetaGPT)** | ![Stars](https://img.shields.io/github/stars/geekan/metagpt.svg) | ![Release](https://img.shields.io/github/release/geekan/MetaGPT) | ![Contributors](https://img.shields.io/github/contributors/geekan/MetaGPT) | 🌟 The Multi-Agent Framework: Given one line Requirement, return PRD, Design, Tasks, Repo | |
| **[XAgent](https://github.com/OpenBMB/XAgent)** | ![Stars](https://img.shields.io/github/stars/openbmb/xagent.svg) | ![Release](https://img.shields.io/github/release/openbmb/xagent) | ![Contributors](https://img.shields.io/github/contributors/openbmb/xagent) | An Autonomous LLM Agent for Complex Task Solving | |

## Evaluation

| Name | Stars | Release | Contributors | About | Tag |
| ---- | ---- | ---- | ---- | ---- | ---- |
| **[AgentBench](https://github.com/THUDM/AgentBench)** | ![Stars](https://img.shields.io/github/stars/thudm/agentbench.svg) | ![Release](https://img.shields.io/github/release/thudm/agentbench) | ![Contributors](https://img.shields.io/github/contributors/thudm/agentbench) | A Comprehensive Benchmark to Evaluate LLMs as Agents | |
| **[lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness)** | ![Stars](https://img.shields.io/github/stars/EleutherAI/lm-evaluation-harness.svg) | ![Release](https://img.shields.io/github/release/EleutherAI/lm-evaluation-harness) | ![Contributors](https://img.shields.io/github/contributors/EleutherAI/lm-evaluation-harness) | A framework for few-shot evaluation of language models. | |
| **[LongBench](https://github.com/THUDM/LongBench)** | ![Stars](https://img.shields.io/github/stars/thudm/longbench.svg) | ![Release](https://img.shields.io/github/release/thudm/longbench) | ![Contributors](https://img.shields.io/github/contributors/thudm/longbench) | LongBench: A Bilingual, Multitask Benchmark for Long Context Understanding | long-context |

## DB Store

| Name | Stars | Release | Contributors | About | Tag |
| ---- | ---- | ---- | ---- | ---- | ---- |
| **[chroma](https://github.com/chroma-core/chroma)** | ![Stars](https://img.shields.io/github/stars/chroma-core/chroma.svg) | ![Release](https://img.shields.io/github/release/chroma-core/chroma) | ![Contributors](https://img.shields.io/github/contributors/chroma-core/chroma) | the AI-native open-source embedding database | vector |
| **[deeplake](https://github.com/activeloopai/deeplake)** | ![Stars](https://img.shields.io/github/stars/activeloopai/deeplake.svg) | ![Release](https://img.shields.io/github/release/activeloopai/deeplake) | ![Contributors](https://img.shields.io/github/contributors/activeloopai/deeplake) | Database for AI. Store Vectors, Images, Texts, Videos, etc. Use with LLMs/LangChain. Store, query, version, & visualize any AI data. Stream data in real-time to PyTorch/TensorFlow. <https://activeloop.ai> | |
| **[Faiss](https://github.com/facebookresearch/faiss)** | ![Stars](https://img.shields.io/github/stars/facebookresearch/faiss.svg) | ![Release](https://img.shields.io/github/release/facebookresearch/faiss) | ![Contributors](https://img.shields.io/github/contributors/facebookresearch/faiss) | A library for efficient similarity search and clustering of dense vectors. | vector |
| **[milvus](https://github.com/milvus-io/milvus)** | ![Stars](https://img.shields.io/github/stars/milvus-io/milvus.svg) | ![Release](https://img.shields.io/github/release/milvus-io/milvus) | ![Contributors](https://img.shields.io/github/contributors/milvus-io/milvus) | A cloud-native vector database, storage for next generation AI applications | cloud,vector |
| **[weaviate](https://github.com/weaviate/weaviate)** | ![Stars](https://img.shields.io/github/stars/weaviate/weaviate.svg) | ![Release](https://img.shields.io/github/release/weaviate/weaviate) | ![Contributors](https://img.shields.io/github/contributors/weaviate/weaviate) | Weaviate is an open-source vector database that stores both objects and vectors, allowing for the combination of vector search with structured filtering with the fault tolerance and scalability of a cloud-native database​. | cloud,vector |

## Observation

| Name | Stars | Release | Contributors | About | Tag |
| ---- | ---- | ---- | ---- | ---- | ---- |
| **[OpenLLMetry](https://github.com/traceloop/openllmetry)** | ![Stars](https://img.shields.io/github/stars/traceloop/openllmetry.svg) | ![Release](https://img.shields.io/github/release/traceloop/openllmetry) | ![Contributors](https://img.shields.io/github/contributors/traceloop/openllmetry) | Open-source observability for your LLM application, based on OpenTelemetry | |
| **[Helicone AI](https://github.com/Helicone/helicone)** | ![Stars](https://img.shields.io/github/stars/helicone/helicone.svg) | ![Release](https://img.shields.io/github/release/helicone/helicone) | ![Contributors](https://img.shields.io/github/contributors/helicone/helicone) | 🧊 The open-source LangSmith alternative for logging, monitoring, and debugging AI applications.| |
| **[phoenix](https://github.com/arize-ai/phoenix)** | ![Stars](https://img.shields.io/github/stars/arize-ai/phoenix.svg) | ![Release](https://img.shields.io/github/release/arize-ai/phoenix) | ![Contributors](https://img.shields.io/github/contributors/arize-ai/phoenix) | ML Observability in a Notebook - Uncover Insights, Surface Problems, Monitor, and Fine Tune your Generative LLM, CV and Tabular Models | |
| **[wandb](https://github.com/wandb/wandb)** | ![Stars](https://img.shields.io/github/stars/wandb/wandb.svg) | ![Release](https://img.shields.io/github/release/wandb/wandb) | ![Contributors](https://img.shields.io/github/contributors/wandb/wandb) | 🔥 A tool for visualizing and tracking your machine learning experiments. This repo contains the CLI and Python API. | |

## Alignment

| Name | Stars | Release | Contributors | About | Tag |
| ---- | ---- | ---- | ---- | ---- | ---- |
| **[OpenRLHF](https://github.com/OpenLLMAI/OpenRLHF)** | ![Stars](https://img.shields.io/github/stars/openllmai/openrlhf.svg) | ![Release](https://img.shields.io/github/release/openllmai/openrlhf) | ![Contributors](https://img.shields.io/github/contributors/openllmai/openrlhf) | An Easy-to-use, Scalable and High-performance RLHF Framework (70B+ PPO Full Tuning & Iterative DPO & LoRA & Mixtral) | |
| **[Self-RLHF](https://github.com/PKU-Alignment/safe-rlhf)** | ![Stars](https://img.shields.io/github/stars/PKU-Alignment/safe-rlhf.svg) | ![Release](https://img.shields.io/github/release/PKU-Alignment/safe-rlhf) | ![Contributors](https://img.shields.io/github/contributors/PKU-Alignment/safe-rlhf) | Safe RLHF: Constrained Value Alignment via Safe Reinforcement Learning from Human Feedback | |

## Outputs

| Name | Stars | Release | Contributors | About | Tag |
| ---- | ---- | ---- | ---- | ---- | ---- |
| **[Instructor](https://github.com/jxnl/instructor)** | ![Stars](https://img.shields.io/github/stars/jxnl/instructor.svg) | ![Release](https://img.shields.io/github/release/jxnl/instructor) | ![Contributors](https://img.shields.io/github/contributors/jxnl/instructor) | structured outputs for llms | |
| **[Outlines](https://github.com/outlines-dev/outlines)** | ![Stars](https://img.shields.io/github/stars/outlines-dev/outlines.svg) | ![Release](https://img.shields.io/github/release/outlines-dev/outlines) | ![Contributors](https://img.shields.io/github/contributors/outlines-dev/outlines) | Structured Text Generation | |
