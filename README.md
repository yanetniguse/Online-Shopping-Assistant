# 🛍️ **Online Shopping Assistant - Jumia Shopping Assistant**

## 📌 **Project Overview**

The **Jumia Shopping Assistant** is an intelligent, knowledge-based expert system built to assist users in choosing products based on their preferences. By leveraging Python and the **experta** library, this assistant provides personalized product recommendations, helping users navigate the overwhelming choices in online shopping. Whether users are searching for electronics, clothing, or other products, the assistant takes into account their specific needs, making the shopping process more efficient and user-friendly.

---

## ❓ **Problem Statement**

With the vast number of products available online, shoppers often struggle to make decisions. Filters may narrow choices, but they don't always lead to the best products tailored to a user's preferences. Many e-commerce platforms don't offer deep personalization, leaving customers frustrated with the decision-making process.

### 🚨 **Challenges Addressed**:
- **Decision Fatigue**: Users often face an overload of choices, making it difficult to choose the right product.
- **Lack of Personalized Recommendations**: Existing filters don't fully understand and cater to individual user preferences.
- **Time-Consuming**: Without a personalized assistant, users waste time browsing multiple options and categories.

---

## 🛠️ **Solution**

The **Jumia Shopping Assistant** offers an intelligent system that simplifies online shopping. It asks users for their preferences such as product category, price range, and desired features, then recommends products that match those criteria. This solution reduces browsing time, boosts confidence in choices, and enhances the overall user experience.

### 🌟 **Core Features**:
- **Personalized Product Recommendations**: The assistant recommends products such as smartphones, jackets, and laptops based on the user’s preferences.
- **Interactive Command-Line Interface**: Users input their preferences, and the system uses those inputs to recommend matching products.
- **Scalability**: Easily add new products, categories, and features to expand the assistant’s capabilities.
- **User Feedback Loop**: The assistant can request additional preferences if no input is provided, ensuring every interaction results in a recommendation.

---
## Screenshots 📸

Here are some screenshots showcasing the key features of the **Online-Shopping-Assistant** app:

### 1. 🏠
![image](https://github.com/user-attachments/assets/9cf8ef3a-9e19-4a48-980b-875bf0468d4f)
![image](https://github.com/user-attachments/assets/ddd0b10b-351a-4f06-91ec-e2a2fb6442b7)
![image](https://github.com/user-attachments/assets/d9ba67db-673c-421b-bb8c-2c79f1d04b6e)
![image](https://github.com/user-attachments/assets/47c1e2a9-b5a2-49ad-a7ef-c42aaca1db97)

## 🤖 **How It Works**

Built using **Python** and the **experta** library, this assistant employs a rule-based system to process facts about the user's preferences. Each user input is treated as a fact, which is matched against a series of rules to determine the best product recommendations.

### 🔑 **System Components**:
1. **User Inputs**: The system prompts users to enter their preferences (e.g., product category, price range, features).
2. **Fact Declaration**: The assistant processes the user input as facts in the system, categorizing their preferences.
3. **Rule Evaluation**: The assistant evaluates the declared facts against predefined rules to identify suitable products.
4. **Product Recommendation**: Based on the rule evaluation, the assistant outputs a product recommendation.

### 💬 **Example Interaction**:
```bash
Enter your shopping preferences (e.g., category, price range, feature). Type 'done' when finished.
Preference: electronics
Preference: medium
Preference: battery_life
Preference: done
Recommendation: Based on your preferences for a medium-priced electronic with long battery life, we recommend a smartphone.
```

---

## 🚀 **Future Improvements**

While the assistant is functional and helpful, there’s plenty of room for enhancement to make the system even smarter and more user-friendly:

1. **Broader Product Catalog**: Introduce a wider variety of product categories, such as home appliances, beauty products, and more.
2. **User Profiles**: Allow the system to store user preferences across sessions to offer more personalized recommendations.
3. **Machine Learning Integration**: Replace or supplement rule-based recommendations with machine learning algorithms to continuously improve based on past behavior.
4. **Real-Time Integration**: Connect with live data from e-commerce platforms to provide up-to-date prices, availability, and reviews.
5. **Natural Language Processing (NLP)**: Allow users to interact with the assistant using natural language, making it easier for non-technical users to interact with the system.
6. **Mobile Application**: Create a mobile version of the assistant to expand accessibility and reach.

---

## 📝 **Installation**

To run the Jumia Shopping Assistant locally, follow the steps below:

### 🔧 **Prerequisites**:
- Python 3.7 or higher.
- The **`experta`** library.

### **Steps to Install**:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yanetniguse/Online-Shopping-Assistant.git
   cd Online-Shopping-Assistant
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter notebook**:
   ```bash
   jupyter notebook
   ```

4. **Execute the `JumiaShoppingAssistant.ipynb` notebook** to start interacting with the assistant.

---

## 📂 **Files Overview**

- **`JumiaShoppingAssistant.ipynb`**: This Jupyter notebook contains the main implementation of the shopping assistant. It processes user inputs and generates product recommendations.
- **`requirements.txt`**: A text file listing the dependencies needed to run the project, including `experta`.

---

## 🤝 **Contributing**

Contributions are welcome! If you'd like to contribute to improving this project, feel free to fork the repository and create a pull request. Here’s how to contribute:

1. **Fork the repository**.
2. **Create a new branch** for your feature or bugfix.
3. **Commit your changes** and push the branch.
4. **Submit a pull request** with a clear description of the changes made.

---

## 📄 **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

## 📬 **Contact**

For any questions, feedback, or suggestions, feel free to contact me:

- **Email**: [yanetesfay@gmail.com](mailto:yanetesfay@gmail.com)
- **LinkedIn**: [Yanet Niguse Tesfay](https://www.linkedin.com/in/yanet-niguse-tesfay-6b85552b7/)

---

## 👨‍🏫 **Instructor**

This project was created under the guidance of **Austin Odera**, whose mentorship and support have been crucial in bringing this idea to life.
