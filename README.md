# SQL-Queries-Escape-Room
Region Query:
IF [State] IN ('Washington', 'California', 'Arizona','Texas') THEN 'West'
ELSEIF [State] IN ('Minnesota', 'Iowa', 'Missouri', 'Illinois') THEN 'Midwest'
ELSEIF [State] IN ('Pennsylvania', 'New York','Ohio','Michigan') THEN 'East'
ELSEIF [State] IN ('North Carolina', 'Georgia', 'Florida','South Carolina') THEN 'South'
ELSE 'Rest'
END

Answer 1 Query :
if [1. What was the Profit % for Touring Bikes in 2016 for CA?] == 1 then 'Congratulations!!!! You have crossed the first step'
ELSEIF [1. What was the Profit % for Touring Bikes in 2016 for CA?] == 0
THEN 'CLUE 2'
else  'YOU HAVE FAILED' 
END

Answer 2 Query :
if [2. What was the total Discount % for ALL states in 2014] == 3 then 'Congratulations !!! You have crossed second step'
ELSEIF [2. What was the total Discount % for ALL states in 2014] == 0
THEN 'CLUE 3'
else 'You have failed'
END

ANSWER 3 Query:
if [3. What was the Total Revenue for MO from Year 2014 to 2016?] == 4 then 'Congratuations !! You have unlocked the escape room'
ELSEIF [3. What was the Total Revenue for MO from Year 2014 to 2016?] == 0
THEN ''
else 'You have failed to unlock it !!'
END

ESCAPE STATUS Query:
if [1. What was the Profit % for Touring Bikes in 2016 for CA?]+[2. What was the total Discount % for ALL states in 2014]+[3. What was the Total Revenue for MO from Year 2014 to 2016?] == 8 
THEN "Yay !!!! You have Escaped"
ELSEIF [1. What was the Profit % for Touring Bikes in 2016 for CA?]+[2. What was the total Discount % for ALL states in 2014]+[3. What was the Total Revenue for MO from Year 2014 to 2016?] < 5
THEN 'Escape Journey'
else "Try Again ! "
end
