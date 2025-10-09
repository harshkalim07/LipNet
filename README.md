🧠 LipNet
Deep Learning–powered Lip Reading App built with TensorFlow & Streamlit

🎙️ Interpret speech without sound.
LipNet leverages Convolutional Neural Networks (CNNs) and Sequence Modeling to read lips from short video clips and predict spoken words — providing accessibility and innovation in silent speech recognition.

🚀 Features

🧩 End-to-end Deep Learning model (TensorFlow/Keras)

🖥️ Streamlit web interface for real-time video input

🎞️ Frame-wise preprocessing and lip region extraction

🔠 Predicts text directly from visual cues (no audio required)

🧠 Optimized for small video datasets like GRID or LISA

🧰 Tech Stack
Component	Description
Python 3.10+	Core language
TensorFlow / Keras	Deep Learning model
OpenCV	Video & frame processing
Streamlit	Interactive UI
NumPy / Pandas	Data handling & utilities
⚙️ Installation

Clone the repository:

git clone https://github.com/harshkalim07/LipNet.git
cd LipNet


Create and activate your virtual environment:

conda create -n ml_env python=3.10 -y
conda activate ml_env


Install dependencies:

pip install -r requirements.txt

▶️ Run the App

To launch the Streamlit interface:

streamlit run app/streamlitapp.py


Then open the provided localhost URL in your browser.

📁 Project Structure
LipNet/
│
├── app/
│   ├── streamlitapp.py        # Streamlit frontend
│   ├── modelutil.py           # Model loading & utilities
│   └── ...
│
├── data/
│   └── s1/                    # Dataset samples
│
├── requirements.txt
├── README.md
└── ...

📈 Model Architecture

The network combines:

CNN layers for spatial feature extraction

Bi-GRU / LSTM layers for temporal sequence modeling

CTC Loss for sequence alignment

🧩 Future Enhancements

Integrate with transformers for improved context modeling

Support for multilingual lip reading

Deploy as a web service / API

💡 Inspiration

Inspired by Oxford’s LipNet architecture — reimplemented with modern TensorFlow and Streamlit for accessibility and experimentation.

🧑‍💻 Author

Harsh Kalim
🔗 GitHub
 | 💼 [LinkedIn (optional)]
