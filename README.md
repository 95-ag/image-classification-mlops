# End-to-End Image Classification with MLOps

Train, track, and deploy an image classifier (TensorFlow) to AWS with automated MLOps pipeline.

## Tech Stack

- TensorFlow
- Docker
- FastAPI
- MLflow
- SQL (SQLite)
- AWS
- GitHub Actions
<!--
- (other key tools -  e.g., pandas, NumPy, OpenCV, matplotlib)
-->

## Motivation

I built this project to practice the full MLOps lifecycle, including Docker-based deployment and cloud hosting (AWS), as well as experiment tracking and reproducibility best-practices.

## Data

I chose to use Kaggle's Fashion Product Images Small for this image classifer project.

### Download Dataset

1. Sign up and accept terms on [Kaggle](https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-small).
2. Install the Kaggle CLI and create API credentials (see Kaggle instructions).
3. Run these commands:
```
pip install kaggle
kaggle datasets download -d paramaggarwal/fashion-product-images-small
unzip fashion-product-images-small.zip -d data/
```

## Features / Roadmap

- [x] Standard ML project structure
- [ ] Data ingestion with SQL integration
- [ ] Multiple TensorFlow model versions
- [ ] MLflow experiment tracking
- [ ] Model export to ONNX
- [ ] FastAPI inference API
- [ ] Docker containerization
- [ ] AWS deployment (free tier)
- [ ] CI/CD and GitHub Actions
- [ ] Documentation & API usage examples

## Getting Started

### Prerequisites

- Python version
- Git
- (add as needed)

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/95-ag/image-classification-mlops.git
   ```
2. Install dependencies
   ```sh
   pip install -r requirements.txt
   ```
3. Run the project
   ```sh
   python main.py
   ```

## Usage / Results

API usage examples and metrics will be reported here as features are implemented.
<!--
Examples of how the project can be used (API Example). Additional screenshots, code examples and demos work. 
_For more examples, please refer to the [Documentation](https://example.com)_
## Results
- Key learning outcome or highlight
- Show quick results—metrics, plot example, or link to notebook/file/results if preferred.
-->
  
## References

- [Google Cloud - MLOps](https://cloud.google.com/architecture/mlops-continuous-delivery-and-automation-pipelines-in-machine-learning)
<!--
- Tutorials/blogs learned from or followed
- Papers, if relevant
-->

## Author

Aishwarya Ganesan

## License
See the LICENSE file for license rights and limitations (MIT).
<!-- add license link if needed -->
