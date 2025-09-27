# face-mask-detection-VGG16-vs-MobileNetV2

این پروژه برای **تشخیص ماسک صورت** طراحی شده است. در اینجا از دو مدل محبوب یادگیری انتقالی (Transfer Learning) استفاده کردیم:

- **MobileNetV2**
- **VGG16**

---

## 📂 Dataset
- داده شامل دو کلاس است:
  - **With Mask** 😷
  - **Without Mask** 🙂
- تصاویر به سه بخش تقسیم شدند:
  - **Train**
  - **Validation**
  - **Test** (جدا شده از Train)

---

## ⚙️ Steps
1. آماده‌سازی داده‌ها با `ImageDataGenerator`
2. تقسیم داده به Train / Validation / Test
3. ساخت مدل با MobileNetV2 و VGG16
4. آموزش مدل‌ها با تکنیک‌های:
   - EarlyStopping
   - ReduceLROnPlateau
5. مقایسه دقت و خطای دو مدل

---

## 📊 Results

### Validation Accuracy
![Validation Accuracy](results/val_accuracy_comparison.png)

### Validation Loss
![Validation Loss](results/val_loss_comparison.png)

---

## 🔥 Test Results
- **MobileNetV2:** ~99.6% Accuracy  
- **VGG16:** ~100% Accuracy  

---

## 🚀 How to Run
1. کلون کردن ریپو:
   ```bash
   git clone https://github.com/your-username/face-mask-detection.git
