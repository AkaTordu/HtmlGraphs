# HtmlGraphs

Bienvenue dans ce mini-projet qui propose **6 exemples de graphiques** réalisés avec [Chart.js](https://www.chartjs.org/).  
Chaque fichier HTML est **autonome** et contient à la fois le code HTML, le style et les données fictives. Vous pouvez rapidement les copier-coller, les modifier ou les dupliquer pour créer votre propre mini-tableau de bord.

---

## 📊 Table des graphiques

| Fichier                 | Type                  | Usage Exemple                                                      | Variables à éditer             |
|-------------------------|-----------------------|--------------------------------------------------------------------|--------------------------------|
| **chart-bar.html**      | Barres (verticales)  | Visualiser un volume (ex. ventes mensuelles, comptages, etc.)     | `barChartLabels`, `barChartData` |
| **chart-line.html**     | Courbe (Line)        | Afficher une tendance (ex. trafic, revenus mensuels, etc.)        | `lineChartLabels`, `lineChartData` |
| **chart-pie.html**      | Camembert (Pie)      | Montrer la répartition d’un ensemble en plusieurs catégories       | `pieChartLabels`, `pieChartData` |
| **chart-hbar.html**     | Barres (horizontales)| Comparer ou classer des catégories (ex. heures de formation)       | `hBarLabels`, `hBarData`       |
| **chart-radar.html**    | Radar                | Comparer plusieurs dimensions (ex. compétences, critères multiples)| `radarLabels`, `radarDatasets` |
| **chart-doughnut.html** | Doughnut (anneau)    | Montrer la répartition en camembert avec un trou au milieu         | `doughnutLabels`, `doughnutData` |

---

## 🚀 Comment les utiliser ?

1. **Cloner ou télécharger** ce repository (ou copier-coller les fichiers HTML).
2. **Ouvrir** chaque fichier `.html` dans votre navigateur (double-clic ou via un serveur local).
3. **Modifier** les données dans la section `<script>` se situant à la fin du fichier :
   - Repérer les constantes comme `barChartData`, `lineChartLabels`, etc.
   - Ajuster les **valeurs**, les **labels**, les **couleurs** (en `rgba(...)`) selon vos besoins.
   - Enregistrer vos changements, puis rafraîchir la page pour visualiser le nouveau graphique.

### Exemple d’ajustement des valeurs

Dans `chart-bar.html`, au bas du fichier :

```js
// === Données modifiables ===
const barChartLabels = ['Jan', 'Fév', 'Mar', 'Avr', 'Mai', 'Juin'];
const barChartData = [12, 18, 9, 15, 20, 25]; // Ventes fictives