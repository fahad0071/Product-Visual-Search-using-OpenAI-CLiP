# Product-Visual-Search-using-OpenAI-CLiP

The VisualShop project aims to revolutionize the online shopping experience by introducing a cutting-edge visual search system for e-commerce. This system, powered by advanced AI and computer vision technologies, allows users to effortlessly upload images of desired products, eliminating the need for precise text information. Leveraging the multi-modal CLIP model, a variant of the Vision Transformer (VIT), and the Pinecone vector database, the system analyzes images, identifies visual features, and searches the catalog for visually similar items. The result is an enhanced product discovery process, providing users with a seamless and language-free shopping experience.

## Implementation Stack
AI and Computer Vision: OpenAI's CLIP model is used to get images based on both image and textual input.

Vector Database: Pinecone is utilized as the vector database, ensuring efficient storage and similarity search.

User Interface (UI): The project features a Streamlit-based UI, offering an intuitive and interactive platform for users to perform visual searches.

## Getting Started
Clone the repository to your local machine.

git clone https://github.com/fahad0071/Product-Visual-Search-using-OpenAI-CLiP.git

## Install the required dependencies.

pip install -r requirements.txt

## Run the Streamlit application to launch the visual search interface.

streamlit run app.py




