# **Medical Records Validator in Python**

A **validation tool for medical patient records**. The program ensures patient data follows the correct format and meets specific validation rules for fields like **patient ID, age, gender, diagnosis, medications, and visit IDs**. Records are validated against predefined constraints to maintain **data integrity**.

---

##  How to Run

1. Ensure you have **Python 3.6 or higher** installed.  
2. Download `medical_records_validator.py`.  
3. Run the program from the terminal:

```bash
python medical_records_validator.py
```
## What I Learned / Concepts Demonstrated
-Using a list of dictionaries to store structured data (medical records).

-Defining functions (find_invalid_records, validate) to modularize validation logic.

-Regular expressions (re.fullmatch) to enforce patterns for IDs.

-Type checking and value constraints for different fields (e.g., age must be ≥ 18, gender must be male/female).

-Handling optional fields (e.g., diagnosis can be None).

-Looping through records with enumerate() to provide index-based error reporting.

-Boolean flags to track validation status across multiple records.

-Unpacking dictionaries with ** to pass as keyword arguments to functions.

-Printing informative error messages for invalid formats.

## Future Improvements
-Allow the user to input medical records dynamically instead of using hardcoded data.

-Save validation results to a log file for auditing purposes.

-Expand validation rules to include date checks, numeric ranges, or drug interactions.

-Add a GUI or web interface for easier data entry and validation.

-Allow partial record correction rather than rejecting the entire record.
