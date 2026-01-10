# Random-tiny-python-scripts
Random python problems that i will solve or just random scripts + ideas

def rolling_average(data, k):
    """
    data is a list of numbers
    k is a positive integer

    Return a new list where each element is the average
    of the previous k values (including the current one).

    If there are fewer than k previous values,
    average whatever is available.
    """
new_data = []
last_valid_value = 0 

for value in data:
        if value is None:
            # Use the last recorded valid value
            clean_data.append(last_valid_value)
        else:
            # A valid value was found; update last_valid_value and append
            last_valid_value = value
            clean_data.append(value)
            
    return clean_data
