# Patou Logger

Un mini projet **pédagogique** pour apprendre à créer et publier :

- 📦 un package **npm (TypeScript)**
- 📦 un package **NuGet (C#)**
  dans **un seul repo GitHub**

Le package ne fait qu’une chose :

---

## 📁 Structure du repository

```bash
patou-logger/
├─ js/
│ └─ patou-logger-js/   # Package npm (TypeScript)
│
└─ dotnet/
  └─ Patou.Logger/      # Package NuGet (C#)

```

## Package npm (TypeScript)

### Installation

```bash
npm install patou-logger
```

### Utilisation

```bash
import { logPatou } from "patou-logger";

logPatou();
// 🐶 PATOU !!!
```

### Build local

```bash
npm run build
```

## Package NuGet (C#)

### Installation

```bash
dotnet add package Patou.Logger
```

### Utilisation

```bash
using Patou.Logger;

PatouLogger.Log();
//  PATOU !!!
```

## 🎯 Objectif du projet

- ✅ C’est un exercice complet et réaliste
- ❌ Ce n’est pas une vraie librairie
- Comprendre comment :
  - créer un package
  - le builder
  - le publier
  - le fonctionnement npm / NuGet
  - tester un mono-repo multi-langages

## Publication

npm : https://www.npmjs.com/

NuGet : https://www.nuget.org/

## Licence

MIT

Ensuite, tu peux faire :

```bash
git add README.md
git commit -m "add README"
```
