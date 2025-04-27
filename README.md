# ece566-homework-2-solved
**TO GET THIS SOLUTION VISIT:** [ECE566 Homework 2 Solved](https://www.ankitcodinghub.com/product/ece566-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;122137&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ECE566 Homework 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
&nbsp;

Write a computer program to evaluate the generalization error (GE), model prediction error (ME) and training error (TE) for the k-nearest neighbors learning approach. Use provided k-NN Python code. Learning model:

In the k-nearest neighbors learning approach guess output, Yˆk , as:

Yˆk fk x Yitraning

where N xk ( ) is a set of k nearest neighbors of x within the observed (training) data. Data model:

Training data

Let us define observed (training) data model.

• First generate N traning =50 uniformly spaced feature samples in the interval from zero to one. That is xi = i x iΔ , = 0,..,N traning −1 where Δx=1N traning .

• Next generate N traning =50 noise samples,ni , as Normally distributed random process with a zero mean and 0.1 standard deviation.

(Hint: Use npr.normal nympy function)

Now the observed noisy data can be calculated as:

Yitraning = f x( i ) +ni, i =1,..,N traning where f x( )i =sin 2( πxi ).

Testing data

• To generate the testing data,Yjtesting, j =1,..,Ntesting , the same procedure described above can be used where N=300.

Evaluation:

The generalization error can be approximately calculated as:

GE k = E⎡⎢

 ( ) ⎣ k ⎥⎦ N testing j=1 (Yjtesting − fˆk (xtjesting ))2 ,

the model prediction error as:  ( ) ⎣ k ⎥⎦ N testing j=1 (xtjesting )− fˆk (xtjesting ))2 ,

ME k = E⎡⎢

and the training error as:

TE k (Yjtraning − fˆk (xtraningj ))2 .

N j=1

Report:
