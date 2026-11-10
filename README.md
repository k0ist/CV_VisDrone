---
title: UAV Detector (YOLO26s, VisDrone)
emoji: 🚁
colorFrom: blue
colorTo: green
sdk: gradio
python_version: 3.12.12
app_file: app.py
pinned: false
---

MVP научно-исследовательской работы: обнаружение людей и транспорта на снимках с БЛА.
Модель YOLO26s, дообучена на VisDrone по фрагментам 640×640 (модель S2); вывод по фрагментам с увеличением до 800 пикселей и дополнительным проходом по целому кадру.
