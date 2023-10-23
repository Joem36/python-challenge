During this challenge I had the tutor by the name of kelly Kennedy assist me with  this specific line of code in my election_data listed below

with open(infile) as in_file:
    reader = csv.reader(in_file) # python-challenge
    header = next(reader)


I utilized Stackoverflow for reference only when it comes how to initite code regarding specfic data.  Reference only 


I utilized the sane initation process that kelli helped me with on election data and I did the same thing to my Budget_data


Utilized BCS assistant and an "Amilla" (TA) assisted me with the line of code listed below for the Budget_data

if previous_value is not None: #this logic will start from the second iteration and will hold as true 
            month_change = profit_changes - previous_value #subtracting profit and loss changes from this month from the previous month that will give me a months change 
            if month_change > greatest_increase: #the first loop through this logic will hold as true. 
                greatest_increase = month_change 
            if month_change < greatest_decrease:
                greatest_decrease = month_change
            if month_change == greatest_increase:#checking if they are the same 
                greatest_increase_month = y[0] #save this to the greatest increase month
            if month_change == greatest_decrease:
