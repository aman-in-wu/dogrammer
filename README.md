#Dogrammer - 次时代编程

##简介
dogrammer是一个由**python**制作，无关键字，仅用符号和函数的语言，意在让未了解编程的人低门槛踏入编程

例如:
'''dogrammer
#Run all --run time运行条件--
add(a, b) ->
back(math(a+b)) --notice注释--
add(1, 2)
'''

##文件名
dogrammer的文件名一般是.dog🐶🐶🐶

##运行时机 #后是运行时机，包括但不限于:
'''dogrammer
#Run all --运行所有--
#Run line1 to line10 --运行特定行--
#Debug all --调试所有(运行前显示所有变量与栈)--
#Debug line1 to line10 --调试特定行--
#Don't show error:Systemerror --不显示特定错误--
#Don't show any error --不显示所有错误--
#Don't show waring:Runtimewaring --不显示特定警告--
#Don't show any waring --不显示所有警告--
#Langrage Chinese --切换编译器语言为中文--
'''
想要多个条件，可以:
'''dogrammer
#Run all
#Langrage Chinese

--扣子--
'''
推荐写运行时机，没有运行时机编译器会提醒你并让你要不要现在运行
这样:
waring:no run time,
do you want to run at now?(y/n)

##缩进
dogrammer有强制缩进，大小两个空格

##编译器
dogrammer的编译器我会设计的较为智能，例如:
error!: math(a+b in line1 has a Parentheseserror
the dog's suggestion:to fix it,you can try math(a+b)
woof woof
dogrammer

如果你在文件开头加入#Langrage Chinese可以让它说中文:
错误!: 第一行的 math(a+b 有关于括号的错误(Parentheseserror)
狗狗的建议:你可以用math(a+b)来修复它
汪汪
dogrammer

##基本语法
'''dogrammer
--表示字符只能用"chars"--
log()--输出--
input()--输入--

--变量定义--
a = 1
log(a)
--函数定义--
add() ->
  back(math(a+b)) --返回--

add() --调用--
--临时函数--
x -> math(x*2)

--条件判断--
b = 2
b == 2? => --判断b是否等于2，其中?表判断，=>表结果--
  log(b)
b == 3?? => --判断b是否等于3，??表elif，每有一个if判断就要加一个?--
  log(b)
??? => --else，是第几个放置的就加几个?--
  log("I do not kown")

--类--
aclass -->
  step(a, b, c) -> --相当于__init__()--
    a, b, c = a, b, c
  func ->
    back(a+b+c)
  
myclass = aclass()
aclass(func())
'''
