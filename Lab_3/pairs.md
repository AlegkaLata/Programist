
    numbers = [1, 2, 3, 4, 5, 5, 6, 7]

for i inrange(len(numbers)):

 for j inrange(i+1, len(numbers)):


        if numbers[i] + numbers[j] == 10:


            print(numbers[i], numbers[j])
