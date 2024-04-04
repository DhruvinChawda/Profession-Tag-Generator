# Profession-Tag-Generator
Profession tag generator based on skills as input. This project will help to generate an optimal role for an applicant based on applicant's skills.

This is a basic version, and for real-world applications, you might want to consider more advanced natural language processing techniques and larger, more comprehensive datasets for skill-to-profession mappings.

This code defines a simple mapping of professions to their related skills and provides a function, determine_profession, which processes a list of skills to find the best-matching profession. The profession with the highest number of matching skills from the provided list is considered the most likely profession for the person. If no skills match, it returns 'Unknown'.

Remember, the accuracy of this function heavily depends on the comprehensiveness and accuracy of the profession_skills dictionary. For more complex or accurate mappings, you might need to expand this dictionary significantly or consider machine learning approaches.

FOR THE APPROACH WHERE DATASET (CSV FILE) IS USED : This code replaces the hardcoded profession_skills dictionary with one dynamically constructed from the expanded CSV dataset. Make sure to replace 'path/to/your/expanded_profession_skills.csv' with the actual path where you saved the expanded_profession_skills.csv file. Running this script will determine the profession based on the provided skills, using the newly loaded dataset.
