# Moh1
my code aaa
input_str = input("Enter the string : ")
input_char = input("Enter the char : ")


def my_function(my_str , my_char):
  count=0
  for char in my_str:
    if char == my_char:
      count=count+1
  print(count)

my_function(input_str,input_char)
