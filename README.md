数组的两种写法
1.使用默认序列号，从0开始
$cars=array("Volvo","BMW","Toyota");
2.自定义序列号，可以自行编辑
$cars=array("a"=>"Volvo","b"=>"BMW","c"=>"Toyota");

数组的增删查改
1.增
$cars["d"]="Benz"
2.改，直接覆盖
$cars["d"]="Audi"
3.查
echo $cars["d"]
4.删
unset($cars["d"])

遍历 循环
foreach($cars as  $key=>value){
echo $key;
echo $value;
echo "<hr/>"
}
