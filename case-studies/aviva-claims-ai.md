# 🧠 AI Case Study Analysis: Aviva Claims Transformation by McKinsey Breakdown

🔗 **Source Article:**  
[Aviva: Rewiring the insurance claims journey with AI — McKinsey](https://www.mckinsey.com/capabilities/tech-and-ai/how-we-help-clients/rewired-in-action/aviva-rewiring-the-insurance-claims-journey-with-ai)

---

## 1. Why I Read This Case

Aviva represents one of the most mature real-world deployments of AI  
in **high-stakes, decision-dense insurance operations**.

This report breaks down:

- **What McKinsey stated (facts)**
- **What the root problem & solution structure was**
- **How the AI system likely worked behind the scenes (my deconstruction)**
- **Why this is a template for future enterprise AI transformations**

---

## 2. Problem — *as stated in the article*

Insurance claims were slow, costly, inconsistent and frustrating:

| Challenge | Description |
|---|---|
| Cost pressure | Claims cost rising faster than inflation (~11% over CPI) |
| Slow settlement | Liability assessment took weeks for complex cases |
| High customer complaints | Inconsistent routing + slow decisions |
| Manual decision bottlenecks | Humans processing every step made scaling impossible |

---

## 3. Solution — *as stated in the article*

McKinsey describes Aviva implementing:

- **~80 AI models across the claims lifecycle**
- A **digital + human hybrid operating model**
- **40,000+ training hours for staff** to adopt AI
- Complete operating model redesign — *not just automation*

Aviva did not add AI to the process.  
It **rebuilt the process around AI.**

---

## 4. Impact & Measured Outcomes (from article)

| KPI | Improvement |
|---|---|
| Liability decision cycle | **–23 days** faster |
| Routing accuracy | **+30%** |
| Complaints | **–65%** |
| Customer NPS | **~7× increase** |
| Employee engagement | **2× increase** |
| Recycled repair parts use | **3× increased** |
| Financial savings | **>£60M in motor claims (2024)** |

---

# 🔎 DECONSTRUCTION (my analysis)

---

## 5. The Root Cause (not just stated — reasoned)

The underlying problem was **decision fragmentation**, not delay itself.  
Insurance claims involve ~30–50 micro-decisions, such as:

> Coverage?  
> Damage level?  
> Fraud risk?  
> Repair or replace?  
> Vendor match?  
> Payout amount?

Humans cannot scale decision density.  
AI can — if decisions are modularized.

---

## 6. Claims Workflow — reconstructed as probable AI pipeline

```text
Claim Filed → FNOL Data → Policy Validation Model  
              ↓
 Photos Uploaded → Damage Severity CNN  
              ↓
 Liability Classifier → (If anomaly) → Fraud Detection  
              ↓
 Repair vs Replace Model  
              ↓
 Vendor Routing Optimizer  
              ↓
 Human-in-loop for edge cases  
              ↓
 Settlement → Feedback Loop → Model retraining
