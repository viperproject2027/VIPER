# 🐍 VIPER — Vision Intelligente et Plotter Efficace Rectangulaire

<br>

### 🏆 Olympiades de Sciences de l'Ingénieur — Session 2027

---

## 📝 Présentation du Projet

**VIPER** est un robot médical d'aide à l'écriture et à la rééducation conçu pour les patients atteints de troubles moteurs (tels que la maladie de Parkinson). 

S'inspirant de la cinématique mécanique rigide **CoreXY** d'une *Voron V0.2*, le système embarque une Intelligence Artificielle basée sur la vision et un traitement du signal avancé pour filtrer et annuler activement les tremblements de l'utilisateur.

---

## 🚀 Fonctionnalités Clés

* **👁️ Vision Intelligente** Analyse en temps réel du besoin du patient, suivi précis des mouvements et génération de trajectoires fluides adaptées via un **Raspberry Pi 5**.

* **📐 Plotter Efficace Rectangulaire** Architecture mécanique CoreXY ultra-rigide permettant des déplacements cartésiens rapides, précis et sans jeu cinématique.

* **📉 Input Shaping (ADXL345)** Filtration active à 100% des vibrations et résonances mécaniques du robot pour garantir un tracé d'une précision chirurgicale.

* **⚡ Sécurité Médicale** Compartiment électrique 230V entièrement scellé sous double-fond, protégé par un interrupteur général lumineux **KCD2**.

---

## 🛠️ Structure du Dépôt

* `📁 CAO_Mecanique` &mdash; Modélisations 3D de la structure et du chariot (fichiers STEP).
* `📁 Code_IA` &mdash; Scripts Python, modèles de vision et traitement pour l'assistance au dessin.
* `📁 Configuration_Klipper` &mdash; Paramètres du firmware et profils de calibration des filtres.
