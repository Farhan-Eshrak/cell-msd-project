# Cell MSD Calculation and Prediction Project

## Relevant Paper/s
1. *The Dynamics and Turnover of Tau Aggregates in Cultured Cells - Insights into Therapies for Taupathies*
## Targeted Cells
1. **Human embryonic kidney-derived QBI-293 cells (QBiogene)**
[HEK 293 cells](https://en.wikipedia.org/wiki/HEK_293_cells)

## **Tools Used**
Python, NumPy, Pandas, Matplotlib

## **Formula/s Used**
$$
MSD(\tau) = \left\langle |\mathbf{r}(t+\tau)-\mathbf{r}(t)|^2 \right\rangle
$$

Where:

$MSD(\tau)$ = Mean Squared Displacement

$\mathbf{r}(t)$ = Particle position at time $t$

$\mathbf{r}(t+\tau)$ = Particle position at time $t+\tau$

$\tau$ = Time lag

$\langle \cdot \rangle$ = Ensemble or time average