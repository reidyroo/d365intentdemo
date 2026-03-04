# D365 Customer Service Intent Agent Demo  
Sample data, configuration guidance, and learning resources for building and understanding the **Dynamics 365 Customer Service Intent Agent**.

This repository is designed to support hands‑on demos, workshops, and community presentations. It provides a lightweight, ready‑to‑use set of files that help you explore how the Intent Agent works, how to configure it, and how to test intent recognition with realistic sample data.

---

## 🎯 Purpose of This Repository

- Provide **sample utterances**, **training data**, and **reference files** for demos.  
- Offer **step‑by‑step setup instructions** for configuring an Intent Agent in D365 Customer Service.  
- Help learners understand **how intent detection works**, how to tune it, and how to validate results.  
- Support **public speaking engagements**, workshops, and self‑guided learning.

---

## 📁 Repository Structure

- **/sample-data** — Example utterances, intents, and categories for import or manual configuration.  
- **/config-examples** — JSON and reference files showing typical Intent Agent settings.  
- **/scripts** — Optional helper scripts for testing or bulk‑loading sample data.  
- **README.md** — This guide.

---

## 🚀 Getting Started

### 1. Prerequisites
- A Dynamics 365 Customer Service environment with **Copilot** and **Intent** features enabled.  
- Appropriate permissions to configure **Customer Service admin settings**.  
- Basic familiarity with **topics**, **intents**, and **utterances** in D365.

---

## 🛠️ Configuring the Intent Agent (Step‑by‑Step)

### 1. Enable the Intent Agent
1. Go to **Copilot Service admin center**.  
2. Navigate to **Copilot → Intent**.  
3. Enable the Intent Agent feature for your environment.

### 2. Create or Import Intents
You can:
- Import structured data ZIP using the configuration migration tool

### 3. Train the Model
Once your intents and utterances are in place:
1. Select **Discovery Setup**.
2. Wait for the model to complete training.  
3. Review the **quality indicators** and adjust utterances if needed.

### 4. Test the Intent Agent
Use the **Test Console** in the admin center:
- Enter sample phrases from `/sample-data/test-utterances.txt`.  
- Validate that the predicted intent matches expectations.  
- Adjust utterances or add new examples to improve accuracy.

---

## 📚 Learning & Demo Tips

- Start with **3–5 simple intents** to keep the demo focused.  
- Use **ambiguous utterances** to show how the model handles edge cases.  
- Demonstrate how adding or refining utterances improves accuracy.  
- Show the **training cycle** and explain how the model evolves.  
- Use the repo’s sample data to keep demos consistent and repeatable.

---

## 🤝 Contributing

Contributions are welcome!  
If you have additional sample data, improved instructions, or demo ideas, feel free to submit a pull request.

---

## 📢 About This Project

Created to support community learning, conference talks, and hands‑on exploration of the **D365 Customer Service Intent Agent**.  
Use it freely for demos, workshops, and training sessions.
