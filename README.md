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
------------------------------------------------------------------------------------------------------------------------------------
199 X 199 |3X3|
197X	197|3X3|
195X	195|3X3|
193	X193|3X3|
191	X191|3X3|
189	X189|3X3|

187	X187|3X3|
185	X185|3X3|
183	X183|3X3|
181X	181|3X3|
179	X179|3X3|
177	X177|3X3|
175	X175|3X3|
173	X173|3X3|
171	X171|3X3|

169X	169|3X3|
167	X167|3X3|
165	X165|3X3|
163	X163|3X3|
161	X161|3X3|
159	X159|3X3|
157	X157|3X3|
155X	155|3X3|
153X	153|3X3|
151	X151|3X3|
149	X149|3X3|
147X	147|3X3|
145	X145|3X3|

143	X143|3X3|
141X	141|3X3|
139	X139|3X3|
137X	137|3X3|
135X	135|3X3|
133X	133|3X3|
131X	131|3X3|
129	X129|3X3||3X3|
127X	127|3X3|

125X	125|3X3|
123	X123|3X3|
121	X121|3X3|
119	X119|3X3|
117	X117|3X3|
115	X115|3X3|
113	X113|3X3|
111	X111|3X3|
109	X109|3X3|

107X	107|3X3|
105X	105|3X3|
103	X103|3X3|
101X	101|3X3|
99X	99|3X3|
97X	97|3X3|
95X	95|3X3|
93X	93|3X3|

91X	91|3X3|
89X	89|3X3|
87X	87|3X3|
85X	85|3X3|
83X	83|3X3|
81X	81|3X3|
79X	79|3X3|
77X	77|3X3|

75X	75|3X3|
73X	73|3X3|
71X	71|3X3|
69X	69|3X3|
67X	67|3X3|
65X	65|3X3|
63X	63|3X3|
61X	61|3X3|
59X	59|3X3|
57X	57|3X3|
55X	55|3X3|

53X	53|3X3|
51X	51|3X3|
49X	49|3X3|
47	X47|3X3|
45	X45|3X3|
43X	43|3X3|
41	X41|3X3|
39X	39|3X3|
37X	37|3X3|
35X	35|3X3|
33X	33|3X3|
31X	31|3X3|

29X	29|3X3|
27X	27|3X3|
25X	25|3X3|
23X	23|3X3|
21X	21|3X3|
19X	19|3X3|
17X	17|3X3|
15X	15|3X3|
13X	13|3X3|
11X	11|3X3|
9	X9|3X3|
7	X7|3X3|
5	X5|3X3|

3	X3|3X3|

1	X1|3X3|


