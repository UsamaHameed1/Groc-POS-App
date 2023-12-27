
# Groc-POS: 📱💳

![Groc-POS Project Logo](Project%20Images/logo/image001.png)

Groc-POS is a mobile-based point-of-sale system designed to cater to the needs of small retail stores in Pakistan. It's on a mission to help these businesses manage their inventory and streamline their checkout process using the latest technology. 🚀

# Problem Statement:

In the context of small retail stores in Pakistan, managing inventory and streamlining the checkout process remains a significant challenge. These businesses often grapple with outdated processes, manual inventory management, and a lack of efficient point-of-sale solutions. The absence of modern technology in day-to-day operations leads to inefficiencies, resource wastage, and a suboptimal shopping experience for both store owners and customers.

Additionally, the identification of grocery items during the checkout process poses a hurdle, often resulting in delays and errors. This not only impacts the speed of transactions but also contributes to an overall decrease in operational efficiency.

Recognizing these challenges, the need for an accessible, affordable, and technologically advanced point-of-sale system tailored for small retail stores in Pakistan becomes evident. Groc-POS aims to address these pain points by introducing a mobile-based solution that integrates Flutter, Dart, Firebase, Python, and TensorFlow technologies. Through this innovative approach, Groc-POS seeks to revolutionize the retail landscape, offering a comprehensive solution to enhance operational efficiency, improve inventory management, and elevate the overall retail experience for both store owners and customers.

## Project Highlights:

### 📸 Object Recognition Function:
Quick and accurate identification of grocery items using your smartphone's camera. We have developed a computer vision model specifically trained on Pakistani Prroducts. For this we have collected a custom dataset based on Pakistani Products. Currently there are 17 differnet products added in the project. 

### 💰 Mobile App Based POS System:
Groc-POS offers all the features that a Traditional POS system offers but just by using your mobile phone.

### 🔄 Resource Optimization:
Retail store owners can save time, space, and resources by using their smartphones for sales-related tasks.

Groc-POS is revolutionizing how small retail stores operate, transforming the retail industry in Pakistan. 🌐✨

## Technology Stack
- **Flutter & Dart:** 
- **Firebase:** 
- **Python:**
- **TensorFlow:** 

## Features of The App:
Groc-POS App has the following features:
1. **Checkout:** Easily process customer transactions at the point of sale.

2. **Products Management:** Efficiently manage and organize your store's product inventory.

3. **Reports:** Access insightful reports to gain valuable business insights.

4. **Ledger System:** Keep track of financial transactions and maintain an organized ledger.

5. **Shop Expense Management:** Monitor and manage your shop's expenses effectively.

6. **Receipt Management:** Generate and manage receipts for customer transactions.

7. **Price Check:** Quickly verify product prices for accurate billing.

8. **Suppliers Management:** Keep track of suppliers and manage your inventory supply chain.

9. **Payment Settings:** Configure and customize payment options according to your business needs.

10. **Shop Profile:** Maintain and update your shop's profile for accurate representation.


## Related To Product Recognition Model:

### Model Dateset:
We have collected a dataset of 17 packed grocery products, which are necessary daily household Class and Brand Name items. The dataset annotation was done using **Roboflow**

| Category      | Class                    | Brand Name                |
|---------------|--------------------------|---------------------------|
| Diary Items   | Milk                     |  Milk pack 1 Liter                         |
|               |                          | Opler’s 1.5 Liter         |
|               | Careem                   | Milk Pack Cream           |
|               | Butter                   | Blue band                 |
| Beverages     | Carbonated Drinks        |   Pepsi                        |
|               | Juices                   | Nestle Juice Apple        |
|               |                          | Tang                      |
|               | Tea                      | Lipton Tea                |
| Snacks        | Chocolate                |       Diary Milk Chocolate                     |
|               | Chips                    |  Lays Salty                          |
|               | Biscuits                 |   Rio Biscuit                         |
| Toiletries    | Surf                     |    Surf Excel                        |
|               | Shampoo                  | Head and Shoulders        |
|               | Soap                     | Lifebuoy                  |
|               | Tissue                   | Rose Patel                |
|               | Dish Soap                | Lemon Max                 |
|               | Toothpaste               | Colgate Sparkle 200g      |
| Toffee               | Toffee                         | Yums                      |
| Condiment     | Ketchup                  |   National Ketchup                                  |

![Groc-POS Project Logo](Project%20Images/Dataset/image041.png)


### Highlights of the Dataset

1. **Limited Dataset:** We have focused our dataset on 16 packed grocery items to ensure a manageable and specific collection.

2. **Images per Product:** A total of 300 images have been collected for each product, providing a comprehensive representation.

3. **Total Images:** The dataset comprises a collection of 5100 images, offering a diverse and robust set for analysis and model training.

### Model Training:
We have trained our dateset on the model Efficient-Det and Efficient-Net for the detection and classification model.

# Model Demo:

### Multiple Products Detections Using Live Camera Feed (On Device - Object Detection Model Efficient-Det):
![Groc-POS Project Logo](Project%20Images/Model/image062.png)

### Multiple Products Detection Using Static Image (On Device - Object Detection Model Efficient-Det):
![Groc-POS Project Logo](Project%20Images/Model/image066.png)

### Single Product Detection Model Integration in the App (On Device - Classification Model Efficient-Net):
![Groc-POS Project Logo](Project%20Images/Model/image067.png)


# App Demo 
![Groc-POS Project Logo](Project%20Images/Demo/Screenshot_20231227_221808.png)

# FYP Poster
![Groc-POS Project Logo](Project%20Images/Poster/GROC-POS%20FYP%20-1%20Poster%20.svg)

# For Code Access Email Me !!!!
