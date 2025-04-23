```markdown
# 🛡️ Phishing Detector (Production-Ready)

A lightweight Python-based CLI tool to detect phishing URLs using machine learning and hand-engineered features.

## 📆 Installation

```bash
git clone https://github.com/YOUR_USERNAME/phishing-detector.git
cd phishing-detector
pip install -r requirements.txt
```

## 🚀 Usage

### Train the model
```bash
python phishing_detector.py --train
```

### Predict URL status
```bash
python phishing_detector.py --url "http://example.com/login"
```

## 🧠 Features Extracted
- URL length
- HTTPS presence
- Dot/slash count
- Suspicious keywords (e.g., `login`, `verify`, `paypal`)
- IP address in domain

## 📁 Dataset Format
Make sure your `phishing_dataset.csv` contains a `label` column with:
- `1` = phishing
- `0` = safe

## 🔒 Disclaimer
Use this tool responsibly. For educational and research purposes only.
```
