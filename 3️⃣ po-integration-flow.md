# 📦 Scenario: PO Integration Flow

## 📌 Business Requirement
Automatically create PO in S4 when PR is approved in Ariba.

---

## 🌍 Scenario
User creates PR → Approved → PO generated → Sent to S4.

---

## 🔁 Flow
1. PR approved in Ariba  
2. PO created  
3. Sent to CIG  
4. Transformed  
5. Posted in S4  

---

## ⚙️ System Behavior
- PO visible in backend  
- Supplier notified  

---

## ⚠️ Challenges
- PO not created  
- Mapping errors  
- Missing data  

---

## ✅ Solution
- Validate PR data  
- Check CIG logs  
- Verify mapping  

---

## 🎯 Learning
PO integration is most critical flow in procurement.
