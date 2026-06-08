# Product Teardown: M-TIBA Health Wallet

**Analyst:** Karani Njoroge
**Date:** June 2026
**Category:** HealthTech / Fintech
**Platform:** USSD + Mobile App

---

## 1. Product Overview

M-TIBA is a mobile health financing platform built on Safaricom's infrastructure, allowing Kenyans to save money specifically for medical expenses and access a network of vetted healthcare providers. Launched in 2016 through a partnership between Safaricom, CarePay, and PharmAccess, it operates as a health wallet — funds deposited can only be spent on healthcare, creating a dedicated savings and payment layer for health.

---

## 2. Target User

**Primary User:** Low-income Kenyan household (individual or family unit)
- Earns irregular income (informal sector)
- Cannot afford private insurance premiums
- Visits public or low-cost private facilities
- Has M-Pesa but limited smartphone access
- Faces healthcare costs as a primary financial shock risk

**Secondary User:** Healthcare providers in the M-TIBA network
- Small private clinics, pharmacies, NHIF-accredited facilities
- Need reliable payment infrastructure and patient volume

---

## 3. Core User Problem

Low-income Kenyans face catastrophic health expenditure risk because they have no mechanism to save specifically for health before illness strikes, and no reliable payment method that both protects savings and is accepted by providers.

---

## 4. User Journey

| Stage | User Action | Product Response | Friction Points |
|---|---|---|---|
| Awareness | Hears about M-TIBA from community health worker or friend | — | Low awareness outside Nairobi in early years |
| Onboarding | Dials USSD code, registers with national ID | Account created, linked to M-Pesa | Multi-step USSD flow is long for first-time users |
| Saving | Transfers money from M-Pesa to M-TIBA wallet monthly | Funds ringfenced for health use only | No reminder system for irregular savers |
| Care Seeking | Visits M-TIBA facility when sick | Shows USSD code at facility for payment | Provider network limited outside Nairobi |
| Payment | Facility charges to M-TIBA wallet | Instant deduction, SMS confirmation | Provider claims process is slow (backend friction) |
| Retention | Continues saving if experience was positive | — | No engagement between health episodes |

---

## 5. Strengths

**USSD-first design:** By building on USSD, M-TIBA reaches users without smartphones or data. This is the right decision for the target demographic and reflects genuine user understanding.

**Behavioral ringfencing:** Money in M-TIBA cannot be spent on anything other than health. This behavioral constraint is the product's most valuable feature — it protects health savings from competing needs in a way a general savings account cannot.

**Trusted infrastructure:** Building on M-Pesa means users trust the underlying payment rail. M-TIBA inherits Safaricom's credibility.

---

## 6. Weaknesses

**No engagement between health episodes:** M-TIBA has no reason for users to open it unless they are sick. This creates low retention and high disengagement — users forget they have an account.

**Provider network gaps:** Outside Nairobi, the network of M-TIBA-accepting facilities is thin. A user who saves faithfully and then cannot use the wallet locally has had their trust broken.

**No proactive saving prompts:** The product is entirely pull — users must remember to save. There is no nudge, reminder, or behavioral mechanism to encourage regular contributions.

---

## 7. Opportunities

| Opportunity | Addresses | Priority |
|---|---|---|
| Monthly saving reminders via SMS | No engagement between episodes | High |
| Family wallet (household pooling) | Individual accounts miss household unit | High |
| Preventive care incentives (save and get a free health check) | Reactive-only engagement | Medium |
| Expand provider network to Level 3 facilities | Geographic gaps | High |

---

## 8. KPIs I Would Track as PM

**North Star:** Active health wallets (deposited at least once in last 90 days)

**Supporting:**
- Monthly active savers (deposited in current month)
- Average wallet balance at time of first use
- Provider network utilization rate by county
- User churn rate (account dormancy > 6 months)

---

## 9. PM Lessons for My Own Work

M-TIBA demonstrates that choosing the right delivery mechanism (USSD over app) is a more important product decision than any individual feature. The product's reach depends entirely on that infrastructure choice. For any product targeting low-income or rural African users, USSD and SMS are not fallbacks — they are primary channels.

The engagement gap between health episodes is a lesson I will apply to my own hospital queue management work: health products need reasons to exist between crises, not just during them.
