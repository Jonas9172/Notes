# Notes

1. 数组最后一个元素：a[-1]
2. 将字符串中的大写字母小写化：lower()
3. 统计str1中str2的出现次数：str1.count(str2)
4.
<img width="515" alt="屏幕截图 2023-12-14 140831" src="https://github.com/Jonas9172/Notes/assets/105164575/6081e3d1-22a9-44d1-83c1-8c2503ffde84">

5.
<img width="517" alt="屏幕截图 2023-12-14 140914" src="https://github.com/Jonas9172/Notes/assets/105164575/ae2d2872-9878-4428-bad0-231999f82247">

6.
<img width="512" alt="屏幕截图 2023-12-14 140940" src="https://github.com/Jonas9172/Notes/assets/105164575/5016aa8d-a5c1-4448-b6b3-43a3363e9146">

7.
<img width="515" alt="屏幕截图 2023-12-14 140947" src="https://github.com/Jonas9172/Notes/assets/105164575/3f69071f-8dd2-45b7-9393-845ac5afd0a5">

8.
<img width="652" alt="屏幕截图 2023-12-14 141757" src="https://github.com/Jonas9172/Notes/assets/105164575/8ca1a69d-2f6a-407b-8a97-d80f74ee734f">

9. list.sort()改变list，无返回值。 倒序排列：list.sort(reverse=True)；对第二个关键字排序：list.sort(key=lambda x:x[1]); 多级排序：list.sort(key=lambda x:(x[1],x[0]))
10.  sorted(list)不改变list，有返回值  注意：不能对string格式的数字排序; list.reverse()将列表倒过来，无返回值; a = sorted(list(set(a)),key=a.index)把字符串或列表中的重复元素删除但是不打乱原来的顺序
11.
<img width="238" alt="屏幕截图 2023-12-14 145531" src="https://github.com/Jonas9172/Notes/assets/105164575/2bb61786-4daf-4f3a-96da-b51f63ced905"> <img width="323" alt="屏幕截图 2023-12-14 145703" src="https://github.com/Jonas9172/Notes/assets/105164575/7570d930-c01d-43b2-896b-2910e82c6053">

12. 字符串可以使用索引，例如 str[-1]； 字符串长度：len(str)； 字符串切片：str[:], str[0:3], str[3:-3], str[-3:]， str[首:尾:步长]； 取字符串中每一个字符---for each in str； 判断字符是否在字符串中---if each in str; 得到字符在字符串中第一次出现的索引位置---str2.find("str1"); 字符和字符串可以使用加法---each + str; 列表也可以使用切片操作，例如可以使用切片对string每个偶数位进行排序---string[::2] = sorted(string[::2])；range(4,-1,-1)指[4,3,2,1,0]
    <img width="369" alt="屏幕截图 2023-12-15 121645" src="https://github.com/Jonas9172/Notes/assets/105164575/e2b8834e-d61c-4d9a-9adb-9162a80489a9">

14. 用ljust(8,"0")在字符串左侧对齐的情况下对右侧进行补位；rjust()反之
15. int("str", base=16) 把str视为16进制并转换为10进制的整数。 十进制转为二进制：bin()[2:]；转为八进制：oct()；转为十六进制：hex()
16. 删除的四种操作：del listname[start : end]； listname.pop(index)--默认最后一个, 改变原值并返回删除的值； remove(值)--只能删除list中的第一个； clear()--清空list；  字符串的替换和删除操作: str.replace("old","new",times), 不改变原值，return结果
17. print(str, end=" ") 让下一次的print内容和此次以" "相连; print(','.join(string))---将string中的每个字符用,隔开，也可以用于list
18.  print中的%用法

<img width="366" alt="屏幕截图 2023-12-16 145045" src="https://github.com/Jonas9172/Notes/assets/105164575/f854fe03-cb58-4dba-94c3-27372f0c02c9"><img width="464" alt="屏幕截图 2023-12-16 145056" src="https://github.com/Jonas9172/Notes/assets/105164575/39e04b23-2ef1-45e6-bd05-b83105da311a">

19. print中的format()
<img width="402" alt="屏幕截图 2023-12-16 144827" src="https://github.com/Jonas9172/Notes/assets/105164575/ef51455d-6179-423b-9dc1-f9ee38f79881">

20. 暴力求质因数（用试除法求一个数所有为质数的因子），时间复杂度为O(n)：
<img width="192" alt="屏幕截图 2023-12-15 105253" src="https://github.com/Jonas9172/Notes/assets/105164575/978410a8-8f81-4e38-981b-bbfef8963add">

21. 优化后：
<img width="231" alt="屏幕截图 2023-12-15 111953" src="https://github.com/Jonas9172/Notes/assets/105164575/6e4d2356-746d-42d2-b017-3a8233407c0d">

22. 浮点数：float()
23. 取整：
<img width="473" alt="屏幕截图 2023-12-15 113603" src="https://github.com/Jonas9172/Notes/assets/105164575/464f111d-4825-4d79-82e4-914bb40af856">

24. ord() -- 返回对应的 ASCII 数值; chr() -- 输入一个ASCII值返回对应的符号； "A" < ""两个字符串中第一个字符的ASCII值越大，字符串越大; 0-9:48-57, A-Z:65-90, a-z:97-122
25. continue跳出本次循环；break跳出整个for循环
26. isinstance(element, int) 判断element是否是某个类型
27. 判断字符串里是否全是数字--str.isdigit(); 判断字符串里是否全是字母--str.isalpha(); 判断字符串里是否全是数字或字母--strstr.isalnum(); 判断str中所有字母都是大写--isupper(); 判断str中所有字母都是小写--islower(); lower()和upper()可以将字符串中所有的字母变成大小写
28. 将list中的string转换为int格式：a = [int(num) for num in a]  或者  a = list(map(int, a))
29. 二维列表的创建 --- a = [[0 for col in range(m)] for row in range(n)]
30. 动态规划---将一个问题拆分为很多小问题，也就是说一个大的解决方案需要多步小步骤实现
31. sum()可以对列表，数组，元组使用
32. zip(a,b)是将两个相同大小的列表合成一个充满元组的列表，例如：zip([1,2,3],[3,4,5])返回[(1,3),(2,4),(3,5)]
33. 二分搜索---bisect.bisect_left(list, num)在升序数列中如果插入一个num，那么num应该插在哪呢，该函数返回此位置的索引
34. enumerate()返回列表元组或字符串中元素的下标和本体
35. list可以直接用==比较
36. 素数（质数）一定是奇数加偶数；任意一个大于二的偶数，都能写成两个质数之和；1不是素数
37. 最大回文子序列要分成单中心和双中心
38. 等差数列和等比数列

![图片](https://github.com/Jonas9172/Notes/assets/105164575/23f8860e-b14e-4148-8666-379acbbb6d42)

39. 元组元素不能被修改; 如果想把元组(1, 2)里的空格删去再打印需要--print('(%d,%d)'%i)
40. list.index() 函数用于从列表中找出某个值第一个匹配项的索引位置。
41. eval() 函数用来执行一个字符串表达式，并返回表达式的值。例如：print(eval("2 + 3 * 4"))  # 输出: 14
42. abs() -- 绝对值
43. n = [1,2,3,4]
    a = n
    a.pop(2)  #n=[1,2,4] 因为列表是可变元素，所以a的指针指向n，而不是创建一个相同列表。如果不想改变n的值，可以使用a = n.copy()或a = n[:]
    但是，如果是n = [[1,2],[2,3]]这样的多维列表，还要使用copy.deepcopy(n)
    
    ![图片](https://github.com/Jonas9172/Notes/assets/105164575/61bc7f73-8b6a-44e9-b010-24e438240f11)


45. 正则表达式表达模式
   
    <img width="596" alt="屏幕截图 2023-12-26 111448" src="https://github.com/Jonas9172/Notes/assets/105164575/347ca67d-eab4-4c09-b08e-97683ea6d5df">
<img width="429" alt="屏幕截图 2023-12-26 110805" src="https://github.com/Jonas9172/Notes/assets/105164575/000e7835-4a66-46c9-9ea3-40499df35867">

   re.findall(pattern, string)---在字符串中找到正则表达式所匹配的所有子串

45. 寻找两个字符串中最长公共子串:

    ![图片](https://github.com/Jonas9172/Notes/assets/105164575/59d3f770-b440-4127-bfd7-ffaab90b9703)

46. 排列组合公式：
    
    ![图片](https://github.com/Jonas9172/Notes/assets/105164575/a1e13d6e-99f7-4531-8fc0-f0f729c8e17f)

47. 取一位小数： round(2.333,1)
48. str1.startswith('str2') 和str1.endswith('str2') 是用来判断字符串str1是否以str2开头或结尾
49. math.sqrt(144) 和 144**0.5 --- 都是求144的平方根; pow(x,y)和math.pow(x,y)都是返回x的y次方,区别是pow()对于浮点数的计算可能不够精确。
50. 最大公倍数等于两个数的乘积除以最大公约数
51. max(list,key=len,default='') 返回list中最长的string
52. 使用 append() 函数添加列表时，是添加列表的「引用地址」而不是添加列表内容，当被添加的列表发生变化时，添加后的列表也会同步发生变化。    函数的参数使用的也是引用地址
53. 堆的优点和局限性

    ![图片](https://github.com/Jonas9172/Notes/assets/105164575/9dd680bd-0b0e-4c6a-b2ff-1aca92509487)

54. 栈的实现
    
    ![图片](https://github.com/Jonas9172/Notes/assets/105164575/627b4664-f1dc-41d0-9853-8f7e6f18182d)

55. 队列（queue）先进先出的特性对多线程安全有什么作用：

    ![图片](https://github.com/Jonas9172/Notes/assets/105164575/c0d7c837-8499-44f3-84d7-a7b17985bb55)

56. 两种可变参数
    
    ![图片](https://github.com/Jonas9172/Notes/assets/105164575/532bced7-edcf-4e4d-bb9c-e27780b7f350)

    ![图片](https://github.com/Jonas9172/Notes/assets/105164575/a5a27b65-029b-41ea-ae82-87f3c3cb73cd)

57. generator的生成，和yield的使用方法

    ![图片](https://github.com/Jonas9172/Notes/assets/105164575/ffd8cd64-a3aa-46a9-b24d-5ece644b9db8)

58. 在函数中，局部变量存储在固定长度的数组中，而不是存储在字典中。这个数组可以通过索引直接访问，使得变量检索非常快。
    全局变量存储在一个字典。当访问全局变量时，Python 必须执行哈希表查找，这涉及计算哈希值，然后检索与之关联的值虽然经过优化，但仍然比基于索引的查找慢。

59. 定义装饰器的例子：

    ![图片](https://github.com/Jonas9172/Notes/assets/105164575/d77c8ff3-f8ae-4e54-950e-d563ed707ee4)

60. 内存泄漏：python中一个程序使用完内存块后，python的垃圾回收机制认为程序还在使用这个内存块，导致这个内存块一直没有被释放。对象的循环引用可能会导致这个问题。
61. 全局解释器锁（Global Interpreter Lock，GIL）：同一时刻只允许一个线程，也就是说线程只能并发不能并行。
62. 网络分层
    
    ![图片](https://github.com/Jonas9172/Notes/assets/105164575/03ed4c5d-3bcc-422a-8799-0a2fbd527678)















