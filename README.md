# April27
def bubble_sort(arr):
    swapped = True
    while (swapped):
        swapped = False
        for i in range(len(arr)-1):
            if arr[i] > arr[i+1]:
                arr[i], arr[i+1] = arr[i+1], arr[i]
                # equivalently:
                # temp1 = arr[i]
                # temp2 = arr[i+1]
                # arr[i+1] = temp1
                # arr[i] = temp2
                swapped = True
    return arr
 
input_arrays = [
    [],
    [9, 8, 7, 6, 5, 4, 3, 2, 1],
    [1, 2, 3, 4],
    [4, 6, 1, 3, 7, 8, 4, 3, 4],
    [1],
    [1, 3, 2]
]

sorted_arrays = [
    [],
    [1, 2, 3, 4, 5, 6, 7, 8, 9],
    [1, 2, 3, 4],
    [1, 3, 3, 4, 4, 4, 6, 7, 8],
    [1],
    [1, 2, 3]    
]
 
for i in range(len(input_arrays)):
    print("")
    print(" Input: " + str(input_arrays[i]))
    output_array = bubble_sort(input_arrays[i])
    print("Output: " + str(output_array))
    test_passed = "true" if output_array == sorted_arrays[i] else "false"
    print("Test Passed? " + test_passed)
    def bubble_sort(arr):
swapped = True
    while (swapped):
        swapped = False
        for i in range(len(arr)-1):
            if arr[i] > arr[i+1]:
                arr[i], arr[i+1] = arr[i+1], arr[i]
                # equivalently:
                # temp1 = arr[i]
                # temp2 = arr[i+1]
                # arr[i+1] = temp1
                # arr[i] = temp2
                swapped = True
    return arr
 
input_arrays = [
    [],
    [9, 8, 7, 6, 5, 4, 3, 2, 1],
    [1, 2, 3, 4],
    [4, 6, 1, 3, 7, 8, 4, 3, 4],
    [1],
    [1, 3, 2]
]

sorted_arrays = [
    [],
    [1, 2, 3, 4, 5, 6, 7, 8, 9],
    [1, 2, 3, 4],
    [1, 3, 3, 4, 4, 4, 6, 7, 8],
    [1],
    [1, 2, 3]    
]
 
for i in range(len(input_arrays)):
    print("")
    print(" Input: " + str(input_arrays[i]))
    output_array = bubble_sort(input_arrays[i])
    print("Output: " + str(output_array))
    test_passed = "true" if output_array == sorted_arrays[i] else "false"
    print("Test Passed? " + test_passed)


def draw_a_square(length, angle=90):
    forward(length)
    right(angle)
    forward(length)
    right(angle)
    forward(length)
    rigth(angle)
    forward(length)
    right(angle)

def fly_turtle_fly():
    up()
    right(90)
    forward(150)
    down()

def draw_circle():
    begin_fill()
    fillcolor('red')
    pencolor('green')
    width(10)
    circle(180)
    end_fill()

def draw_star():
    for i in range(5):
        forward(100)
        right(144)

def main():
    
    
    
