# video-llm-dataset

A multimodal pipeline for video segmentation, annotation, and LLM dataset generation.

---

## Features

- Shot segmentation
- Key frame extraction
- Automatic annotation
- Multimodal dataset construction
- Metadata generation for LLM training

---

## Tech Stack

- Python
- OpenCV
- PyTorch
- FastAPI
- FAISS

---

## Pipeline

Video → Shot Segmentation → Frame Extraction → Annotation → Dataset Generation

---

## Project Structure

```text
video-llm-dataset/
├── app/
├── pipeline/
├── scripts/
├── data/
├── README.md
└── requirements.txt
```

---

## Future Plans

- Fashion show analysis
- Video semantic search
- Multimodal retrieval
- AI dataset platform

---

## How to Run

```bash
pip install -r requirements.txt
python app/main.py
```

---

## Example

Input:
- video.mp4

Output:
- shots
- frames
- annotations
