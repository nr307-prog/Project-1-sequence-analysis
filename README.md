# Project-1-sequence-analysis
This is an analysis on NGS mutations in data sequencing.
The purpose of this program is to identify and characterise the mismatches that show up in the sample data provided. It will also allow us to inspect how DNA mutations change between each of the samples provided.
It expects the input of the data sample and outputs a combination of treated, untreated and control samples
My code design consists of validating the read data by preventing any future error flags, this is shown through: 

    for char in upper_seq:
        if char not in "ACGT":
            errors.append("invalid_characters")
            break
#the return statement will send the upper seq value to where it was. 
    return {
        "sequence": upper_seq,
        "valid": len(errors) == 0,
        "errors": errors
    }

In the find mutations variations, I am showing that the data is verified and working correctly, integrating this into the data. this is then summarised into clear tables for the control, untreated, treatment groups.
I divided my work into these categories because it would be simpler to read through the data especially codon data due to its complex length It will also enable to make the statistical and final analysis manageable for comparison work.
There were errors that came up in the project such as indentation, name and syntax errors. I had run into an issue where I was unable to execute my code due to a NameError, this resulted in some variables that were produced by a typo. Indentation errors occurred when I was unable to define code blocks accurately. These errors challenged me to see where I may have missed a variable and to look over my work over again. 
I made these three tests and here is what they entail in my project. I analysed my code and made sure that the code is functional when data is changed, when the data is unreadable and when the data is correct. 
