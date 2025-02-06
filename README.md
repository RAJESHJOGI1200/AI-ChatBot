# 🍽️ Food Ordering Chatbot

This **AI-powered chatbot** enables users to **place food orders, track orders, modify their cart**, and **check store hours** using **FastAPI, Dialogflow, and MySQL**. It efficiently processes user queries and ensures smooth order management.

---

## 🚀 Features

✔️ **Place Orders** – Add food items with quantity to the cart.  
✔️ **Modify Orders** – Remove items from an ongoing order.  
✔️ **Track Orders** – Retrieve order status using order ID.  
✔️ **Store Hours Inquiry** – Users can ask about restaurant open/close hours.  
✔️ **Database Integration** – Stores and retrieves orders from MySQL.  
✔️ **Error Handling** – Handles missing items, duplicate requests, and invalid inputs.  

---

## 🛠 Tech Stack

- **Backend:** FastAPI (Python)  
- **Database:** MySQL  
- **Dialogflow:** NLP-powered intent recognition  
- **Frontend:** (Optional) Flask/React for UI integration  

---

## 📂 Project Structure
FoodChatBot/
│── main.py                 # Handles API requests and order processing
│── db_helper.py            # Database interaction functions
│── generic_helper.py       # Utility functions for formatting responses
│── requirements.txt        # Dependencies list
│── README.md               # Project documentation

---

## ⚙️ Installation
### 1️⃣ Clone the repository
git clone https://github.com/yourusername/FoodChatBot.git
cd FoodChatBot

### 2️⃣ Set up a virtual environment
python -m venv venv
source venv/bin/activate  # Mac/Linux
venv\Scripts\activate     # Windows

### 3️⃣ Install dependencies
pip install -r requirements.txt

### 4️⃣ Set up MySQL Database
1. Create a pandeyji_eatery database.
2. Import the provided schema.sql file.
3. Update db_helper.py with your MySQL credentials.

### 5️⃣ Run the FastAPI Server
uvicorn main:app --reload

## 🧪 Testing
1. Run the API using uvicorn main:app --reload
2. Test via Postman
3. Connect with Dialogflow to simulate chatbot interactions

## 🛠 Future Enhancements
🔹 Add Payment Integration
🔹 Deploy on Cloud (AWS/GCP)
🔹 Build Frontend for User Interaction using React or any other frontend frameworks

#### 🙌 Contributions Welcome! Fork the repo, improve it, and submit a pull request. 🚀
