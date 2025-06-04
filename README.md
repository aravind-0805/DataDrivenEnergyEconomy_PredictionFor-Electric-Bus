# Data-Driven Energy Economy Prediction for Electric City Buses

This Django-based web application predicts the energy economy of electric city buses using machine learning algorithms. The project is designed to help optimize route planning and energy efficiency in public transport.

## 🚀 Features

- User & Service Provider login
- Upload datasets and train models
- Predict energy economy type using ML algorithms
- Visualize predictions using charts
- Download predicted datasets

## 🛠️ Technologies Used

- Python
- Django Framework
- MySQL (via XAMPP)
- HTML, CSS (for frontend)
- ML Algorithms: KNN, Decision Tree, Naïve Bayes

## 📁 Project Structure

- `Remote_User/`: Handles end-user interfaces
- `Service_Provider/`: Handles admin/service provider functionality
- `Template/`: Contains static and HTML templates
- `settings.py`: Configuration for database and installed apps

## ⚙️ How to Run the Project

### Prerequisites
- Python 3.x
- MySQL Server (XAMPP preferred)
- Django (recommended: `pip install -r requirements.txt`)

### Steps

1. **Clone the repository**:
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   
2. **Install dependencies:**
   pip install -r requirements.txt
   
3. **Setup MySQL database:**
   
   Open XAMPP and start MySQL
   Create a database named: data_driven_energy_economy_prediction
   Update DB username/password in settings.py if needed
   
5. **Run migrations (if needed):**
   python manage.py makemigrations
   python manage.py migrate

7. **Start the server:**
   python manage.py runserver

9. **Open in browser:**
   http://127.0.0.1:8000/

     
