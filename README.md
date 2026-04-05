# 🦠 Mise en Évidence d'une Attaque par Ransomware

> Projet Cybersécurité · Aminata Diallo · Master 1 Cybersécurité & Science des Données · Université Paris 8 · 2025–2026

---

## 🎯 Objectif

Analyser et démontrer les mécanismes techniques d'une attaque par **ransomware** : vecteurs d'infection, chiffrement des fichiers, propagation et mesures de défense.

---

## 📋 Contenu du projet

### Phases de l'attaque étudiées

| Phase | Description |
|---|---|
| **1. Infection** | Vecteurs d'entrée : phishing, exploitation de vulnérabilités, RDP |
| **2. Persistance** | Mécanismes de maintien d'accès sur le système |
| **3. Chiffrement** | Algorithmes utilisés (AES, RSA hybride), ciblage des fichiers |
| **4. Exfiltration** | Double extorsion — vol de données avant chiffrement |
| **5. Rançon** | Communication C2, paiement en crypto-monnaie |
| **6. Défense** | Contre-mesures, détection, récupération |

### Mécanismes techniques analysés

- **Chiffrement hybride** : clé AES générée localement, chiffrée avec RSA public
- **Shadow Copy deletion** : suppression des sauvegardes Windows
- **Lateral movement** : propagation réseau via SMB, WMI
- **Obfuscation** : techniques d'évasion antivirus

---

## 🛡️ Contre-mesures identifiées

```
✅ Sauvegardes isolées (règle 3-2-1)
✅ Segmentation réseau
✅ Principe du moindre privilège
✅ Mise à jour des systèmes
✅ Sensibilisation au phishing
✅ EDR / détection comportementale
✅ Désactivation des macros Office
```

---

## ⚠️ Avertissement éthique

Ce projet est réalisé dans un cadre **strictement académique et éducatif**.  
Aucun code malveillant n'est distribué. L'objectif est la compréhension des mécanismes pour mieux s'en défendre.

---

## 🛠️ Technologies & outils

- Analyse statique et dynamique
- Environnement virtualisé (sandbox)
- Python — simulation des mécanismes
- Wireshark — analyse réseau
- MITRE ATT&CK Framework

---

## 👩‍💻 Auteure

**Aminata Diallo** — Master 1 Cybersécurité & Science des Données — Université Paris 8  
📧 aminatadiallopro10@gmail.com
