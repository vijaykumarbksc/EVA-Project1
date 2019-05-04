# EVA
Assignment 1
**What are Channels and Kernels (according to EVA)?**

**Kernels** : As per EVA , Kernels are **feature** extractors or **3 X 3 matrix** or also called as **filters**  
              


   **Channels** are **similar** Feature Bags.

Let us under stand with the below example .

 We have a Biriyani image( Yummy   :)) .


![](https://www.kannammacooks.com/wp-content/uploads/Tamilnadu-muslim-chicken-biriyani.jpg)












Now Biriyani is made up of many different ingredients as shown below:















 
![Biriyani ](https://www.kannammacooks.com/wp-content/uploads/Tamilnadu-muslim-chicken-biriyani-recipe-ingredients.jpg) 

So here in the image we have separate ingredients which in case of Computer Vision can be said as Channels. Since Channels are collection of similar features. So in this case **all onions combined together is a CHANNEL** ,all tomatoes combined together is a separate channel so on and so forth.






**Kernels** : One **single** **onion** here is like a **kernel** , 
but  all onions combined together forms a channel.

![](https://qph.fs.quoracdn.net/main-qimg-5905bb375bdfa4cbd638eb349066991f) 

For example in the below image all onions combined together forms a Channel.

![](https://www.kannammacooks.com/wp-content/uploads/Tamilnadu-muslim-chicken-biriyani-recipe-spices.jpg) 


Mostly CHANNELS are expected to contain similar information, but we can combine few channels and make a complex channel which may be conceptually similar.

For Example : In below image tomatoes, onions and garlic are mixed together to form a complex channel.

![](https://www.kannammacooks.com/wp-content/uploads/Tamilnadu-muslim-chicken-biriyani-recipe-tomato.jpg)

----------------------------------------------------------------------------------------------------------------------------------------
**Why should we only (well mostly) use 3x3 Kernels?**

 ![](https://thinkjarcollective.com/wp-content/uploads/2012/01/Paul-Freeman1.jpg)
# ????????????? #

Did you mean this ?




































![](https://i.stack.imgur.com/5tp2P.png)

We should use 3x3 Kernels because of below reasons:

1.It is heavily optimized all across the globe its has become a **standard** all across.

Because it is like this:![](https://spiderimg.amarujala.com/assets/images/2018/10/10/750x506/amitabh-bachchan_1539166595.jpeg)













2.The modern  GPU's built today are accelerated  for the optimal performance with  a 3 x 3 kernel.


<img src="https://c8.alamy.com/comp/BCG4P6/modern-computer-graphics-card-on-white-background-BCG4P6.jpg" alt="GPU"
	title="GPU" width="200" height="120" />
<img src="https://c8.alamy.com/comp/BCG4P6/modern-computer-graphics-card-on-white-background-BCG4P6.jpg" alt="GPU"
	title="GPU" width="200" height="120" />
<img src="https://c8.alamy.com/comp/BCG4P6/modern-computer-graphics-card-on-white-background-BCG4P6.jpg" alt="GPU"
	title="GPU" width="200" height="120" />

The most optimised GPU for 3x3 is like Rajnikant. "Master of all trades jack of none."

![](https://akm-img-a-in.tosshub.com/indiatoday/images/story/201811/CS-Rajinikanth-Dec10-1_770.jpeg?1AKWA1FRZoyNYs8HL9s_JZoHm5ySZIW7)


3.It also satisfies the condition that a Kernel should be of Odd number and not even number.It is symmetric.
![](https://study.com/cimages/multimages/16/symmetric_property_2.jpg)

4 It limits the numbers of parameters and reduces the number of calculations that needs to be done . For ex : 4x4 kernel will have 16 numbers to be calculated whereas 3x3 has 9 only.

So less calculations means more savings .
![](http://www.dollarsfromsense.com/wp-content/uploads/2016/02/6793826885_d3b6befb99_b.jpg)
  
