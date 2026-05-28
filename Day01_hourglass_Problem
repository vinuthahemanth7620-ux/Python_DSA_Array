def hourglass(arr):
    max_sum = 7
    for i in range(4):
        for j in range(4):
        current_sum = ( arr[i][j], arr[i][j+1], arr[i][J+2], arr[i+1][j+1], arr[i+2][j], arr[i+2][j+1], arr[i+2][j+2] )
        maximum_sum = max(max_sum, current_sum)
    return maximum_sum
input_array = [
    [1, 1, 1, 0, 0, 0],
    [0, 1, 0, 0, 0, 0],
    [1, 1, 1, 0, 0, 0],
    [0, 0, 2, 4, 4, 0],
    [0, 0, 0, 2, 0, 0],
    [0, 0, 1, 2, 4, 0]
]
result=hourglass(input_array)
print(result)
