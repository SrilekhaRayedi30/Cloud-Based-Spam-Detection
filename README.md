# Cloud-Based-Spam-Detection


Introduction:
This project involves building a deep learning model using TensorFlow to detect SMS spam. The model is trained using a labeled dataset and is capable of accurately distinguishing between legitimate and spam messages. It is deployed on AWS infrastructure for real-time analysis and categorization.

Features:
Deep Learning Model: Developed using TensorFlow for accurate spam detection.
AWS Deployment: Hosted on Amazon EC2, with API Gateway for real-time interaction.
Scalability: Designed to handle large-scale requests efficiently.
User-Friendly API: Allows users to submit SMS messages for instant categorization.
Security: Implements data encryption and access control for secure processing.
Requirements

Software
Python 3.x
Required Libraries: NumPy, Keras, Seaborn, Matplotlib, Scikit-learn, Pandas
TensorFlow Framework
AWS services: EC2, API Gateway, Lambda, CloudWatch
Hardware
OS: Windows
Processor: i5 or above
RAM: 8 GB or more
Hard Disk: 25 GB free space

Project Structure:
Data Preprocessing: Tokenizes and processes text data to convert it into numerical formats.
Model Building: Uses TensorFlow to build and train a deep learning model.
Deployment: Hosts the model on an EC2 instance using Flask and API Gateway.
Real-Time Spam Detection: Users can interact with the API to classify messages in real-time.
Monitoring: Uses CloudWatch for performance tracking and debugging.

Setup and Installation:
Clone the repository.
Install required libraries using pip install.
Configure AWS services (EC2, Lambda, API Gateway, CloudWatch) with appropriate permissions.
Deploy the Flask application on an EC2 instance.
Set up the API Gateway to communicate with the EC2 instance.

Usage:
Submit SMS messages via the API endpoint for real-time spam detection.
Monitor the system's performance and logs using CloudWatch.

Results:
The deployed model provides accurate classifications between spam and legitimate messages. A user-friendly interface allows for efficient message submission and instant results.

Future Scope:
Integration with multiple messaging systems.
Real-time adaptive learning to handle evolving spam tactics.
Enhanced security measures to safeguard user data.
