Leetcode周賽 Biweekly Contest 86 紀錄

看那666,1666名 大概是少數我有機會拿獎品的比賽了巴

![image](https://github.com/ga544523/contest/blob/main/Leetcode%E5%91%A8%E8%B3%BD%20Biweekly%20Contest%2086/%E6%93%B7%E5%8F%96.PNG?raw=true)

遺憾最後力道沒控制好 還會有下次嗎 
![image](https://github.com/ga544523/contest/blob/main/Leetcode%E5%91%A8%E8%B3%BD%20Biweekly%20Contest%2086/%E6%93%B7%E5%8F%961.PNG?raw=true)


T1: 2395. Find Subarrays With Equal Sum
https://leetcode.com/problems/find-subarrays-with-equal-sum/

題意:給你一個陣列問是否可以找到兩組相鄰的數加起來相同

思路：按照題意即可


T2: 2396. Strictly Palindromic Number
https://leetcode.com/problems/strictly-palindromic-number/

題意:一個整數n被叫做嚴格迴文,只有在他以2到n-2為進治表示後都是回文
給你一個整數n,問是否是嚴格迴文

思路：嚴格到沒有數字能達成.直接回傳false即可 什麼垃圾題目

T3: 2397. Maximum Rows Covered by Columns
https://leetcode.com/problems/maximum-rows-covered-by-columns/

題意:給你一個大小m x n只有1/0的陣列 和一個整數numSelect,
選擇numSelect個coloum,問最多能有幾個把選中的coloum排除後,該列全是0的row

思路：可以想成把選中的coloum的元素變0在作計算,數據範圍小,直接暴力回朔即可

T4: 2398. Maximum Number of Robots Within Budget
https://leetcode.com/problems/maximum-number-of-robots-within-budget/

題意:給你n個機器人分別有n個充電時間和n個執行耗費問最多能有幾個"連續"的機器人
能被啟動,而總耗費不超過預算budget 總耗費=max(選中的機器人中最大的充電時間)+選中的機器人數*選中的機器人執行耗費總和 

思路：看到連續後很明顯的two pointer 選中的最大充電時間可以用像multiset這類的資料結構來維護
