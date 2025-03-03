🎵 Song & Artist Identification using PyTorch 🎶



This project identifies a song and artist from a snippet of lyrics using deep learning embeddings instead of traditional keyword-based approaches. The model is powered by PyTorch and Sentence Transformers, offering high accuracy and context-aware predictions.

🚀 Supports both VS Code & Google Colab with GPU acceleration!

🌟 Features
✅ Identifies Top 3 Closest Songs from lyrics
✅ Uses Pretrained Deep Learning Embeddings (Better than TF-IDF)
✅ PyTorch-Powered for Efficiency
✅ Handles Large Datasets with GPU Support
✅ Flexible & Easily Extendable

📂 Dataset
The dataset used is spotify_dataset.csv, which contains:

Column Name	Description
song	Name of the song
artist	Artist of the song
text	Lyrics of the song
🛠 Installation & Setup
🚀 For VS Code (Local Machine)
1️⃣ Clone the Repository

bash
Copy
Edit
git clone https://github.com/yourusername/song-identifier.git
cd song-identifier
2️⃣ Install Dependencies

bash
Copy
Edit
pip install pandas torch sentence-transformers
3️⃣ Run the Script

bash
Copy
Edit
python song_identifier.py
☁️ For Google Colab
1️⃣ Upload spotify_dataset.csv to Colab Files or Google Drive
2️⃣ Run the following in Colab:

python
Copy
Edit
!pip install pandas torch sentence-transformers
3️⃣ Copy & Run the PyTorch-based script from this repo

🧠 How It Works
1️⃣ Loads the spotify_dataset.csv (containing song names, artists, and lyrics)
2️⃣ Uses Sentence Transformer (all-MiniLM-L6-v2) to generate semantic embeddings
3️⃣ Computes cosine similarity to find the closest matching songs
4️⃣ Returns the Top 3 Most Similar Songs

🎯 Example Usage
bash
Copy
Edit
Enter a snippet of the song lyrics: 
👉 "Hello from the other side"
🔍 Identified Songs:

Rank	Song	Artist
🎵 1	Hello	Adele
🎵 2	Someone Like You	Adele
🎵 3	Rolling in the Deep	Adele
Tip: Works best with longer lyric snippets

🚀 Future Improvements
✔️ Train a custom deep learning model for enhanced accuracy
✔️ Integrate BERT/GPT-based embeddings for richer understanding
✔️ Build a web-based UI for user interaction
✔️ Connect with Spotify/Genius API for real-time results

🤝 Contributing
💡 Have ideas for improvements? Fork the repo and submit a PR!

📝 License
This project is licensed under the MIT License. Feel free to use and improve it!

🔹 Made with ❤️ using PyTorch & Sentence Transformers 🔹
