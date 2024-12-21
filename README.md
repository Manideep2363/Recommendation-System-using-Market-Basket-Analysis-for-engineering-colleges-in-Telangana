# College Recommendation System Using Market Basket Analysis

This project aims to assist students in selecting engineering colleges in Telangana by analyzing preferences for location, facilities, and ranking. Using **Market Basket Analysis** with the Apriori algorithm, the system identifies patterns and suggests colleges that match user-defined criteria. The GUI, built using **Tkinter**, provides an intuitive interface for users to input preferences and view recommendations.

---

## **About the Project**
The system leverages Market Basket Analysis to recommend colleges based on patterns in historical data. It identifies associations among college attributes, such as location, facilities, and rankings, to make accurate suggestions.  

### **How the System Works**  
1. **Input**:  
   Users specify preferences for facilities, location, and ranking range through the GUI.  

2. **Processing**:  
   - Data is preprocessed and encoded using **One-Hot Encoding**.  
   - **Apriori algorithm** generates frequent itemsets and association rules.  
   - Recommendations are filtered based on user preferences and rules.  

3. **Output**:  
   The system displays a list of colleges matching the criteria, along with details like location and ranking.

---

## **Features**
- **Customizable Preferences**:  
  - Select college facilities (e.g., Libraries, Sports).  
  - Choose location from available districts.  
  - Specify ranking range (e.g., `50-100`).  
- **Dynamic Recommendations**:  
  Provides a tailored list of colleges matching user inputs.  
- **Interactive GUI**:  
  A user-friendly interface built with **Tkinter** for seamless input and output.  
- **Real-Time Validation**:  
  Ensures valid input for ranking range.  
- **Progress Indication**:  
  Displays a loading indicator during recommendation generation.  

---

## **Demo**
 ![output](https://github.com/user-attachments/assets/7b128a74-a26a-402d-ba6e-ae139d90e71d)

The interface to select preferences for facilities, location, and ranking range.  


---

## **Getting Started**
### **Clone the Repository**  
```bash
git clone https://github.com/yourusername/college-recommendation-system.git
cd college-recommendation-system
