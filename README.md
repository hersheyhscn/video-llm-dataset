# video-llm-dataset
A multimodal pipeline for video segmentation, annotation, and LLM dataset generation.

## Features

- Shot segmentation
- Key frame extraction
- Automatic annotation
- Multimodal dataset construction
- Metadata generation for LLM training

## Tech Stack

- Python
- OpenCV
- PyTorch
- FastAPI
- FAISS

## Pipeline

Video
→ Shot Segmentation
→ Frame Extraction
→ Annotation
→ Dataset Generation

## Project Structure

```text
video-to-llm-dataset/
├── app/
├── pipeline/
├── scripts/
├── data/
├── README.md
└── requirements.txt
