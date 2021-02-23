+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = "Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "Software Development Engineer"
  company = "Amazon.com, Inc."
  company_url = "https://www.amazon.com/"
  location = "Austin, Texas, United States"
  date_start = "2020-07-13"
  date_end = ""
  description = """
  Work on the Business Web Services (BWS) team of Amazon Business Org
  
  * Wrote Unit tests to improve team service's code coverage and Integration tests for API to make pipeline fully continuous delivery (CD).
  * Studied, implemented and tested new features for API end to end development in Spring Framework.
  *Created Low-level design for team's current service such as how to direct them to call other APIs, how to use the data from other APIs to serve the current service functionalities and what to set up to prepare for the case where other APIs are down through interaction diagrams.
  * Used AWS Kinesis, Simple Storage Service(S3) and Redshift to store and transfer Team’s API requests from AWS CloudWatch, which provides a better practice for API’s maintenance.
  * Added AWS Key Management Service(KMS) to team's different services and published the logs to a same library, which provides a good management environment for different services. KMS was used for encrypting API's encryption log fields and configured through logs compressing, encrypting, decrypting, decompressing.
  """


[[experience]]
  title = "Machine Learning Intern"
  company = "Electronic Arts Inc.(EA)"
  company_url = "https://www.ea.com/"
  location = "Austin, Texas, United States"
  date_start = "2019-05-27"
  date_end = "2019-08-16"
  description = """
  Work on the customer experience IT team
  
  * Translated EA customer and service agent conversation audio ﬁles into text using AWS S3’s Transcribe function in Python. Designed protocols to divide the text into different channels.
  * Applied NLP model Bert from Google with GPU on AWS EC2 to do sentiment analysis using customer’s data as well as IMDB movie review data and achieved 86% accuracy in testing.
  * Built a complete website with Django, JavaScript and Vue.js to allow customer support advisers to log in and view/update the analysis results stored in MongoDB. Added Google charts to represent the data distribution in database and posts to allow system news from different users.
  * Transplanted the whole website onto AWS EC2, used Nginx to connect user from browser to Django and Bert model was applied in backend as a classiﬁer to allow machine learning engineers to upload audio/text ﬁles and see the predictions from Bert in real time. Incorporated the AWS Transcribe into the website and used Celery to make Bert run asynchronously.
  """

[[experience]]
  title = "Applied Machine Learning Research Intern"
  company = "Los Alamos National Laboratory (LANL)"
  company_url = "https://www.lanl.gov/"
  location = "Los Alamos, New Mexico, United States"
  date_start = "2018-05-28"
  date_end = "2018-08-03"
  description = """
  Machine learning solutions to revealing the hidden seismicity of Mars
  
  * Applied Fingerprinting to preprocess the Marsquake waveform data and transferred the Fingerprinting results into both Sequence and Image, two perspectives in Deep Learning.
  * Built a Convolutional Recurrent Neural Network (CRNN) with Keras and TensorFlow incorporating both CNN and LSTM. Adjusted the parameters and structure in CRNN to improve model’s performance in ﬁnding the waveform where Marsquake events happen. Used time window to separate time-history waveform in order to get training data. Evaluated the model with 10-fold cross-validation and observed the results using confusion matrices.
  * Classiﬁed both waveform and Fingerprinting data with CRNN and Random Forest. Achieved 80% accuracy on both training and testing stably without overﬁtting the model.
  """
[[experience]]
  title = "Research/Teaching Assistant"
  company = "University of New Mexico"
  company_url = "https://www.unm.edu/"
  location = "Albuquerque, New Mexico, United States"
  date_start = "2017-06-01"
  date_end = "2018-04-30"
  description = """
  Responsibilities include:
  
  * Built machine learning models and wrote reports for research project: “Support Vector Machine and Convolutional Neural Network Applications in Dynamic Vision Sensor Data”. Teaching Assistant for classes Engineering Statics (CE 202) and Structural Dynamics (CE 521).
  """

+++
