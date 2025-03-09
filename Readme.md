# 🚀 RAG Application Instructions

Welcome to the **RAG (Retrieval-Augmented Generation) Application**! This guide will help you set up and run the application on your system. Follow the steps below to get started. 🛠️

---

## 🌟 Features
- Upload documents in `.pdf`, `.txt`, or `.md` formats.
- Ask questions and get answers based on the uploaded content.

---

## 🖥️ System Requirements
- **Operating System**: Windows/Linux
- **Optional**: NVIDIA GPU (for faster processing)

---

## 🛠️ Setup Instructions

### 1️⃣ Install Conda 🐍
#### **For Windows**:
- Download the Conda installer from the official website.
- Double-click the `.exe` file and follow the on-screen instructions.
- Open the **Anaconda Prompt** after installation to verify by running:
  ```
  conda --version
  ```

#### **For Linux**:
- Download the installer:
  ```
  wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
  ```
- Run the installer:
  ```
  bash Miniconda3-latest-Linux-x86_64.sh
  ```
- Follow the prompts and restart your terminal.
- Verify installation:
  ```
  conda --version
  ```

---

### 2️⃣ Install CUDA (Optional for GPU Users) ⚡
#### **For Windows**:
- Download the NVIDIA CUDA Toolkit from the [official site](https://developer.nvidia.com/cuda-toolkit).
- Follow the installation wizard to set it up.

#### **For Linux**:
- Download and install using the terminal:
  ```
  wget https://developer.download.nvidia.com/compute/cuda/12.0.1/local_installers/cuda_12.0.1_525.85.12_linux.run
  sudo sh cuda_12.0.1_525.85.12_linux.run
  ```

---

### 3️⃣ Create a Conda Environment 🌱
1. Open your terminal or Anaconda Prompt.
2. Create a new environment:
   ```
   conda create -n rag_env python=3.9 -y
   ```
3. Activate the environment:
   ```
   conda activate rag_env
   ```

---

### 4️⃣ Open IDE 📦
Open VS Code for easy use

---

### 5️⃣ Run the Application on Windows Machine🏃‍♂️

1. Open `RAG_Notebook.ipynb` from VS code.
2. Then Select the environment we created
3. Follow the instructions in the notebook 
4. Enjoy the application

### gguf is available in hugginface - dinukpathiraja/Qwen-2.5-3B-GRPO
### Model name is - DataMavericks_Qwen_2.5_3B_GRPO.gguf
---

## 🎉 Usage Instructions

### Upload a Document 📄
- Supported formats: `.pdf`, `.txt`, `.md`
- Drag and drop your file into the upload section of the notebook.

### Ask Questions ❓
- Type your question in the provided input box.
- The application will retrieve relevant context from your document and generate an answer.

### Reminder
- If the GPU is not utilized the model runs on CPU in that case the response will take around 1.5 minutes
- So please wait

---

## 🛑 Troubleshooting

### Common Issues:
1. **Conda not recognized**: Ensure Conda is added to your system's PATH during installation.
2. **CUDA not detected**: Verify that your GPU drivers are installed and compatible with CUDA.

For further assistance, feel free to reach out! ✉️

---

# 🚀 Finetuning Qwen2.5 3B

Open a kaggle notebook and then upload Finetuning_Qwen_Notebook.ipynb and then execute the cells and download the gguf saved in kaggle working directory

Welcome to the **RAG (Retrieval-Augmented Generation) Application**! This guide will help you set up and run the application on your system. Follow the steps below to get started. 🛠️

---

Enjoy using your RAG application! 🎉✨ 


