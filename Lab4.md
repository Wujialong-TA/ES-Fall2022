[4-1 Linux 常用文件指令 (12 commands)
![1](https://user-images.githubusercontent.com/89715433/174972401-24a5152b-9e7d-48f2-ac37-9fa83e44ebe9.png)
![2](https://user-images.githubusercontent.com/89715433/174972413-c212fdd6-5443-43d2-a286-e1bfa5e5c96f.png)
![3](https://user-images.githubusercontent.com/89715433/174972419-e0951b3c-d17e-42c9-b919-7495555b2b7b.png)
![4](https://user-images.githubusercontent.com/89715433/174972425-1aeb7be0-d2f5-4aae-a60c-32f00e55ed5f.png)
![5](https://user-images.githubusercontent.com/89715433/174972457-5f2c6e32-d17c-4f40-afe0-3e77e3ec3c19.png)
![6](https://user-images.githubusercontent.com/89715433/174972472-c0330c97-faf8-4165-a789-e772010ea0f8.png)
![7](https://user-images.githubusercontent.com/89715433/174972485-1209c2d3-55a2-4d88-902a-f3f2840bb9eb.png)
![8](https://user-images.githubusercontent.com/89715433/174972506-f78681b0-c18a-427e-b374-fbf2144eae2e.png)
![9](https://user-images.githubusercontent.com/89715433/174972511-f2d7a41f-3efe-4582-b581-b746a82ca0e6.png)
![10](https://user-images.githubusercontent.com/89715433/174972519-c670b6c2-36c8-4b5f-a882-e61caa3950c0.png)
![11](https://user-images.githubusercontent.com/89715433/174972529-7cd0a82f-0b35-47e9-9ce5-08daa43da5a2.png)
![12](https://user-images.githubusercontent.com/89715433/174972538-38750219-58f8-421d-b7e0-06a63e8624fc.png)


[4-2 BASH Shell介紹與實戰]


創建並執行第一個 BASH 程序
![1](https://user-images.githubusercontent.com/89715433/174972691-fe1d9ebd-1349-460f-aaf1-236440889f71.jpg)


加減乘除
![2](https://user-images.githubusercontent.com/89715433/174972767-a6999fd1-e3b9-469e-81bd-722dfa98868f.jpg)



#!/bin/bash

# add, subtract, multiply, divide 2 numeric value
((result1 = 1+100))
((result2 = 100-1))
((result3 = 9*9))
((result4 = 9/9))
# Print the results
echo $result1
echo $result2
echo $result3
echo $result4
echo "Done by jl"




使用While Loop
![3](https://user-images.githubusercontent.com/89715433/174973681-38395a38-3f9f-429b-b7b2-ba15bd4d1d73.jpg)



#!/bin/bash
valid=true
count=1
((result=0))


使用For Loop
![4](https://user-images.githubusercontent.com/89715433/174974000-c5d036ac-1d60-46b0-aae1-bddd5d860eda.jpg)

#!/bin/bash

((result = 0 ))

for (( counter=i; counter<=10; counter++ ))
do
echo -n "$counter "
((result = result + counter))
done

echo -n ", sum = "$result
printf "\n"

讓使用者輸入
![5](https://user-images.githubusercontent.com/89715433/174976065-20778620-45ce-45b4-9aae-6e54c992603e.jpg)

#!/bin/bash

echo "Enter your name"
read name
echo "Welcome $name to Ubuntu Linux"
echo ""
date
echo ""
ls -lrt JiaLong*
echo ""
echo "Good job! $name !"


while [ $valid ]
do
echo $count
((result = result + count))

if [ $count -eq 10 ];
then
break
fi
((count++))

done

echo '1+2+....+10 = '$result


自動產生9x9表, 並自動將結果輸出到 table99.txt 中
![6](https://user-images.githubusercontent.com/89715433/174979741-6c536dfe-7360-44b8-8c43-8ebd251b7707.jpg)
![7](https://user-images.githubusercontent.com/89715433/174979838-2925891c-2504-43fb-8f96-9c07a5b99f63.jpg)


rm jl_table99.txt

clear
date
echo ""
echo 'Table 9x9, by jl, CSIE VNU'

for (( i=1;i<=9;i++ )); do
	for (( j=1;j<=9;j++)); do
		echo -ne "${j}x${i}=$[$i*$j] \t"
		echo -ne "${j}x${i}=$[$i*$j] \t" >> jl_table99.txt	
	done
	echo ""
	echo "" >> jl_table99.txt
	
done


echo ""
echo 'Check the output file: table99.txt'
echo ""

echo ""
head jl_table99.txt
echo ""
echo "Excellent job, jl!"
echo ""

