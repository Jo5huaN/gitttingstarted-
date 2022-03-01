'''
Plan for box calculater 

get user input for number of items 

divide input by big boxes 

then remaining items divided by medium boxes 

finally remaining items divided by small boxes 

then print how many of each box needed 
'''

#box calculater 

big_box = 5
med_box = 3
small_box = 1
#greeting message 

print("  Hello and welcome to box calculater...  ")

#asking user for number of items 

print(" please tell us how many items do you have ")

number_of_items = int(input())

print(" Okay you have " , number_of_items, "items so .... ")

#function for divide 

def divide (x, y):
    return x // y


#dividing number of items by big boxes 
large_boxes_needed = ((divide(number_of_items, big_box)))
print(" you will need ",large_boxes_needed, " Large boxes ")

#finding out boxes remaining 
big_boxes_remaining = (number_of_items % big_box)

(big_boxes_remaining)
#dividing number of items by big_boxes_remaining

med_boxes_needed = ((divide(big_boxes_remaining, med_box)))

#dividing number of items by med_boxes_remaining
print(" you will need ", med_boxes_needed, " Medium boxes" )

med_boxes_remaining = (big_boxes_remaining % med_box)
(med_boxes_remaining)


#dividing number of items by small_boxes_remaining
small_boxes_needed = ((divide(med_boxes_remaining, small_box)))
print( " you will need ", small_boxes_needed, " Small box ")

small_boxes_remaining = (med_boxes_remaining % small_box)
(small_boxes_remaining)
