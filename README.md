# Assignment - 3 - Nike Shopping Bot

Welcome to the Nike Product Search Bot! This application helps you search for Nike products using both text queries and image uploads. Built with Streamlit, it leverages the CLIP model for embeddings and Pinecone for vector database management.

## Live Application

TODO : Deploy the application on GCP and add the link here to the streamlit and Fastapi application
[Add link to live application if available]
[![Live Application](https://img.shields.io/badge/codelabs-4285F4?style=for-the-badge&logo=codelabs&logoColor=white)](https://codelabs-preview.appspot.com/?file_id=1r6Cg_miHqOiVv43CM6GhOtq1ZWK9lf6mIlYW7VNuSVk)

## Video Demo

TODO : Make youtube channel and upload video and add the link here to the unlisted video
[Add link to video demo if available]
[![Video Demo](https://img.shields.io/badge/codelabs-4285F4?style=for-the-badge&logo=codelabs&logoColor=white)](https://codelabs-preview.appspot.com/?file_id=1r6Cg_miHqOiVv43CM6GhOtq1ZWK9lf6mIlYW7VNuSVk)

## Documentation

[![codelabs](https://img.shields.io/badge/codelabs-4285F4?style=for-the-badge&logo=codelabs&logoColor=white)](https://codelabs-preview.appspot.com/?file_id=1rxwEOAuZc-nYXXGWnDTdTcSZ_Ha2OzUyzep-SCzlBuo#0)

## Features

### Product Search
<img width="1276" alt="Product Search" src="https://github.com/deveshcode/shopping-multimodal-rag/assets/37287532/6de1a49e-242e-4836-bcf8-dca0e9346eba">

It performs search functionality as follows:

<img width="1280" alt="Search Functionality" src="https://github.com/deveshcode/shopping-multimodal-rag/assets/37287532/ce713ad3-4df3-4067-8004-5019404546c2">

### Virtual Try-On
You can also virtually try it on by providing your image and product image:

<img width="1280" alt="Virtual Try-On" src="https://github.com/deveshcode/shopping-multimodal-rag/assets/37287532/97c1d403-7dee-4bee-9f39-0ede08e56b55">

## Installation

1. Git clone the repository:

```bash
git clone https://github.com/deveshcode/shopping-multimodal-rag.git
cd shopping-multimodal-rag
```

2. Install the required packages:

```bash
pip install -r requirements.txt
```

3. Create a .env file in the root directory and add your API keys:

```bash
PINECONE_API_KEY=your_pinecone_api_key
OPENAI_API_KEY=your_open_ai_key
API_HOST=http://localhost:8001
BUCKET_NAME=gcs_bucket_name 
GOOGLE_APPLICATION_CREDENTIALS=gcloud_creds_json_file
azure_cv_key=azure_cv_key
azure_cv_endpoint=azure_cv_endpoint
```

## Usage

To run the REST API server:

```bash
uvicorn app:app --host 0.0.0.0 --port 8001 --reload
```

To run the Streamlit app:

```bash
streamlit run app.py
```

Open the provided URL in your web browser to access the application.

## Tools and Technologies

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io/)
[![CLIP](https://img.shields.io/badge/CLIP-FF4B4B?style=for-the-badge&logo=openai&logoColor=white)](https://beta.openai.com/docs/)
[![Pinecone](https://img.shields.io/badge/Pinecone-FF4B4B?style=for-the-badge&logo=pinecone&logoColor=white)](https://www.pinecone.io/docs/)
[![Google Cloud Storage](https://img.shields.io/badge/Google%20Cloud%20Storage-FF4B4B?style=for-the-badge&logo=google-cloud&logoColor=white)](https://cloud.google.com/storage/docs)
[![Azure Cognitive Services](https://img.shields.io/badge/Azure%20Cognitive%20Services-FF4B4B?style=for-the-badge&logo=microsoft-azure&logoColor=white)](https://docs.microsoft.com/en-us/azure/cognitive-services/)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/)

## Data Sources
Data collected from the following sources:
Nike Website : https://www.nike.com/

## Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

## License
Distributed under the MIT License. See LICENSE for more information.

## Project Team
Name | Contribution %| Contributions |
--- |--- | --- |
Devesh Surve | 50% | |
Snehil Aryan | 50% | |


## References
1. OpenAI API Documentation: https://beta.openai.com/docs/ 
2. Pinecone Documentation: https://www.pinecone.io/docs/ 
3. FastAPI Documentation: https://fastapi.tiangolo.com/ 
4. Streamlit Documentation: https://docs.streamlit.io/ 
5. Google Cloud Storage Documentation: https://cloud.google.com/storage/docs 
6. Azure Cognitive Services Documentation: https://docs.microsoft.com/en-us/azure/cognitive-services/ 
