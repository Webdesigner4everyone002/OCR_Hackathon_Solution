🧾 Medical Report OCR Parser 🧠
This project extracts structured JSON data from scanned medical reports using Tesseract OCR and Ollama LLMs (like Gemma or LLaMA).
Ideal for automating data entry from printed lab reports.

🚀 Features
🖼️ OCR with Tesseract

📄 Medical text parsing using local LLMs via Ollama

🧠 Tested with models like gemma:2b, llama3.2:3b, and mistral

🧾 Outputs:

Clean text

Structured JSON

Debug logs

🔧 Setup
1. Clone this repo
bash
Copy
Edit
git clone https://github.com/Webdesigner4everyone002/ocr-hackathon
cd ocr-hackathon
2. Install dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Install & Configure Tesseract
Windows: Download Tesseract

Add path to tesseract.exe in your system PATH

4. Install Ollama and Pull Model
bash
Copy
Edit
ollama run llama3.2:3b
# or try gemma:2b or mistral
▶️ Run the App
bash
Copy
Edit
python main.py --input "input_images/input.jpeg"
📁 Output
./output/text/ – Raw extracted text

./output/json/ – Final structured JSON
