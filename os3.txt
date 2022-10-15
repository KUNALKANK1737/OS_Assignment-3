#!bin/sh
echo "Enter the Number a and b"
read a
read b
((add=a + b))
((sub=a-b))
((mul=a*b))
((div=a/b))
echo "Enter Your Choice:"
echo "1.Addition"
echo " 2.Subtraction"
echo "3.Multiplication"
echo "4.Division"
read choice
case $choice in
1)
echo "Sum=$add"
;;
2)
echo "Subtraction=$sub"
;;
3)
echo "Multiplication=$mul"
;;
4)
echo "Division=$div"
;;
