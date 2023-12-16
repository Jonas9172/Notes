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
10.  sorted(list)不改变list，有返回值  注意：不能对string格式的数字排序
11.
<img width="238" alt="屏幕截图 2023-12-14 145531" src="https://github.com/Jonas9172/Notes/assets/105164575/2bb61786-4daf-4f3a-96da-b51f63ced905"> <img width="323" alt="屏幕截图 2023-12-14 145703" src="https://github.com/Jonas9172/Notes/assets/105164575/7570d930-c01d-43b2-896b-2910e82c6053">

12. 字符串可以使用索引，例如 str[-1]； 字符串长度：len(str)； 字符串切片：str[:], str[0:3], str[3:-3], str[-3:]， str[首:尾:步长]； 取字符串中每一个字符---for each in str； 判断字符是否在字符串中---if each in str; 字符和字符串可以使用加法---each + str
    <img width="369" alt="屏幕截图 2023-12-15 121645" src="https://github.com/Jonas9172/Notes/assets/105164575/e2b8834e-d61c-4d9a-9adb-9162a80489a9">

14. 用ljust(8,"0")在字符串左侧对齐的情况下对右侧进行补位；rjust()反之
15. int("str", base=16) 把str视为16进制并转换为10进制的整数。 转为二进制：bin()[2:]；转为八进制：oct()；转为十六进制：hex()
16. 删除的四种操作：del listname[start : end]； listname.pop(index)； remove(值)--只能删除list中的第一个； clear()--清空list
17. print(str, end=" ") 让下一次的print内容和此次以" "相连
18. 暴力求质因数（用试除法求一个数所有为质数的因子），时间复杂度为O(n)： <img width="192" alt="屏幕截图 2023-12-15 105253" src="https://github.com/Jonas9172/Notes/assets/105164575/978410a8-8f81-4e38-981b-bbfef8963add">

19. 优化后：<img width="231" alt="屏幕截图 2023-12-15 111953" src="https://github.com/Jonas9172/Notes/assets/105164575/6e4d2356-746d-42d2-b017-3a8233407c0d">

20. 浮点数：float()
21. 取整：<img width="473" alt="屏幕截图 2023-12-15 113603" src="https://github.com/Jonas9172/Notes/assets/105164575/464f111d-4825-4d79-82e4-914bb40af856">
22. ord() -- 返回对应的 ASCII 数值
23. continue跳出本次循环；break跳出整个for循环
24. isinstance(element, int) 判断element是否是某个类型
25. 判断字符串里是否全是数字--str.isdigit(); 判断字符串里是否全是字母--str.isalpha(); 判断字符串里是否全是数字或字母--strstr.isalnum()

