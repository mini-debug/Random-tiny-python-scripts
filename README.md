# Random-tiny-python-scripts
Random python problems that i will solve or just random scripts + ideas

#1; counting groups if reapted indexes in list 
 def count_runs_list(L):
    count = 0
    for i in range(len(L)):
        if i == 0 or L[i] != L[i-1]:
            count += 1
    return count