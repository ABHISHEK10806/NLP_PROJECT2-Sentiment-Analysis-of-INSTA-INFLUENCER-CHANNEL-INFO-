# 📌 NLP Mini Project 2: Instagram Channel Sentiment Analysis-

🎯 Project Overview

Is project ka objective hai Instagram influencer ke channel name se sentiment predict karna
yaani channel Positive hai ya Negative.

Ye ek basic NLP + Deep Learning (ANN) based project hai.

📂 Dataset
- Dataset: Top Instagram Influencers Data
- Column used:
- channel_info → Instagram username / channel name

⚙️ Methodology

1. Sentiment Creation (Rule-based)
 - Kuch positive keywords define kiye jaise:
 - fitness, love, music, football, model, star
 - Agar channel name me positive word mila → Positive (1)
 - Nahi mila → Negative (0)

2. Text Tokenization
 - Channel name ko lowercase karke words me split kiya

3. Manual Vocabulary
 - Har unique word ko ek index assign kiya
 - Unknown words ko 0 index diya

4. Encoding & Padding
 - Text ko fixed length (20) tak pad kiya
 - PyTorch tensor me convert kiya

🧠 Model Architecture
 - Embedding Layer
 - Simple ANN (Fully Connected Layer)
 - Sigmoid Activation for binary classification

🏋️ Model Training
 - Loss Function: Binary Cross Entropy Loss
 - Optimizer: Adam
 - Epochs: 3
📉 Loss gradually decrease hua, jo learning show karta hai.

🧪 Sample Prediction
 - Input:
 official fitness model
 - Output:
❌ Negative 😞
(Dataset aur sentiment rules simple hone ki wajah se)

🚀 Conclusion
 - Ye project NLP preprocessing + ANN workflow ko clearly demonstrate karta hai
 - Simple rule-based sentiment creation ka use kiya gaya hai
 - Project beginners ke liye Deep Learning with Text samajhne ke liye best hai

🧠 Skills Used
 - Python
 - NLP Basics
 - PyTorch
 - Artificial Neural Network (ANN)
 - Tokenization & Embedding
