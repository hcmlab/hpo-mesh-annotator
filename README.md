# HPO-Mesh-Annotator

[![Plotly](https://img.shields.io/badge/Plotly-3D%20Scatter-blueviolet)](https://plotly.com/javascript/3d-scatter-plots/)
[![HPO](https://img.shields.io/badge/Human%20Phenotype%20Ontology-orange)](https://hpo.jax.org/app/)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3-green)](https://getbootstrap.com/)

**Interactive 3D face mesh annotation tool for Human Phenotype Ontology (HPO) facial phenotyping.**

## 🚀 Quick Start

1. [**Open** in any modern browser](https://hcmlab.github.io/hpo-mesh-annotator/)
2. **Annotate** points by clicking (blue=selected, gray=unselected)
3. **Navigate** steps with Next/Previous or arrow keys
4. **Export** `face-mesh-selections-YYYY-MM-DD.json`

## 📊 HPO Steps (15 Total)

| Step | HPO Term                                |
|------|-----------------------------------------|
| 1    | Abnormality of the mouth                |
| 2    | Abnormality of the orbital region       |
| 3    | Abnormality of the nose                 |
| 4    | Abnormality of the eye                  |
| 5    | Abnormality of facial soft tissue       |
| 6    | Abnormal midface morphology             |
| 7    | Abnormal forehead morphology            |
| 8    | Abnormal facial shape                   |
| 9    | Abnormality of the periorbital region   |
| 10   | Abnormality of the chin                 |
| 11   | Abnormality of the submandibular region |
| 12   | Abnormal facial expression              |
| 13   | Craniofacial hyperostosis               |
| 14   | Craniofacial dysostosis                 |
| 15   | Tessier cleft                           |

## 💾 Sample JSON Output

```

{
   "version": "1.0.0",
   "generated": "2025-12-05T22:16:00.000Z",
   "steps": [
      {
         "index": 0,
         "name": "Abnormality of the mouth",
         "selectedPoints": [0, 1, 2, 3]
      }
   ]
}

```

## 🔍 Use Cases

- **Craniofacial phenotyping** for research
- **Rare disease classification** training data generation
- **Medical AI datasets** for facial landmark annotation
- **HPO validation** of MediaPipe face mesh points

## 📱 Controls

- **Click points** to toggle selection
- **Ctrl/Cmd + Drag** to pan
- **Scroll** to zoom
- **← → arrows** navigate steps
- **Reset All** clears every step
- **Export JSON** downloads selections

## 🎨 Customization

Edit `faceMesh` array or `STEPS` in source:

```

const STEPS = ["Your", "Custom", "HPO", "Terms"];

```

---

⭐ **Star if useful for HPO facial phenotyping!**

