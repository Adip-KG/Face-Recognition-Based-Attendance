# Face-Recognition-Based-Attendance
Attendance system which marks whether or not a student/person is present or not by recognising their face from a trained single-label image classification model.
This is then updated in a Google Sheet along with the time the person was detected at.
The model was trained using Teachable Machine by Google and run on Google Colab.

## Instructions to use
1. Open the Google Colab link [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Fle54xIao8d3hNJHYgmAgJHZaSzgYarQ#scrollTo=QMMJKYRVwpYt)
2. Connect your Google Account
3. Visit [Teachable Machine](https://teachablemachine.withgoogle.com/)
4. Select Image Project
<img width="332" alt="Screenshot 2023-02-13 at 4 39 09 PM" src="https://user-images.githubusercontent.com/87146827/218442492-50705ef7-d16c-49ed-840a-1773ca12aae0.png">
5. Select Standard Image Model
<img width="942" alt="Screenshot 2023-02-13 at 4 39 17 PM" src="https://user-images.githubusercontent.com/87146827/218442569-63930844-aacd-4f01-b4c9-cf278791e55f.png">

6. Train the Model (The colab is built for 3 objects/person(s). Edit the last code block to change the number of objects/person(s))
7. Export the model and save using Keras
<img width="805" alt="Screenshot 2023-02-13 at 4 44 12 PM" src="https://user-images.githubusercontent.com/87146827/218443330-8c82631b-5b3a-4d1b-a198-6f74aa1ae244.png">

8. Upload the trained model to the Google Colab file
9. Run each code block on Colab
