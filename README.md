# CashGuard

CashGuard is a cross-platform mobile application built with Flutter, designed to detect whether an Indian currency note is real or fake. The app leverages machine learning algorithms like Optical Character Recognition (OCR) and Structural Similarity Index (SSIM) for image comparison. The backend is powered by Flask to handle image processing and data management.

## Features

- **Cross-Platform Compatibility**: Developed using Flutter, ensuring a smooth experience on both iOS and Android devices.
- **ML-Based Detection**: Utilizes machine learning algorithms such as OCR and SSIM to verify the authenticity of currency notes.
- **Secure and Fast**: Provides instant results with high accuracy using the latest AI models.
- **Flask Backend Integration**: A robust Flask server supports the app's backend for handling image processing and other operations.

## Screenshots

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/894bbba3-d756-47a0-a40e-6f3da24a557f" width="250" /></td>
    <td><img src="https://github.com/user-attachments/assets/cd29a904-8330-4af9-90c9-c5a079b6e0d5" width="250" /></td>
    <td><img src="https://github.com/user-attachments/assets/b18c9f0c-d8b5-4615-9c63-978e11762f9e" width="250" /></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/a4827376-d979-4f93-9a86-17afe787c025" width="250" /></td>
    <td><img src="https://github.com/user-attachments/assets/dd2122c6-b96f-40cd-ae60-31d8f4713469" width="250" /></td>
    <td><img src="https://github.com/user-attachments/assets/6e17ce12-e2fc-40e0-96e7-b9ac54a0a56d" width="250" /></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/3a712499-f24b-4c8d-9b38-2e14d75b1cc7" width="250" /></td>
    <td><img src="https://github.com/user-attachments/assets/2a5e7489-5bff-4545-9435-86cd6ffcccea" width="250" /></td>
    <td></td>
  </tr>
</table>

## How It Works

1. **Image Input**: The user uploads or captures an image of the currency note.
2. **Backend Processing**: The image is sent to the Flask backend, where it is analyzed using OCR and SSIM.
3. **Result Display**: The app displays the analysis result, indicating whether the currency note is real or fake.

## Technologies Used

- **Flutter**: For cross-platform mobile app development.
- **Flask**: As the backend server for handling image processing.
- **Machine Learning**: Implemented OCR and SSIM algorithms to check currency authenticity.
- **Python**: Used for writing backend scripts and algorithms.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/yourrepository.git
