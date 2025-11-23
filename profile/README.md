# 🌟 LifeStyle - Plateforme Multi-Solutions Connectées

> Améliorer votre quotidien grâce à des solutions connectées intelligentes et accessibles.
---

> ![WARNING]
> **on ne travaille pas sur `main` on ne push pas sur `develop` non plus, on crée une branche feature, on fait uniquement la feature puis une pull request, et on attend la review.**

---

## 📖 Vision

**LifeStyle** est une plateforme Cloud qui permet aux utilisateurs de souscrire à différentes solutions connectées pour améliorer leur style de vie au quotidien.

Chaque solution propose un service spécifique avec son propre device/système embarqué, le tout géré via un compte unique et des abonnements flexibles.

### 🎯 Solutions actuelles

#### 🍽️ SmartMeal (2025)
**Le frigo connecté intelligent**
- Gestion automatique de l'inventaire alimentaire
- Recommandations de recettes personnalisées par IA
- Alertes de péremption intelligentes
- Liste de courses optimisée
- **Device** : Raspberry Pi 4

#### 🔮 Prochaines solutions
- ...

---

## 🏗️ Architecture Globale

```
┌────────────────────────────────────────────────────────────┐
│                LIFESTYLE (Cloud Platform)                  │
│                                                            │
│  ┌─────────────────┐         ┌──────────────────┐          │
│  │ lifestyle-front │ ◄─────► │  lifestyle-back  │          │
│  │   (Angular)     │         │  (Spring Boot)   │          │
│  │                 │         │                  │          │
│  │ • Compte user   │         │ • API REST       │          │
│  │ • Abonnements   │         │ • Auth JWT       │          │
│  │ • Devices       │         │ • Multi-solutions│          │
│  └─────────────────┘         └────────┬─────────┘          │
│                                        │                   │
│                                   PostgreSQL               │
└──────────────────────────────┬─────────────────────────────┘
                               │
                API REST (Auth & Config)
                               │
┌──────────────────────────────▼──────────────────────────────┐
│                        Chaque solution                      │
│                      HardWare, SoftWare                     │
│                        pi, web, app, ...                    │
└─────────────────────────────────────────────────────────────┘
```

---

## 🤝 Contribution

* [Formidabledu59](https://github.com/Formidabledu59)
* [Zagoki](https://github.com/Zagoki)
* [DxrkSquks](https://github.com/BleuzeHugo)

---

## 📞 Contact

- **GitHub Org** : [Open-Innovation](https://github.com/Open-Inno)
- **Email** : lifestyle.app.fr@gmail.com
