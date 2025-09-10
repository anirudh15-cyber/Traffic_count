# 🚦 Traffic Analytics with YOLO 

This project is an end-to-end **Traffic Analytics System** that detects, tracks, and counts vehicles in traffic videos.  
It extends YOLO-based object detection with **multi-object tracking** and a **custom lane marker tool** for zone-wise vehicle analysis.

---

## 📌 Features
- 🚗 Detects **cars, buses, and trucks** using YOLO
- 🎯 Tracks vehicles with **BoT-SORT** for stable unique IDs
- 🖌️ **Custom Lane Marker Tool** for drawing polygon-based traffic zones
- 📊 Zone-wise **unique vehicle counting**
- 📝 Exports per-frame counts and final summary to **CSV**
- 🎨 Real-time annotated video output with bounding boxes, IDs, and zone overlays

---

## ⚙️ Tech Stack
- [YOLO (You Only Look Once)](https://github.com/ultralytics/ultralytics) – Object Detection  
- [BoT-SORT](https://github.com/NirAharon/BoT-SORT) – Multi-object Tracking  
- [OpenCV](https://opencv.org/) – Video processing & visualization  
- [Python](https://www.python.org/) – Core pipeline  
- [Pandas](https://pandas.pydata.org/) – Data export & analytics  

---
## 📊 Outputs

- **Annotated Video** → Saved with bounding boxes, track IDs, and zone overlays  
- **Per-frame CSV** → Vehicle entries per frame  
- **Final Summary CSV** → Unique vehicle counts per class and zone  

**Example output format:**
```csv
zone_0_class_2,zone_0_class_5,zone_0_class_7
15,3,6
```
---

## 🌍 Applications
- 🚦 Adaptive traffic signal control  
- 🏙️ Urban traffic density monitoring  
- 📊 Smart city planning & policy analysis  
- 🚔 Traffic rule violation detection  

---

## 📌 Future Improvements
- Support for more vehicle classes (motorcycles, bicycles, etc.)  
- Speed estimation per vehicle  
- Integration with real-time video streams (CCTV/IP cameras)  
- Cloud deployment for scalable analytics  

---

## 🤝 Contributing
Pull requests and suggestions are welcome!  
Feel free to open an issue or fork the repo.  

---

## 📄 License
This project is licensed under the **MIT License**.  

---

## 👤 Author
**Anirudh Narang**  
_Data Scientist & Deep Learning Engineer_  

🔗 [LinkedIn](https://www.linkedin.com/in/anirudh-narang/) | [GitHub](https://github.com/anirudh15-cyber)
