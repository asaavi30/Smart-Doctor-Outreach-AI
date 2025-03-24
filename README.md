# Smart Doctor Outreach AI

## Overview & Objective
Doctors receive numerous survey invitations, but many go unanswered. This AI/ML-powered web app ensures invitations reach the right doctors at the right time. By analyzing login/logout times and past survey participation, it predicts which doctors are most likely to respond at a given time. Simply enter a preferred time, and the app generates a downloadable list of targeted NPIs, optimizing outreach efforts.

## Features
- **AI/ML-based Prediction:** Uses past engagement patterns to determine the best doctors to target at a given time.
- **Interactive UI:** Users input a time, and the system processes the data to generate results.
- **Downloadable Reports:** Exports the predicted list of doctors as CSV/Excel for easy use.
- **Dark Mode & Light Mode Support:** Offers a toggle for switching between dark and light themes for better readability and user comfort.
- **Efficient Email Targeting:** Reduces unnecessary outreach and improves response rates.

## Tech Stack
- **Frontend:** Streamlit (for interactive UI)
- **Backend:** Python (for data processing & ML model)
- **Machine Learning:** Scikit-learn, Pandas, NumPy (for data analysis & prediction)
- **Data Storage:** CSV/Excel files (for storing doctor survey data)

## Installation & Setup
1. **Clone the repository:**  
   ```bash
   git clone https://github.com/asaavi30/smart-doctor-ai-outreach.git
   cd smart-doctor-ai-outreach
   ```

2. **Run the web app:**  
   ```bash
   streamlit run app.py
   ```

## Usage
1. Open the web app in your browser.
2. Enter the preferred time for survey outreach.
3. Click the submit button.
4. Download the list of predicted doctors in CSV/Excel format.

## Dataset
The dataset contains:
- **NPI (National Provider Identifier)** - Unique ID for each doctor.
- **Specialty, Region** - Doctor's medical field and location.
- **Login & Logout Time** - Past activity data.
- **Time Spent, Count of Attempts** - Previous engagement details.

## Future Enhancements
- **Integration with Email APIs** for automated campaign management.
- **Enhanced ML Model** with more sophisticated behavioral analysis.
- **Dashboard & Visualizations** for better insights.

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

