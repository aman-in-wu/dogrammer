# Dogrammer —— 次时代编程

## 简介
`dogrammer`是一个由**python**制作，无关键字，仅用符号和函数的解释型语言，意在让未了解编程的人低门槛踏入编程。例如:
```dogrammer
#Run all --run time运行条件--
add(a, b) ->
back(math(a+b)) --notice注释--
add(1, 2)
```

## 文件名
`dogrammer`的文件名后缀一般是`.dog`。 🐶🐶🐶

## 运行时机
在`#`后是运行时机，包括但不限于:
```dogrammer
#Run all                          --运行所有--
#Run line1 to line10              --运行特定行--
#Debug all                        --调试所有(运行前显示所有变量与栈)--
#Debug line1 to line10            --调试特定行--
#Don't show error:Systemerror     --不显示特定错误--
#Don't show any error             --不显示所有错误--
#Don't show waring:Runtimewaring  --不显示特定警告--
#Don't show any waring            --不显示所有警告--
#Language Chinese                 --切换编译器语言为中文--
```
想要多个条件，可以:
```dogrammer
#Run all
#Language Chinese
```
在没有[运行时机](#运行时机)时，编译器会提醒并询问是否现在运行，就像:
```warning
waring:no run time,
do you want to run at now?:(y/n)
```


##  编译器
`dogrammer`的编译器会设计的较为智能，例如:
```
error!: math(a+b in line1 has a Parentheseserror
the dog's suggestion:to fix it,you can try math(a+b)
woof woof
dogrammer
```
中文翻译即：
```如果你在文件开头加入#Langrage Chinese可以让它说中文:
错误!: 第一行的 math(a+b 有关于括号的错误(Parentheseserror)
狗狗的建议:你可以用math(a+b)来修复它
汪汪
dogrammer
```
## 基本语法
- 缩进
`dogrammer`有强制缩进，大小为2个空格
- 输出 & 输入
```dogrammer
log()    -- 输出 --
input()  -- 输入 --
```


- 变量定义
```dogrammer
a = 1
log(a)
```

- 函数定义
```dogrammer
-- 普通函数 --
add(a, b) ->
  back(math(a+b))  -- back() 表示返回 --

add(1, 2)          -- 函数调用 --

-- 临时函数 --
x -> math(x*2)
```

- 条件判断
> `?` 表示判断，`=>` 表示结果，`??` 相当于 `elif`，`???` 相当于 `else`

```dogrammer
b = 2

b == 2? =>       -- if：判断 b 是否等于 2 --
  log(b)

b == 3?? =>      -- elif：判断 b 是否等于 3（每多一个分支多一个 ?）--
  log(b)

??? =>           -- else：第几个分支就加几个 ? --
  log("I do not know")
```

- 字符串
> 字符只能使用双引号 `"chars"`

```dogrammer
log("Hello, World!")  -- 输出：Hello, World! --
```

- 类
```dogrammer
aclass -->
  step(a, b, c) ->      -- 相当于 __init__() --
    a, b, c = a, b, c

  func ->
    back(math(a+b+c))

myclass = aclass()     -- 实例化 --
myclass(func())        -- 调用方法 --
```

---



> **developed by *aman-in-wu***

