5-1 安裝, 測試Apache Server, 並且架設自己的網站

sudo apt update && sudo apt install apache2
![1](https://user-images.githubusercontent.com/89715433/174984421-a5120b62-a798-442f-a0c0-eebdd979cc34.jpg)
![2](https://user-images.githubusercontent.com/89715433/174984431-acb10106-1f6a-4ba9-b1e1-319a23538c85.jpg)
![3](https://user-images.githubusercontent.com/89715433/174984442-f5726dfe-967c-4b5e-a0f0-32f553a0415c.jpg)

sudo service apache2 status
![4](https://user-images.githubusercontent.com/89715433/174984452-906d67a7-d90d-4b38-9a2a-5d87a9db0ab9.jpg)
![5](https://user-images.githubusercontent.com/89715433/174985047-6721290a-d800-4e29-802d-15e55cef1db3.jpg)

sudo apt install net-tools
ifconfig
![6](https://user-images.githubusercontent.com/89715433/174986155-d01324a2-fdc4-41b4-bcc9-2d41bccaac7b.jpg)
![7](https://user-images.githubusercontent.com/89715433/174986166-7f716c6d-7b0e-4e29-b996-18a8ac6cbb62.jpg)

5-2 Apache 網頁伺服器起手式

sudo gedit /var/www/html/index.html
![8](https://user-images.githubusercontent.com/89715433/174987221-13bacdf4-f85b-48af-b383-a21fe8cd63e3.jpg)
![9](https://user-images.githubusercontent.com/89715433/174990291-082a26db-ab5b-42e7-9fac-998d2def26b6.jpg)
![10](https://user-images.githubusercontent.com/89715433/174990303-a4de9380-4ecd-458b-834b-1e49ddf30615.jpg)
![12](https://user-images.githubusercontent.com/89715433/174991538-81e1f117-16b9-4f7a-9756-2525945df4e1.jpg)
![11](https://user-images.githubusercontent.com/89715433/174991255-8a3fb02c-b9a8-4c7e-93fc-dd78a67d9633.jpg)




<!DOCTYPE html>
<html>

<head>
<meta charset="UTF-8">
<title>虛擬化系統與實作</title>
</head>

<body>

<h1>虛擬化系統與實作</h1>
<br>
<h2>Created by jl, VNU</h2>
<h2>Date: 2022.05.08</h2>
<br>
<h2>Good Job ! jl !!</h2>

</body>
</html>

![13](https://user-images.githubusercontent.com/89715433/174992266-1946b44e-157b-44ec-abee-3181ad25e340.jpg)

<meta charset="UTF-8">

<h1>*** 1. HTML Headings ***</h1>

<h1>虛擬化系統與實作 1</h1>
<h2>虛擬化系統與實作 2</h2>
<h3>虛擬化系統與實作 3</h3>
<h6>虛擬化系統與實作 6</h6>
<hr size="3" width="100%" color="red"> 

<h1 style="color:red;">*** 2. HTML Paragraphs ***</h1>
<p>
巧克力，是以可可樹的種子作為主要原料製作的食品，它可以是固體、液體或糊狀，也可作為其他食品的調味料。巧克力的出現最早可以追溯到公元前19世紀的奧爾梅克文明，在其遺址發現飲用巧克力飲料的痕跡。大多數的中部美洲文明都會製作巧克力飲料，包括瑪雅文明和阿茲特克。
</p>
<hr size="3" width="100%" color="red"> 
<br>
<br>
<h2 style="color:blue;">Created by jl. Date: 2022.05.08</h2>


![14](https://user-images.githubusercontent.com/89715433/174998714-0ad3114d-6766-4bf4-942c-23034a6cdc62.jpg)
![15](https://user-images.githubusercontent.com/89715433/174998794-3d488394-211f-40d7-8e18-b79b4cc75a62.jpg)


<!DOCTYPE html>
<html>
<body>

<h1 style="color:red;"> *** Hi I'm jl *** </h1>
<h2> Tested by jl, VNU @ Date: 2022.05.08 </h2>

<iframe width="560" height="315" src="https://www.youtube.com/embed/AtYCK4O4ZbE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<iframe width="300" height="200" src="https://www.youtube.com/embed/ZhD0FtWSiRo">
</iframe>
<hr size="3" width="100%" color="red">  
<iframe width="300" height="200" src="https://www.youtube.com/embed/VA_c5itfcsA">
</iframe>
<hr size="3" width="100%" color="red"> 

</body>
</html>


sudo gedit vun.html
![16](https://user-images.githubusercontent.com/89715433/175001589-f9fa28f8-d778-41fb-bc55-b621d2ba75e2.jpg)



<!DOCTYPE html>
<html>
< meta charset="UTF-8">
<body>

<h1 style="color:red;"> *** My First Web Site by Apache Server and Ubuntu 20.04*** </h1>
<h2> Tested by jl, VNU @ Date" 2022.05.08 </h2>

<iframe src="https://www.vnu.edu.tw/" style="border:0px #ffffff none;" name="VNU" scrolling="no" frameborder="1" marginheight="0px" marginwidth="0px" height="400px" width="600px" allowfullscreen></iframe>

  ![17](https://user-images.githubusercontent.com/89715433/175002045-e6623893-4adc-4edd-a236-4194fd81ca03.jpg)
 
  


5-3 Apache 網頁伺服器應用
sudo apt install git


