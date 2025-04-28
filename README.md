# csci111-lab-2-solved
**TO GET THIS SOLUTION VISIT:** [CSCI111 Lab 2 Solved](https://www.ankitcodinghub.com/product/csci-111-lab-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116898&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI111 Lab 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
File names: Names of files and variables, when specified, must be EXACTLY as specified. This includes simple mistakes such as capitalization.

The editor: Running programs in the shell is good for small tasks and makes a good replacement for a calculator. However, if we’re going to write long programs we need to write the program out and save it in a file. For this we use the IDLE editor.

In the menu bar of the IDLE shell, click on File → New .

A new window will open up with the title Untitled .

Use File → Save to save your file. Unless you did this for lab01, make a new folder in your home directory, or your Box directory, called CSCI111Labs

Make a new folder in CSCI111Labs called lab02 Finally, save the file as sphere.py

The problems: The problems all come from exercises for chapter 2 of the text, however you are required to solve the problems in a general way using functions. You will turn in three modules: sphere.py, wholesale.py, and home.py sphere.py: In the file saved as sphere.py:

The volume of a sphere with radius r is .

Use the IDLE shell to find the volume of a sphere with radius 5.

In the sphere.py file open in your editor window, define a function sphere. When you run your file, it will print no output, but the sphere function will be defined so as to print a message like this:

&gt;&gt;&gt; sphere(5)

The volume of a sphere of radius 5 is 523.5987755982989

1

2

Check to make sure your function got the same value you did in the IDLE shell.

wholesale.py: Save a new file with the name wholesale.py

Suppose the cover price of a book is $24.95, but bookstores get a 40% discount. Shipping costs $3 for the first copy and 75 cents for each additional copy.

Use the IDLE shell to find out the total wholesale cost for 60 copies. You should get the following price, in pennies:

300+75*59+int(0.4*2495)*60

1

Note that we have assumed the discount discards any fractions of a cent.

Now write three functions with the following headers:

def shipping_cost(n, first_copy, extra_copy):

1

def wholesale_cost(n, cover_price, discount):

1

def total_cost(n, cover_price, discount, first_copy, extra_copy):

1

which do the obvious things, where the total cost is just the sum of the wholesale cost and the shipping cost.

The original problem can now be solved by running the module and then entering in the shell:

print(total_cost(60, 2495, 40, 300, 75))

1

You should get the same answer as before.

Note that the prices are all in pennies and the percentage is a percentage, not a fraction.

Here are some results from my solution to check your work:

&gt;&gt;&gt; total_cost(100, 2495, 40, 300, 75) 107525

&gt;&gt;&gt; total_cost(20, 32595, 25, 100, 50)

164010

&gt;&gt;&gt; total_cost(1000, 195, 10, 100, 5)

24095

1

2

3

4

5

6

home.py: If I leave my house at 6:52 am and run 1 mile at an easy pace (8:15 per mile), then 3 miles at tempo (7:12 per mile) and 1 mile at easy pace again, what time do I get home for breakfast?

Solve the above problem using the shell.

Open a file called home.py and write several appropriate functions to help solve the above problem.

You can make simplifying assumptions, for example that there are only ever two paces, but that each one might be different and for different distances.

Your computations should be in minutes as integers.

Document each function with comments.

Include a print statement at the end of the file that solves the above problem, and then several others.

Requirements: Each of the three files, sphere.py, wholesale.py, and home.py should begin with a comment block with the information like this:

# home.py

# Geoffrey Matthews

# functions to calculate arrival at home

# after running at varying paces

1

2

3

4

5

All programs you hand in should begin with a similar comment block!

Upon completion: Zip your lab02 folder with the three programs, sphere.py, wholesale.py, and home.py and turn in the zipped file to Canvas.

Zipping: You can zip a folder in windows by right-clicking on the folder in the file browser and selecting from the popup menu:

Send to → Compressed (zipped) folder
