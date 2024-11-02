def move_zeros(numbers):
    # Iterate through the list using the index
    for i in range(len(numbers)):
        # Check if the current element is zero
        if numbers[i] == 0:
            # Remove the first occurrence of 0 from the list
            numbers.remove(0)
            # Append 0 to the end of the list
            numbers.append(0)
    
    # Return the modified list with all zeros moved to the end
    return numbers
