# Exoplanet Statistical Analysis

## Project goal

This project aims to explore several statistical claims on an exoplanet dataset.  
The objective is to move from simple observations to results that can be statistically defended.

---

## Dataset

The dataset comes from Kepler observations and includes information about planets and their host stars:

- planetary radius (koi_prad)
- orbital period (koi_period)
- equilibrium temperature (koi_teq)
- stellar temperature (koi_steff)
- classification (confirmed, candidate, false positive)

---

## Methods used

In this project, I used different statistical tools depending on the problem:

- permutation tests
- t-tests
- bootstrap estimation
- confidence intervals
- effect size (Cohen’s d)
- Pearson correlation method
- Spearman correction method

---

## Claims explored

### Claim 1 — Difference in size between habitable and non-habitable planets

I wanted to understand if there is a difference in size between habitable and non-habitable planets.

---

### Claim 2 — Are habitable planets smaller?

Here I focused more specifically on whether habitable planets are smaller on average.

---

### Claim 3 — Do habitable planets orbit different stars?

In this claim, I looked at the temperature of the host stars (koi_steff).

---

### Claim 4 — What is the average size of habitable planets?

Here, I used a bootstrap approach to estimate the average size of habitable planets.

---

### Claim 5 — Do confirmed planets have different temperatures?

I compared confirmed planets with non-confirmed ones using a t-test.

---

### Claim 6 — Is the difference meaningful?

Finally, I used Cohen’s d to evaluate the effect size.

---

### Claim 7 — Is there a relation between a planet's radius and its orbital period ?

This claim, was to test and confirm that there can be a positive correlation between the radius and the orbital period of a planet.

---
## Key takeaway

Statistical significance does not always mean practical importance.  
This project highlights the importance of combining statistical tests, effect size, and interpretation.

---

## Limitations

- very small number of habitable planets
- possible selection bias in the dataset
- results should be interpreted with caution

---

## Author note

This project was done as part of a personal effort to improve my understanding of statistics and data science in an astrophysics context.