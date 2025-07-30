# Neurodegenerative-Disease-prediction

# Gait Analysis of Neurological Disorders

## ALS (Amyotrophic Lateral Sclerosis)

The following graphs display **stance**, **swing**, and **stride** characteristics of a person with ALS.

- **Channel 1** (sensor value: 25 to 270) represents the **elapsed time (in seconds)** for gait cycles.
- This line increases linearly, indicating a constant gait cycle time.  
  However, at **time step ~112**, an **increase in gait cycle time** is noted.
- At this same point, there is a **sudden rise in double support interval** from **0.35s to 1.5s**.
  - This means both feet were in contact with the ground longer — a **sign of balance issues**.
- Overall, **spikes in stride and stance time intervals** suggest longer foot-on-ground durations, reflecting difficulty in walking.

---

## Control (Normal Person)

The following graphs represent a **normal individual's walking characteristics**:

- **Channel 1** shows a **steady linear increase**, indicating **constant gait cycle intervals**.
- **Channel 10 & 11** show stance percentages at around **60%**, which is ideal.
- **Channel 6 & 7** show swing percentages at **~40%**, which is also ideal.
- There are **no abrupt spikes** in stride, swing, or stance intervals — indicating **stable, consistent gait**.

---

## Huntington’s Disease

These graphs show gait characteristics of a person with **Huntington’s Disease**.

- Due to **chorea** (involuntary movements caused by damage to the **basal ganglia**), gait patterns are **irregular and unstable**.
- The **2nd graph** shows **jerky, inconsistent stance, swing, and stride intervals**, reflecting:
  - Irregular timing
  - Variation in duration of foot contact
- This instability is a hallmark of Huntington’s-related motor dysfunction.

---

## Comparative Analysis (Boxplots of 64 Subjects)

- **ALS** patients have the **highest stride intervals**.
  - Indicates slow walking with long foot-ground contact.
- **Huntington’s Disease** shows **more stride asymmetry** (difference between left and right stride intervals).
- **Mean stance percentage** (time foot is on ground during gait cycle):
  - **Highest** in ALS
  - Followed by Parkinson’s
  - Then Huntington’s
  - **Lowest** in control subjects
- **Asymmetry Summary**:
  - **Huntington’s**: Most asymmetric
  - **ALS and Parkinson’s**: Asymmetric at **specific events**
    (e.g., certain gait cycles show unequal left-right durations)

---

> ✅ Conclusion: Neurological diseases like **ALS**, **Parkinson’s**, and **Huntington’s** significantly affect gait patterns — causing increased stance time, stride asymmetry, and instability — making patients walk slowly and inconsistently.



## 📚 Citation

If you use this repository or the dataset in your work, please cite the following:

**Dataset Source:**
Hausdorff JM, Lertratanakul A, Cudkowicz ME, Peterson AL, Kaliton D, Goldberger AL.  
*Dynamic markers of altered gait rhythm in amyotrophic lateral sclerosis.*  
Journal of Applied Physiology, 88:2045–2053, 2000.

**PhysioNet Reference:**
Goldberger AL, Amaral LAN, Glass L, Hausdorff JM, Ivanov PCh, Mark RG, Mietus JE, Moody GB, Peng C-K, Stanley HE.  
*PhysioBank, PhysioToolkit, and PhysioNet: Components of a new research resource for complex physiologic signals.*  
Circulation [Online]. 2000;101(23):e215–e220.  
RRID:SCR_007345. https://doi.org/10.1161/01.CIR.101.23.e215

