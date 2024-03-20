mpg= float(input())
cost = float(input())
distance_1 = float(input())
distance_2 = float(input())
distance_3 = float(input())
short_trip = (distance_1/mpg)*cost
med_trip = (distance_2/mpg)*cost
long_trip = (distance_3/mpg)*cost

print(f'{short_trip:.2f} {med_trip:.2f} {long_trip:.2f}')