# The-arithmetic-average-of-two-numbers

Task text:

Write a program that finds the arithmetic average of two numbers: get two variables and write each number by number.
Then get the third one and write down the arithmetic average of the first two. And then put all this on the screen.

# defined array

greeting = [

	"Введите два числа:",
	"Здравствуйте, введите пожалуйста два целых натуральных числа:",
	"Оу.. Вы нас снова посетили! Не соблаговолите ли ввести два числа для нахождения их среднего арифметического? Прошу:"

]

# output a random array value using the method sample

puts greeting.sample

# started two numeric objects that accept numeric values from the user

num1 = gets.to_i
num2 = gets.to_i

# num3 takes arithmetic average num1 && num2, and output arithmetic average

num3 = (num1 + num2)/2

puts "Среднее арифметическое чисел #{num1} и #{num2} => #{num3}"
