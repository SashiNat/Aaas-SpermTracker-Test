# AaaS Sperm Tracker Test Project

This repo is a hands-on evaluation task for candidates exploring roles in developing the Andrology as a Service (AaaS) platform.

## Objective
Build a basic Python tool that can:
1. Load sperm motility videos
2. Detect and track sperm cells using OpenCV (or ML if desired)
3. Classify movement into:
   - Fast-moving
   - Slow-moving
   - Non-moving
4. Output a CSV with per-frame statistics
5. (Bonus) Visualize bounding boxes or trajectories
6. ---

### 🟡 Bonus (Optional, Not Required)

If you're familiar with basic Python front-end frameworks like **Streamlit** or **Flask**, you may optionally build a UI to:

- Upload `.mp4` video file
- Trigger the analysis
- Display the report table in the browser
- Show download buttons for CSV or annotated video

This is **not required** for evaluation, but is a plus if completed.

---


## Dataset
👉 You can download real sperm motility videos from the public [VISEM dataset](https://zenodo.org/record/7293726).
- Suggested file: `annotated_videos.zip`
- Use 1 or 2 `.mp4` files from that zip and place them inside `/videos`

## Tools You Can Use
- Python
- OpenCV
- YOLOv5 or any detection model
- CSV or Matplotlib (for visualization)

## How to Submit
- Share your GitHub repo or zip with code + output CSV + annotated video (optional)
- Include a short Loom (2–3 min) or README summary of your approach

## Time Allotment
~3–4 hours max. We’re evaluating working knowledge, not a polished product.

## Submission
- Fork this repo and push your changes
- Or email a zip containing:
  - Your `output/` folder
  - Your code
  - A short note or Loom link explaining your approach

Good luck! 🚀
