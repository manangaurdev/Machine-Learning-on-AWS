# Amazon Nova with Amazon Bedrock - Machine Learning Workshop

This repository contains hands-on tutorials and examples for working with Amazon Nova models through AWS Bedrock. The workshop focuses on multimodal understanding, creative content generation, and fine-tuning using Amazon's state-of-the-art AI models.

## Overview

Amazon Nova offers two categories of models:
1. **Understanding Models** - Process multiple input modalities (text, video, image) and output text
   - Amazon Nova Micro: Fast, cost-effective text-only model
   - Amazon Nova Lite: Affordable multimodal foundation model
   - Amazon Nova Pro: State-of-the-art multimodal model
2. **Creative Content Generation Models**
   - Amazon Nova Canvas: Image generation
   - Amazon Nova Reel: Video generation

## Workshop Contents

1. `01_Intro_to_Bedrock_Amazon_Nova.ipynb`: Introduction to Amazon Nova models and basic setup
2. `02_Multi_modal_RAG_Amazon_Bedrock_Nova.ipynb`: Advanced multimodal RAG (Retrieval Augmented Generation) implementation
3. `fine-tuning-with-sagemakerai-and-bedrock/`: Comprehensive guide to fine-tuning foundation models
   - Task 1: Foundation Model Playground
   - Task 2: Customizing Foundation Models
   - Task 3: Foundation Model Evaluation
   - Task 4: Responsible AI Practices
   - Task 6: Partner AI Applications

## Prerequisites

- AWS Account with access to Bedrock service
- Python 3.x
- Required packages (install via `pip install -r requirements.txt`):
  - boto3
  - langchain and related packages
  - PyMuPDF
  - FAISS for vector operations
  - Other utility packages for data processing

## Setup Instructions

1. Request model access in AWS Bedrock following the [official documentation](https://docs.aws.amazon.com/bedrock/latest/userguide/model-access-modify.html)
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Configure AWS credentials with appropriate permissions

## Model Selection Guide

- **Nova Micro**: Best for high-volume, latency-sensitive tasks like classification, routing, entity extraction, and document summarization
- **Nova Lite**: Ideal for complex scenarios requiring low latency and multimodal capabilities
- **Nova Pro**: Suited for advanced reasoning, creativity, and code generation tasks with multimodal inputs

## Fine-tuning Guide

The workshop includes a comprehensive fine-tuning section that covers:

1. **Foundation Model Playground**: Get hands-on experience with foundation models
2. **Customization**: Learn how to fine-tune models for specific use cases
3. **Evaluation**: Understand how to evaluate model performance
4. **Responsible AI**: Implement best practices for responsible AI development
5. **Partner Integration**: Learn how to integrate with partner AI applications

To get started with fine-tuning:
1. Navigate to the `fine-tuning-with-sagemakerai-and-bedrock` directory
2. Follow the tasks in sequence from 01 to 06
3. Each task includes detailed instructions and examples

## Directory Structure

```
.
├── data/                   # Data files for examples
├── imgs/                   # Image assets for notebooks
├── fine-tuning-with-sagemakerai-and-bedrock/  # Fine-tuning workshop materials
│   ├── task_01_foundation_model_playground/
│   ├── task_02_customize_foundation_model/
│   ├── task_03_foundation_model_evaluation/
│   ├── task_04_responsible_ai/
│   ├── task_06_partner_ai_apps/
│   └── utilities/
├── *.ipynb                 # Jupyter notebooks with tutorials
└── requirements.txt        # Python package dependencies
```

## Additional Resources

- [AWS Bedrock Documentation](https://docs.aws.amazon.com/bedrock/)
- [Amazon Nova Model Documentation](https://docs.aws.amazon.com/bedrock/latest/userguide/what-is-bedrock.html)
- [AWS SageMaker Documentation](https://docs.aws.amazon.com/sagemaker/)
- [Fine-tuning Best Practices](https://docs.aws.amazon.com/bedrock/latest/userguide/fine-tuning.html)
