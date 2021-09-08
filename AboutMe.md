# Rehana Naguru

I am from India. I worked as an Lecturer in my college,and I had experiance in TATA Consultancy services. I love reading books and I enjoy coding.

 ***[Rehana Naguru](Rehana_naguru.jpg)*** 

 ---

 ## Tasty Foods 

There are many delicious foods one has to try. Hash Browns are the quick breakfast. India's famous Chicken Biryani is the flavourful rice with tender chicken, that every one must try. Caramel Macchiato is the relaxing coffee. Crab Rangoon is the apt choice for chinese food lovers. Funnel Cake is the yummy snack. Following is the list of good foods, their location and price:

   | Food/Drink | Location | Price | 
   | :---:      |  :---:   |:---:  |
   | Hash Browns | Dunkin Donuts | $1.29 |
   | Chicken Biryani  | Indian Restaurants | $16.00 |
   | Caramel Macchiato | Starbucks | $3.75 |
   | Crab Rangoon | Chinese Restaurants | $4.00 |
   | Funnel Cake | Lees Kitchen, Philadelphia | $9.00 | 

---

## My Favourite Quotes

Quotes are the best lines which will give inspiration at all times. A quote can change a life, if you follow. Below are my all time best quotes:

>Never..Never..Never Quit
>> Author is *Winston Churchill* , This is the best quote. To achieve Success first we have to try , if we quit no success will follow. 

>To shine like a sun, first you have to burn like a sun. ~ *A.P.J Abdul Kalam* 

>Nothing is impossible. The word itself says I'm possible. ~ *Audrey Hepburn*

---

## Pascal's Triangle

>Pascal’s triangle is a triangular array of the binomial coefficients. Number of entries in every line is equal to line number. For example, the first line has “1”, the second line has “1 1”, the third line has “1 2 1”,.. and so on. Every entry in a line is value of a Binomial Coefficient. 

Pascal's Traingle <https://www.geeksforgeeks.org/pascal-triangle/>
 


```
const int maxn = ...;
int C[maxn + 1][maxn + 1];
C[0][0] = 1;
for (int n = 1; n <= maxn; ++n) {
    C[n][0] = C[n][n] = 1;
    for (int k = 1; k < n; ++k)
        C[n][k] = C[n - 1][k - 1] + C[n - 1][k];
}
```
Pascal's Triangle Code <https://cp-algorithms.com/combinatorics/binomial-coefficients.html>




