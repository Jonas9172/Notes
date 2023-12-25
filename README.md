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

9. list.sort()改变list，无返回值。 倒序排列：list.sort(reverse=True)；对第二个关键字排序：list.sort(key=lambda x:x[1])
10.  sorted(list)不改变list，有返回值  注意：不能对string格式的数字排序; list.reverse()将列表倒过来，无返回值; a = sorted(list(set(a)),key=a.index)把字符串或列表中的重复元素删除但是不打乱原来的顺序
11.
<img width="238" alt="屏幕截图 2023-12-14 145531" src="https://github.com/Jonas9172/Notes/assets/105164575/2bb61786-4daf-4f3a-96da-b51f63ced905"> <img width="323" alt="屏幕截图 2023-12-14 145703" src="https://github.com/Jonas9172/Notes/assets/105164575/7570d930-c01d-43b2-896b-2910e82c6053">

12. 字符串可以使用索引，例如 str[-1]； 字符串长度：len(str)； 字符串切片：str[:], str[0:3], str[3:-3], str[-3:]， str[首:尾:步长]； 取字符串中每一个字符---for each in str； 判断字符是否在字符串中---if each in str; 得到字符在字符串中第一次出现的索引位置---str2.find("str1"); 字符和字符串可以使用加法---each + str; 列表也可以使用切片操作，例如可以使用切片对string每个偶数位进行排序---string[::2] = sorted(string[::2])
    <img width="369" alt="屏幕截图 2023-12-15 121645" src="https://github.com/Jonas9172/Notes/assets/105164575/e2b8834e-d61c-4d9a-9adb-9162a80489a9">

14. 用ljust(8,"0")在字符串左侧对齐的情况下对右侧进行补位；rjust()反之
15. int("str", base=16) 把str视为16进制并转换为10进制的整数。 十进制转为二进制：bin()[2:]；转为八进制：oct()；转为十六进制：hex()
16. 删除的四种操作：del listname[start : end]； listname.pop(index)--默认最后一个, 返回删除的值； remove(值)--只能删除list中的第一个； clear()--清空list；  字符串的替换和删除操作: str.replace("old","new",times), 不改变原值，return结果
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
38. 等差数列和公式 Sn=n (a1+an)/2=na1+n (n-1)/2 d； 等比数列求和公式 q≠1时 Sn=a1 (1-q^n)/ (1-q)= (a1-anq)/ (1-q) q=1时Sn=na1 (a1为首项,an为第n项,d为公差,q 为等比)
39. 元组元素不能被修改; 如果想把元组(1, 2)里的空格删去再打印需要--print('(%d,%d)'%i)
40. list.index() 函数用于从列表中找出某个值第一个匹配项的索引位置。
41. eval() 函数用来执行一个字符串表达式，并返回表达式的值。例如：print(eval("2 + 3 * 4"))  # 输出: 14
42. abs() -- 绝对值
43. n = [1,2,3,4]
    a = n
    a.pop(2)  #n=[1,2,4] 因为列表是可变元素，所以a的指针指向n，而不是创建一个相同列表。如果不想改变n的值，可以使用a = n.copy()或a = n[:]
