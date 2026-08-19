<div align="center">

<a href="https://github.com/SadiaSiddique01">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=30&duration=3000&pause=900&color=00B4A6&center=true&vCenter=true&width=800&lines=Machine+Learning+Engineer;Arabic+NLP+and+RAG+systems;MSc+Artificial+Intelligence+%40+KFUPM;Answers+that+cite+a+page+you+can+open" alt="Machine Learning Engineer" />
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=SadiaSiddique01&label=PROFILE%20VIEWS&color=00b4a6&style=flat-square" alt="profile views" />
<a href="https://github.com/SadiaSiddique01?tab=followers"><img src="https://img.shields.io/github/followers/SadiaSiddique01?label=FOLLOWERS&style=flat-square&color=00b4a6" alt="followers" /></a>

</div>

---

## `>` whoami

```python
engineer = {
    "name":      "Sadia Siddique",
    "studying":  "MSc Artificial Intelligence @ KFUPM",
    "focus":     ["Arabic NLP", "Retrieval-Augmented Generation"],
    "building":  ["Hybrid retrieval", "Citation-grounded answers", "Multi-agent systems"],
    "interests": ["Low-resource-language IR", "OCR quality", "LLM evaluation"],
    "principle": "An answer without a source you can open is not an answer",
}
```

I build systems that **retrieve before they generate**, and that can prove where an
answer came from. Most of my recent work is Arabic-language: right-to-left layouts,
Arabic-Indic digits, scanned and photographed documents, and the retrieval problems
that come with all three.

I care about the part most RAG demos skip: **measuring whether it actually works**,
and saying plainly where it does not.

---

## `>` what I work on

<table>
<tr>
<td width="50%" valign="top">

### Retrieval & RAG
Hybrid dense + lexical retrieval, reciprocal rank fusion, parent/child chunking,
context assembly under token budgets, and citation verification at the character
level. Evaluation sets authored from source documents rather than from parser
output, so the score measures retrieval and not agreement with itself.

</td>
<td width="50%" valign="top">

### Arabic & low-resource NLP
Arabic normalisation and tokenisation for BM25, digit folding, clitic and article
handling, cross-lingual embedding so an English question finds an Arabic passage,
and OCR provenance on documents that were photographed rather than typed.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### LLM systems
Fine-tuning, sufficiency-based refusal instead of similarity thresholds, conflict
detection between sources, provider abstraction across hosted and open-weight
models, and multi-agent orchestration.

</td>
<td width="50%" valign="top">

### Computer vision
Object detection for safety monitoring, face recognition pipelines, and real-time
hand-tracking interfaces with MediaPipe and OpenCV.

</td>
</tr>
</table>

---

## `>` education

<table>
<tr>
<td width="50%" valign="top">

**MSc, Artificial Intelligence** &nbsp;·&nbsp; *in progress*
King Fahd University of Petroleum and Minerals (KFUPM)

</td>
<td width="50%" valign="top">

**Arab Open University**

</td>
</tr>
</table>

---

## `>` toolkit

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**ML / NLP**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Transformers](https://img.shields.io/badge/Transformers-FF6F00?style=flat-square&logo=huggingface&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=flat-square&logo=yolo&logoColor=black)

**Retrieval & data**

![Chroma](https://img.shields.io/badge/Chroma-FF6B6B?style=flat-square&logo=databricks&logoColor=white)
![BM25](https://img.shields.io/badge/BM25-6E56CF?style=flat-square&logo=elasticsearch&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**Serving & ops**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## `>` selected work

| project | what it is |
|---|---|
| **Arabic Document QA** | Upload Arabic documents (native PDF, scans, phone photos, Office files), ask in Arabic or English, get an answer grounded in a passage you can open on the page, or an explicit refusal. Hybrid retrieval measured at **91 % recall@5 over 216 questions**, with per-page OCR quality flags and character-level quote verification. |
| [**arabic-model-finetuning**](https://github.com/SadiaSiddique01/arabic-model-finetuning) | Fine-tuning experiments on Arabic language models. |
| [**MemAgent**](https://github.com/SadiaSiddique01/MemAgent) | Agent with persistent memory. |
| [**Construction-Hazard-Detection**](https://github.com/SadiaSiddique01/Construction-Hazard-Detection) | YOLO-based object detection for construction-site safety monitoring. |
| [**GestureBasedVolumeControl**](https://github.com/SadiaSiddique01/GestureBasedVolumeControl) | Real-time hand tracking with MediaPipe and OpenCV. |
| [**Facial Recognition Attendance**](https://github.com/SadiaSiddique01/Facial_Recognition_Based_Attendance_System) | Face-recognition attendance pipeline. |

---

## `>` stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=SadiaSiddique01&show_icons=true&hide_border=true&theme=tokyonight&include_all_commits=true&count_private=true" alt="stats" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SadiaSiddique01&layout=compact&hide_border=true&theme=tokyonight&langs_count=8" alt="top languages" />

</div>

---

<div align="center">

### `>` reach me

<a href="mailto:sadiasiddique801@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="email" /></a>
<!-- To add LinkedIn: uncomment the line below and put your URL in the href. -->
<!-- <a href="https://www.linkedin.com/in/YOUR-HANDLE"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin" /></a> -->

</div>
