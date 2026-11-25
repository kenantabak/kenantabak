### Merhaba, Ben Kenan Tabak 👋

Bilgisayarlı görü (*Computer Vision*) alanında nesne tespiti (**YOLO**, **DETR**, **ONNX**) ve örnek segmentasyonu üzerine çalışan; açık kaynaklı Türkçe veri setleri, üretime hazır model ağırlıkları (`.pt` / `.onnx`) ve pratik mühendislik notları paylaşan bir geliştiriciyim.

Çalışmalarımı **[EVREN (`ssyz.org.tr`)](https://evren.ssyz.org.tr/users/u19979974710e)** platformunda geliştiriyor; açık ağırlık, veri seti ve canlı demoları **[Hugging Face (`@kenantabak`)](https://huggingface.co/kenantabak)** üzerinde, teknik makale serilerimi ise **[Dev.to (`@kenantabak`)](https://dev.to/kenantabak)** üzerinde paylaşıyorum.

[![EVREN](https://img.shields.io/badge/EVREN-Profile-10B981?style=for-the-badge)](https://evren.ssyz.org.tr/users/u19979974710e)
[![Hugging Face](https://img.shields.io/badge/Hugging_Face-19_Models_·_10_Datasets_·_4_Spaces-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/kenantabak)
[![Dev.to](https://img.shields.io/badge/Dev.to-Technical_Series-0A0A0A?style=for-the-badge&logo=dev.to&logoColor=white)](https://dev.to/kenantabak)
[![Live ONNX Demo](https://img.shields.io/badge/Live_Demo-Browser_ONNX-6366F1?style=for-the-badge)](https://huggingface.co/spaces/kenantabak/EVREN-Live-Object-Detection-Demo)

---

### Teknoloji ve Araçlar

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![ONNX Runtime](https://img.shields.io/badge/ONNX_Runtime-005CED?style=flat-square&logo=onnx&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Gradio](https://img.shields.io/badge/Gradio-F97316?style=flat-square&logo=gradio&logoColor=white)

---

### Açık Kaynak Projeler

| Proje | Açıklama | Stack |
|---|---|---|
| **[evren-yolo-vision-kit](https://github.com/kenantabak/evren-yolo-vision-kit)** | Hugging Face üzerindeki açık (`.pt` / `.onnx`) nesne tespiti modellerini tek komutla çalıştıran saf **ONNX Runtime** / PyTorch çıkarım SDK'sı ve CLI aracı. | `Python` · `ONNX` · `PyTorch` |
| **[evren-cv-dataset-quality-auditor](https://github.com/kenantabak/evren-cv-dataset-quality-auditor)** | Büyük ölçekli CV veri setlerinde bozuk/aşırı kutu, `Errno 36` dosya adı, sıfır örnekli sınıf ve kalite puanı denetimi yapan Python paketi. | `Python` · `Pytest` · `CI` |
| **[evren-dual-verifier-auto-annotator](https://github.com/kenantabak/evren-dual-verifier-auto-annotator)** | İkili model uzlaşısı (IoU konsensüsü) ve eksik kutu tespitiyle yüksek kesinlikli etiket doğrulama kütüphanesi. | `Python` · `Pytest` · `CI` |
| **[evren-yolo26-yolo11-training-suite](https://github.com/kenantabak/evren-yolo26-yolo11-training-suite)** | Trafik levhaları, İHA/hava görüntüleri, tıbbi radyoloji ve endüstriyel İSG sahnelerine özel YAML eğitim profilleri, `preflight` araçları ve COCO→YOLO bölücü. | `YOLO` · `YAML` · `Pytest` |
| **[evren-turkish-cv-datasets-catalog](https://github.com/kenantabak/evren-turkish-cv-datasets-catalog)** | EVREN üzerinde hazırlanmış **367** açık kaynaklı (`CC-BY-4.0`) bilgisayarlı görü veri setinin indeksi, arama CLI'ı ve keşif defteri. | `Pandas` · `Parquet` · `CLI` |
| **[evren-yolo26-83-models-benchmark](https://github.com/kenantabak/evren-yolo26-83-models-benchmark)** | Farklı sektörlerde eğitilen **162+** modelin mimari, çözünürlük ve `mAP@50` / `mAP@50-95` / `F1` karşılaştırma verileri. | `Python` · `Jupyter` · `JSON/CSV` |

---

### Canlı Hugging Face Vitrinleri (`4` Space)

- 🎯 **[EVREN Live Object Detection Demo (Browser ONNX)](https://huggingface.co/spaces/kenantabak/EVREN-Live-Object-Detection-Demo)** — Sunucusuz, doğrudan tarayıcıda WebAssembly ile çalışan canlı nesne tespiti demosu.
- 🚀 **[EVREN Vision Explorer](https://huggingface.co/spaces/kenantabak/EVREN-YOLO26-Vision-Explorer)** — Tüm veri setleri ve model benchmark'ları için etkileşimli keşif arayüzü.
- 🗂️ **[EVREN 367 Grade-A Veri Seti Kataloğu](https://huggingface.co/spaces/kenantabak/EVREN-316-Datasets-Catalog)** — Canlı filtrelenebilir veri seti kataloğu (`3.37M+` görsel).
- ⚙️ **[EVREN Hiperparametre Danışmanı](https://huggingface.co/spaces/kenantabak/EVREN-YOLO26-Hyperparameter-Advisor)** — Alan ve nesne boyutuna göre eğitim reçetesi önerici.

### Multi-Architecture CV & ONNX Benchmark (2026 Flagship)
- **GitHub Code & Unified ONNX Decoder:** [evren-multiarch-cv-onnx-benchmark](https://github.com/kenantabak/evren-multiarch-cv-onnx-benchmark) — 24 controlled runs across **YOLO26, YOLO11, YOLOv9c, RT-DETR-L, D-FINE-M, RF-DETR-Base** + 4-thread ONNX Runtime CPU benchmarks + `pytest` CI.
- **Visually Audited Multi-Arch HF Models:** [RF-DETR-Base Skin Lesion (81.17% mAP@50)](https://huggingface.co/kenantabak/rfdetr-base-skin-lesion-detection-tr) · [D-FINE-M Traffic Signs 49 (75 MB / 336 ms CPU)](https://huggingface.co/kenantabak/dfine-m-traffic-signs-49-tr) · [YOLOv9c Traffic Signs 49 (87.94% mAP@50)](https://huggingface.co/kenantabak/yolov9c-traffic-signs-49-tr)
- **Native Parquet HF Datasets:** [Multi-Arch CV & ONNX Benchmark](https://huggingface.co/datasets/kenantabak/evren-multiarch-cv-onnx-benchmark) · [L929 Phase-Contrast Microscopy (630 Images, 26.8K Boxes)](https://huggingface.co/datasets/kenantabak/evren-l929-microscopy-cell-detection-tr)
- **Technical Writing (Dev.to):** [dev.to/kenantabak](https://dev.to/kenantabak) — Turkish computer vision engineering articles.
