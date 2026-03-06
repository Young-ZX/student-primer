# Document your edge case here
- To get marks for this section you will need to explain to your tutor:
1) The edge case you identified
During calculations in get_status, the denominator len(valid_marks) may result in an error when this value is 0. This occurs when there are no students in the database or when students have no valid scores.
2) How you have accounted for this in your implementation
Add a check, if the student list is empty or the len(valid_marks) is zero, return zero for each output value and display a prompt instead of throwing an error.