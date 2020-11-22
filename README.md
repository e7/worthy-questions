收集比较有价值或者有趣的问题<br>
**水平有限，错漏之处，欢迎指正**

* 在浏览器中键入<span>https://www.test.com</span>回车后可能涉及到哪些协议？（计算机网络）
  <details><summary>参考答案</summary>DNS协议（UDP或TCP），SSL握手协议，HTTP协议（目前主流TCP），如果目标机器不可访问可能会收到ICMP差错报文</details>
 
* 快速排序最坏时间复杂度是多少？什么情况下会导致最坏情况？如何改善？（算法）
  <details>
  <summary>参考答案</summary>
    O(n^2)，凡是会导致划分一边倒的输入都会出现最坏情况，比如正序、逆序或者全部元素相同<br><br>
    可从以下几点考虑改善：<br>
    1. pivot的选择，三数中值法，对于大数组可以取更多的数求中值<br>
    2. 双指针遍历减少交换次数<br>
    3. 使用更多的分区，包括等于pivot的元素单独分区（可避免重复元素的情况），甚至使用多个pivot，对于分区元素数目比较小的（20以内）不再划分而采用插入排序<br>
    4. 对于输入本来就很小的数组，直接采用插入排序<br>
    5. 防止递归过深导致栈溢出，比如尾递归或者模拟栈
  </details>
  
* 如何在高丢包率的网络环境下尽可能快地传输文件？（ex：如何模拟高丢包率网络环境？）（算法、网络）

* 一台安装有Linux系统的计算机，请描述从按下电源到启动init进程的过程。（操作系统）

* Linux是如何将逻辑地址转换为物理地址的？（操作系统）

* C++中如何实现判断一个类是不是另一个类的子类（要求编译时关闭RTTI）？（C++）
  <details>
  <summary>参考答案</summary>
   dGVtcGxhdGUgPHR5cGVuYW1lIGRlcml2ZWQsIHR5cGVuYW1lIGJhc2U+IGNsYXNzIElzRGVyaXZlZCB7CiAgICAvKiB0eXBl5Li65peg55So5qih5p2/5b2i5Y+C77yM5Zug5Li65bWM5aWX57G75qih5p2/5Y+q6IO95YGP54m55YyWICovCnByaXZhdGU6CiAgICB0ZW1wbGF0ZSA8aW50IG4sIHR5cGVuYW1lIGlnbj12b2lkPiBjbGFzcyBDU2l6ZUJveCB7CiAgICBwcml2YXRlOgogICAgICAgIENTaXplQm94PG4tMSwgaWduPiBib3gxOwogICAgICAgIENTaXplQm94PG4tMSwgaWduPiBib3gyOwogICAgfTsKICAgIHRlbXBsYXRlIDx0eXBlbmFtZSBpZ24+IGNsYXNzIENTaXplQm94PDAsIGlnbj4gewogICAgcHJpdmF0ZToKICAgICAgICBjaGFyIGM7CiAgICB9OwogICAgQ1NpemVCb3g8MD4gQ2hlY2soYmFzZSBjb25zdCopIGNvbnN0OwogICAgQ1NpemVCb3g8MT4gQ2hlY2soLi4uKSBjb25zdDsKIApwdWJsaWM6CiAgICAvKiDmo4DmtYvnu6fmib/lhbPns7vvvIznnJ/ooajnpLrnu6fmib/lhbPns7vmiJDnq4sgKi8KICAgIGNvbnN0ZXhwciBib29sIG9wZXJhdG9yICgpKHZvaWQpIGNvbnN0IHsKICAgICAgICByZXR1cm4gKAogICAgICAgICAgICBzaXplb2YoQ2hlY2soc3RhdGljX2Nhc3Q8YmFzZSBjb25zdCo+KG51bGxwdHIpKSkKICAgICAgICAgICAgPT0KICAgICAgICAgICAgc2l6ZW9mKENoZWNrKHN0YXRpY19jYXN0PGRlcml2ZWQgY29uc3QqPihudWxscHRyKSkpCiAgICAgICAgKTsKICAgIH0KICAgIG9wZXJhdG9yIGJvb2wodm9pZCkgY29uc3QgewogICAgICAgIHJldHVybiAoKnRoaXMpKCk7CiAgICB9Cn07
  </details>

* 对于一台2^n位的计算机，计算一个2^n位长度的整型变量中二进制位为1的数目（要求时空复杂度O(1)）。（算法）
 
* 未完待续。。。
