📚 Book Recommender System

A Streamlit-based intelligent book recommendation system built using Collaborative Filtering.
This application suggests books based on user preferences and also showcases the Top 50 popular books.

🚀 Features
📖 Top 50 Popular Books
Displays trending books with title, author, and cover image.
🤝 Collaborative Filtering Recommendation
Suggests similar books based on user selection.
📊 Interactive UI
Clean and responsive interface using Streamlit.
🗂 Dataset Visualization
View books, users, and ratings datasets directly in the app.
🧠 How It Works

This system uses:

Collaborative Filtering
Similarity Matrix (Cosine Similarity)
Preprocessed datasets stored using Pickle

When a user selects a book:

The system finds its index.
Computes similarity scores.
Recommends top 5 similar books.
🛠 Tech Stack
Frontend: Streamlit
Backend: Python
Libraries:
Pandas
NumPy
Pickle
📂 Project Structure
├── app.py
├── popular.pkl
├── books.pkl
├── pt.pkl
├── similarity_scores.pkl
├── Data/
│   ├── Books.csv
│   ├── Users.csv
│   ├── Ratings.csv
⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/your-username/book-recommender-system.git
cd book-recommender-system
2️⃣ Install dependencies
pip install -r requirements.txt

(If requirements.txt not available)

pip install streamlit pandas numpy
3️⃣ Run the application
streamlit run app.py
🖥️ Application Preview
Sidebar:
Top 50 Books
Book Recommendation Dropdown
Dataset Viewer
Main Panel:
Book Covers
Recommendations
Dataset Tables
📊 Dataset

This project uses:

Books dataset
Users dataset
Ratings dataset

These are used to build the recommendation engine.

📌 Key Function
def recommend(book_name):
Takes a book name as input
Returns top 5 similar books
🎯 Future Improvements
🔍 Add search-based recommendations
🌐 Deploy on cloud (Streamlit Cloud / AWS)
🤖 Integrate AI-based NLP recommendations
👤 Add user login & personalization
👨‍💻 Author

Karthikeyan R

📧 karthikeyan9108354@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/karthikeyan1509/
