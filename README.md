# Neurodegenerative-Disease-prediction

## Diseases and Gait-Based Diagnosis

| **Disease**              | **Description**                                                                 |
|--------------------------|----------------------------------------------------------------------------------|
| **Parkinson’s Disease**  | A progressive neurodegenerative disorder affecting movement due to dopamine loss. |
| **Huntington’s Disease** | A genetic disorder causing uncontrolled movements, cognitive decline, and mood issues. |
| **ALS** (Amyotrophic Lateral Sclerosis) | A motor neuron disease causing muscle weakness and paralysis, sparing cognition. |

# Gait Analysis of Neurological Disorders

## ALS (Amyotrophic Lateral Sclerosis)
<img width="940" height="524" alt="image" src="https://github.com/user-attachments/assets/7744296e-67fb-41f0-a322-a6a7c6053fc3" />
<img width="940" height="530" alt="image" src="https://github.com/user-attachments/assets/a22f4636-cd4a-4bae-9f0d-0cc41a991b43" />

The following graphs display **stance**, **swing**, and **stride** characteristics of a person with ALS.

- **Channel 1** (sensor value: 25 to 270) represents the **elapsed time (in seconds)** for gait cycles.
- This line increases linearly, indicating a constant gait cycle time.  
  However, at **time step ~112**, an **increase in gait cycle time** is noted.
- At this same point, there is a **sudden rise in double support interval** from **0.35s to 1.5s**.
  - This means both feet were in contact with the ground longer — a **sign of balance issues**.
- Overall, **spikes in stride and stance time intervals** suggest longer foot-on-ground durations, reflecting difficulty in walking.

---

## Control (Normal Person)
<img width="940" height="504" alt="image" src="https://github.com/user-attachments/assets/e66d8c97-37d1-41af-a3df-08fe94f390c1" />

<img width="940" height="514" alt="image" src="https://github.com/user-attachments/assets/f6dcbd61-9356-4da8-a1bf-21d8dd6864d3" />


The following graphs represent a **normal individual's walking characteristics**:

- **Channel 1** shows a **steady linear increase**, indicating **constant gait cycle intervals**.
- **Channel 10 & 11** show stance percentages at around **60%**, which is ideal.
- **Channel 6 & 7** show swing percentages at **~40%**, which is also ideal.
- There are **no abrupt spikes** in stride, swing, or stance intervals — indicating **stable, consistent gait**.

---

## Huntington’s Disease
<img width="940" height="508" alt="image" src="https://github.com/user-attachments/assets/1a5673ba-ecbc-4294-a96a-260e44c1efba" />
<img width="940" height="521" alt="image" src="https://github.com/user-attachments/assets/819d81ab-1c50-465e-940c-b6d3e219c171" />

These graphs show gait characteristics of a person with **Huntington’s Disease**.


- Due to **chorea** (involuntary movements caused by damage to the **basal ganglia**), gait patterns are **irregular and unstable**.
- The **2nd graph** shows **jerky, inconsistent stance, swing, and stride intervals**, reflecting:
  - Irregular timing
  - Variation in duration of foot contact
- This instability is a hallmark of Huntington’s-related motor dysfunction.

---

## Comparative Analysis (Boxplots of 64 Subjects)
<img width="940" height="440" alt="image" src="https://github.com/user-attachments/assets/02cd3845-f70b-4a60-9a11-e25865db6a5a" />

- **ALS** patients have the **highest stride intervals**.
  - Indicates slow walking with long foot-ground contact.
<img width="940" height="734" alt="image" src="https://github.com/user-attachments/assets/bb554488-81c0-4f5f-a860-e0e22f334b52" />

- **Huntington’s Disease** shows **more stride asymmetry** (difference between left and right stride intervals).
<img width="1107" height="361" alt="image" src="https://github.com/user-attachments/assets/a111edf6-0f5a-4b7d-816d-0e6a3b7be879" />

- **Mean stance percentage** (time foot is on ground during gait cycle):
  - **Highest** in ALS
  - Followed by Parkinson’s
  - Then Huntington’s
  - **Lowest** in control subjects
<img width="1046" height="345" alt="image" src="https://github.com/user-attachments/assets/fd7f32b9-2b9f-4d8e-871a-efe68fbb2fde" />

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

