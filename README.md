# Project-1-sequence-analysis
This is an analysis on NGS mutations in data sequencing.
The purpose of this program is to ----
It expects the input of the data sample and outputs ------
My code design consists of validating the read data by preventing any future error flags, this is shown through: 

 upper_seq = sequence.upper()
    errors = []
    if len(upper_seq) != len(reference):
        errors.append("wrong_length")

    for char in upper_seq:
        if char not in "ACGT":
            errors.append("invalid_characters")
            break

    return {
        "sequence": upper_seq,
        "valid": len(errors) == 0,
        "errors": errors
    }

In the find mutations variations, I am showing that the data is verified and working correctly, integrating this into the data. this is then summarised into clear tables for the control, untreated, treatment groups.

I divided my work into these categories because it would be
There were errors that came up in the project such as indentation, name and syntax errors. I had run into an issue where I was unable to execute my code due to a NameError, this resulted in some variables that were produced by a typo. Indentation errors occurred when I was unable to define code blocks accurately. These errors challenged me to see where I may have missed a variable and to look over my work over again. 
I made these three tests and here is what they entail in my project. I analysed my code and made sure that is 
