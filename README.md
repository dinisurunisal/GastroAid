# GastroAid

GastroAid is an innovative platform designed to aid in the early
detection and classification of gastrointestinal tract diseases using
a semi-supervised learning approach. Combining cutting-edge AI
technology with an intuitive user interface, GastroAid aims to enhance
diagnostic accuracy and support medical professionals in making
informed decisions.

## Features

- **Semi-Supervised Learning Model**: Utilizes a hybrid ensemble of
ResNet50 and InceptionResNetV2 for improved accuracy and
generalizability in pathology detection.
- **Angular Frontend**: A responsive and user-friendly interface
designed to facilitate easy navigation and interaction for users of
all technical backgrounds.
- **Python Backend**: Robust and scalable backend architecture
developed with Python, ensuring efficient processing and analysis of
endoscopic image data.
- **Dataset Compatibility**: Tested with Kvasir and Kvasir-Capsule
datasets, demonstrating remarkable F1 scores of 0.82 and 0.93,
respectively, and an overall improvement in model performance.

## Getting Started

### Prerequisites

- Node.js and npm
- Python 3.8 or higher
- Required Python packages: `tensorflow`, `keras`, `flask`
- Angular CLI

### Installation

1. Clone the repository:
```
git clone https://github.com/dinisurunisal/GastroAid.git
```
2. Install frontend dependencies:
```
cd GastroAid/frontend 
npm install
```
3. Install backend dependencies:
```
cd GastroAid/backend 
pip install -r requirements.txt
```
### Running the Application

- Start the backend server:
```
python app.py
```
- Launch the frontend application:
```
ng serve
```
- Navigate to `http://localhost:4200/` to access the application.

## Usage

Upload gastrointestinal tract images through the web interface. The
platform processes the images, applying the semi-supervised learning
model for classification, and displays the diagnosis results.

## Acknowledgements

Special thanks to the advisors, contributors, and institutions that
supported the development of GastroAid, highlighting the collaborative
effort behind the project.
