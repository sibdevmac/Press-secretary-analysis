# 📰 Press Secretary – Media Bias Ecosystem Analysis

## 📌 Project Overview

Press freedom is frequently emphasized in Western democracies, particularly in the United States. However, White House press secretaries operate within a structured media ecosystem where certain news agencies dominate coverage.

This project analyzes a custom-built dataset containing:

- **Press Secretary**
- **Years**
- **President**
- **Commonly Covering News Agencies**
- **Publication Bias**

The goal of this project is to examine:

- Media dominance patterns
- Publication bias distribution
- Exposure to non-centrist media
- Polarization trends across presidencies
- The evolving press ecosystem in the White House

All analysis was performed using Python.

---

## 📊 Key Findings

---

### 1️⃣ Dominant News Agencies in the White House Ecosystem

<img width="563" height="495" alt="image" src="https://github.com/user-attachments/assets/0edabcf9-bdb7-4d22-ad6f-5c434f1da50d" />

Most press secretaries were commonly covered by:

| News Agency | Count |
|-------------|--------|
| Associated Press | 14 |
| Reuters | 14 |
| CNN | 13 |
| New York Times | 10 |
| Fox News | 3 |

### 🔎 Insight:

- Associated Press and Reuters dominate institutional coverage.
- CNN also shows strong presence.
- Fox News appears significantly less represented in this dataset.
  
This suggests that journalists aiming to enter White House reporting may benefit from beginning their careers at highly represented agencies.

---

### 2️⃣ Overall Publication Bias Distribution

<img width="627" height="470" alt="image" src="https://github.com/user-attachments/assets/176b2e5d-b9a2-4990-8a7e-0a908c9c8a49" />

The distribution of publication bias across the dataset shows:

- Center (largest share)
- Left
- Lean Left
- Right
- Center-Left
- Others

### 🔎 Insight:

Although centrist publications dominate numerically, left-leaning outlets form a strong secondary layer. This reflects the broader ideological tension between conservative movements and mainstream media institutions in the U.S.

---

### 3️⃣ Press Secretary Exposure to Non-Center Publications

To measure polarization, a **Non-Center Exposure Index** was created:


Non-Center = Lean Left + Left + Right + Independent

<img width="625" height="470" alt="image" src="https://github.com/user-attachments/assets/fd7ff93e-6f44-4a9c-b748-e66716c4d05b" />

The graph **“Press Secretary Exposure to Non-Center Publications”** showed higher exposure levels for:

- Ari Fleischer  
- Jen Psaki  
- Karine Jean-Pierre  
- Karoline Leavitt  

### 🔎 Insight:

These press secretaries had comparatively higher exposure to non-centrist publications, indicating stronger interaction with ideologically positioned media.

---

### 4️⃣ Average Non-Center Bias Exposure by President

<img width="630" height="470" alt="image" src="https://github.com/user-attachments/assets/e9ee9d34-72ca-44d2-a033-dca27d6edaeb" />

The graph **“Average Non-Center Bias Exposure by President”** indicates:

- A measurable rise in non-centrist exposure over time
- Peak polarization during the Biden administration

### 🔎 Insight:

This suggests increasing media fragmentation and ideological sorting. The rise of alternative media platforms, podcasts, and digital-first outlets reflects a shift in how political narratives are constructed and consumed.

---

### 5️⃣ Bias Exposure by President (Press Secretary Ecosystem)

<img width="630" height="470" alt="image" src="https://github.com/user-attachments/assets/9644234c-9fcd-4ca4-b442-f957a0592657" />

The graph **“Bias Exposure by President”** reveals:

- Donald Trump shows higher overall non-centrist exposure
- Bush administration appears more balanced
- Obama administration shows stronger left-leaning exposure

For example:


Trump Non-Center Exposure = 19
(4 + 8 + 1 + 5 + 1 = 19)


### 🔎 Insight:

- Trump's administration demonstrates greater polarization in media interaction.
- Obama's ecosystem reflects stronger left-leaning engagement.
- Bush shows comparatively balanced exposure.

This indicates that press secretaries play a meaningful role in shaping the media narrative and influencing ideological media engagement.

---

## Author
Sibankar Saha
