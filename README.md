# 🖼️ Steganography Project - Image-Based Message Hiding  

## 📌 Project Overview  
This project demonstrates **image-based steganography**, where a secret text message is embedded into an image and retrieved using a **passcode**.  

## 🚀 Features  
✅ **Message Hiding in Image Pixels**  
✅ **Passcode-Protected Message Retrieval**  
✅ **Minimal Image Alterations**  

## 🔧 Technologies Used  
- **Python**  
- **OpenCV (cv2)**  

## 🛠️ How It Works  
### 🔒 **Encoding (Hiding the Message)**  
1️⃣ Load an image using OpenCV  
2️⃣ Convert text to ASCII values  
3️⃣ Embed ASCII values into **RGB pixel values**  
4️⃣ Save the modified image  

### 🔓 **Decoding (Retrieving the Message)**  
1️⃣ Load the encrypted image  
2️⃣ Extract ASCII values from pixels  
3️⃣ Convert ASCII values back to text  
4️⃣ Verify the **passcode** before displaying the message  

## 📸 Screenshots  
| Original Image | Encrypted Image |  
|---------------|----------------|  
| ![Original](C:\Users\ramac\OneDrive\Documents\Cybersecurity_Project\images\mypicture.jpg) | ![Encrypted](C:\Users\ramac\OneDrive\Documents\Cybersecurity_Project\images\encryptedImage.jpg) |  


🚀 Future Enhancements
✅ Advanced Encoding Techniques
✅ Support for Large Messages
✅ GUI Integration

📬 Contact
🌐 Mail Id : barkavikannan951@gmail.com

