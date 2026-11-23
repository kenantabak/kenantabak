### Merhaba, Ben Kenan Tabak

Bilgisayarlı görü (Computer Vision) alanında nesne tespiti (**YOLO26**, **YOLO11**) ve örnek segmentasyonu üzerine çalışan, açık kaynaklı Türkçe veri setleri ve üretime hazır model ağırlıkları (`.pt` / `.onnx`) geliştiren bir araştırmacı ve geliştiriciyim.

Çalışmalarımı **[EVREN (`ssyz.org.tr`)](https://evren.ssyz.org.tr/users/u19979974710e)** platformunda geliştirip, açık ağırlıklar ve veri seti katalogları olarak **[Hugging Face (`@kenantabak`)](https://huggingface.co/kenantabak) [![Dev.to](https://img.shields.io/badge/Dev.to-Technical_Blog-0A0A0A?style=for-the-badge&logo=dev.to&logoColor=white)](https://dev.to/kenantabak)** üzerinde paylaşıyorum.

---

### Teknoloji ve Araçlar

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX_Runtime-005CED?style=flat-square&logo=onnx&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Python](https://img.shields.io/badge/Python_3.11-3776AB?style=flat-square&logo=python&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Gradio](https://img.shields.io/badge/Gradio-F97316?style=flat-square)

---

### Açık Kaynak Projeler

| Proje | Açıklama | Stack |
| :--- | :--- | :--- |
| **[evren-yolo-vision-kit](https://github.com/kenantabak/evren-yolo-vision-kit)** | Hugging Face üzerindeki açık `YOLO26` & `YOLO11` (`.pt` / `.onnx`) modellerini tek komutla çalıştıran saf **ONNX Runtime** / PyTorch çıkarım SDK'sı, CLI aracı ve Gradio arayüzü. | `Python` · `ONNX` · `PyTorch` · `Gradio` |
| **[evren-yolo26-yolo11-training-suite](https://github.com/kenantabak/evren-yolo26-yolo11-training-suite)** | Trafik levhaları, İHA/hava görüntüleri, tıbbi radyoloji ve endüstriyel İSG sahnelerine özel YAML eğitim profilleri, veri ön-denetim araçları (`preflight`) ve COCO→YOLO bölücü. | `YOLO26` · `YOLO11` · `YAML` · `Pytest` |
| **[evren-turkish-cv-datasets-catalog](https://github.com/kenantabak/evren-turkish-cv-datasets-catalog)** | EVREN üzerinde hazırlanmış 328 açık kaynaklı (`CC-BY-4.0`) bilgisayarlı görü veri setinin indeksi, arama CLI'ı ve keşif defteri (`EDA Notebook`). | `Pandas` · `Parquet` · `CLI` |
| **[evren-yolo26-83-models-benchmark](https://github.com/kenantabak/evren-yolo26-83-models-benchmark)** | Farklı sektörlerde eğitilen 126 `PRODUCTION` modelin mimari, çözünürlük ve augmentation etkilerini inceleyen benchmark veri seti ve analiz araçları. | `Python` · `Jupyter` · `CSV/JSON` |

---

### Öne Çıkan Açık Model Ağırlıkları (`.pt` & `.onnx`)

Tüm modeller `CC-BY-4.0` lisanslıdır ve doğrudan [`kenantabak` Hugging Face](https://huggingface.co/kenantabak) üzerinden indirilebilir:

| Alan | Model | Mimari | mAP@50 | İndir & İncele |
| :--- | :--- | :---: | :---: | :--- |
| **Tarım / Gıda** | Yer Fıstığı Küf ve Kalite Tespiti | `yolo26s` | `%99.50` | [Hugging Face](https://huggingface.co/kenantabak/yolo26s-peanut-mold-quality-detection-tr) · [EVREN](https://evren.ssyz.org.tr/models/u19979974710e/yer-fistigi-kuf-ve-kalite) |
| **Elektronik / Kalite** | PCB 6 Üretim Kusuru Tespiti | `yolo11s` | `%99.15` | [Hugging Face](https://huggingface.co/kenantabak/yolo11s-pcb-defect-inspection-6class-tr) · [EVREN](https://evren.ssyz.org.tr/models/u19979974710e/baskili-devre-karti-pcb-6-uretim-kusuru-tespiti-modeli) |
| **Endüstriyel İSG** | Endüstriyel KKD Tespiti Pro | `yolo26x` | `%98.48` | [Hugging Face](https://huggingface.co/kenantabak/yolo26x-industrial-ppe-safety-pro-tr) · [EVREN](https://evren.ssyz.org.tr/models/u19979974710e/endustriyel-kkd-tespiti-pro) |
| **Havacılık / İHA** | Havalimanı Apron Araçları Tespiti | `yolo11s` | `%98.03` | [Hugging Face](https://huggingface.co/kenantabak/yolo11s-airport-apron-ground-vehicles-tr) · [EVREN](https://evren.ssyz.org.tr/models/u19979974710e/havalimani-apron-ve-yer-hizmetleri-araclari-tespiti) |
| **Termal IR** | Termal İnsan ve Arama-Kurtarma Köpeği | `yolo26s` | `%97.92` | [Hugging Face](https://huggingface.co/kenantabak/yolo26s-thermal-human-canine-detection-tr) · [EVREN](https://evren.ssyz.org.tr/models/u19979974710e/termal-insan-ve-kopek-tespiti) |
| **Otonom Sürüş** | Karayolu 23 Sınıf Trafik İşaretleri | `yolo26s` | `%95.53` | [Hugging Face](https://huggingface.co/kenantabak/yolo26s-highway-traffic-signs-23class-tr) · [EVREN](https://evren.ssyz.org.tr/models/u19979974710e/karayolu-trafik-isaretleri-hiz-siniri-ve-sinyalizasyon-tespiti-23-sinif) |
| **Afet / Orman** | Orman Yangını Dumanı Erken Tespit | `yolo26s` | `%93.96` | [Hugging Face](https://huggingface.co/kenantabak/yolo26s-wildfire-smoke-early-detection-tr) · [EVREN](https://evren.ssyz.org.tr/models/u19979974710e/orman-yangini-dumani-tespiti) |
| **Medikal** | Diş Röntgeni Anomali ve İmplant Tespiti | `yolo26s` | `%79.80` | [Hugging Face](https://huggingface.co/kenantabak/yolo26s-dental-xray-pathology-detection-tr) · [EVREN](https://evren.ssyz.org.tr/models/u19979974710e/dis-rontgeni-curuk-dolgu-gomulu-dis-ve-implant-tespiti) |

---

### Bağlantılar

- **EVREN Profilim:** [https://evren.ssyz.org.tr/users/u19979974710e](https://evren.ssyz.org.tr/users/u19979974710e)
- **Hugging Face:** [https://huggingface.co/kenantabak](https://huggingface.co/kenantabak)
- **İnteraktif Model & Veri Seti Gezgini:** [EVREN YOLO26 Vision Explorer](https://huggingface.co/spaces/kenantabak/EVREN-YOLO26-Vision-Explorer)

### Newly Added Production Models (22 November 2026)

| Model Repository | Domain | Architecture | mAP@50 | mAP@50-95 | F1 |
|---|---|---|---:|---:|---:|
| [kenantabak/yolo26s-knee-xray-acl-detection-tr](https://huggingface.co/kenantabak/yolo26s-knee-xray-acl-detection-tr) | Diz Röntgeninde Ön Çapraz Bağ (ACL) Bölgesi Tespiti | `yolo26s` | **99.50%** | 75.06% | 100.00% |
| [kenantabak/yolo26s-structural-surface-crack-detection-tr](https://huggingface.co/kenantabak/yolo26s-structural-surface-crack-detection-tr) | Yüzey ve Yapısal Çatlak Tespiti (320px Hafif Model) | `yolo26s` | **99.34%** | 74.78% | 98.69% |
| [kenantabak/yolo26s-maritime-naval-vessel-detection-tr](https://huggingface.co/kenantabak/yolo26s-maritime-naval-vessel-detection-tr) | Deniz Gözetiminde Savaş Gemisi Tespiti | `yolo26s` | **99.23%** | 80.85% | 98.46% |
| [kenantabak/yolo26s-powerline-insulator-defect-tr](https://huggingface.co/kenantabak/yolo26s-powerline-insulator-defect-tr) | Elektrik İletim Hattı İzolatör ve Yüzey Hasarı Tespiti | `yolo26s` | **98.25%** | 76.12% | 96.95% |

### Newly Added Open-Source Repositories & Dataset Suites (22 November 2026)

- **GitHub Tools (7 Repositories):**
  - [`kenantabak/evren-cv-dataset-quality-auditor`](https://github.com/kenantabak/evren-cv-dataset-quality-auditor) — Automated CV dataset quality & health auditing SDK (`Errno 36` filename sanitizer, `selected_class_ids` zero-val filter, bbox geometry verifier).
  - [`kenantabak/evren-dual-verifier-auto-annotator`](https://github.com/kenantabak/evren-dual-verifier-auto-annotator) — Dual-Architecture (`YOLO26/YOLO11` Teacher + `GroundingDINO` VLM) consensus auto-annotation engine.
- **Hugging Face Dataset Suites (10 Datasets):**
  - [`kenantabak/evren-maritime-naval-underwater-vision-suite`](https://huggingface.co/datasets/kenantabak/evren-maritime-naval-underwater-vision-suite)
  - [`kenantabak/evren-civil-infrastructure-energy-defect-suite`](https://huggingface.co/datasets/kenantabak/evren-civil-infrastructure-energy-defect-suite)
  - [`kenantabak/evren-retail-logistics-warehouse-vision-suite`](https://huggingface.co/datasets/kenantabak/evren-retail-logistics-warehouse-vision-suite)

