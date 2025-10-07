Chat-Reply Recommendation System using Transformers
---------------------------------------------------

📘 Project Overview:
This project builds an offline chat-reply recommendation system using a Transformer-based model (GPT-2).
The model is trained to predict User A's response based on User B's latest message and past conversation context.

📂 Folder Structure:
[your_meetmux_email_id]/
│── ChatRec_Model.ipynb      → Jupyter Notebook containing model code
│── Report.pdf                → Project Report (Model_Report.pdf)
│── Model.joblib              → Saved (or placeholder) model file
│── ReadMe.txt                → This file

⚙️ Requirements:
- Python 3.10+
- Libraries: transformers, torch, pandas, numpy, scikit-learn, nltk, matplotlib, joblib

📊 Model Summary:
Model Used: GPT-2 (Small)
Objective: Generate context-aware replies
Training Data: Two-person chat dataset (userA_chats.csv, userB_chats.csv)
Evaluation Metrics: BLEU, ROUGE, Perplexity

🚀 Execution Steps:
1. Open 'ChatRec_Model.ipynb' in Jupyter Notebook or PyCharm.
2. Ensure the datasets are placed in the correct paths:
   /Desktop/Dataset/userA_chats.csv
   /Desktop/Dataset/userB_chats.csv
3. Run all notebook cells sequentially to preprocess, train, and generate replies.
4. Use the 'generate_reply' function to test new messages.

💾 Offline Usage:
All operations are offline using preloaded Transformer weights from Hugging Face.
The model and tokenizer are saved locally and can be reloaded for inference.

🧠 Example:
Input:  "Hey, are you coming to the party tonight?"
Output: "Yeah, I’ll be there soon! Can’t wait to see everyone."

📞 Contact:
For issues or clarifications, reach out to the MeetMux evaluation team.
