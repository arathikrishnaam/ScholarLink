# ScholarLink
The ScholarLink is designed to help users find scholarships that match their preferences by analyzing a dataset of available scholarships.The system provides an intuitive interface for users to input a scholarship name and receive a list of similar scholarships. 

## Features
- **Scholarship Matching**: Users can input a scholarship name, and the system will suggest similar scholarships based on several features.
- **Data Preprocessing**: The system uses a dataset containing scholarship details such as Name, Education Qualification, Gender, Community, and Income to create combined features for better matching.
- **Cosine Similarity**: The core matching algorithm is based on the cosine similarity of the feature vectors.
- **TF-IDF Vectorization**: Converts text-based features into numerical vectors for comparison using TF-IDF.

