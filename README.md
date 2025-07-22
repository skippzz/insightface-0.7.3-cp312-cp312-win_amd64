# insightface-0.7.3-cp312-cp312-win_amd64

This repository provides a **precompiled Python wheel** for `insightface==0.7.3` targeting:

- **Python version:** cp312 (Python 3.12)
- **Platform:** Windows (AMD64)

## 📌 Why does this exist?

As of the time of publishing, InsightFace does not provide an official `.whl` (wheel) file for Windows users on Python 3.12.  
This causes issues when installing via `pip`—especially for environments like:

- **ComfyUI pipelines**
- **Triton inference backend setups**

To solve this, I manually built the wheel and am now sharing it for public access to help others avoid the same headache.

## 📦 Download & Install

Clone or download this repository, then:

```bash
pip install insightface-0.7.3-cp312-cp312-win_amd64.whl
