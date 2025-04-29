# machine-learning-exercise-10-solved
**TO GET THIS SOLUTION VISIT:** [Machine Learning Exercise 10 Solved](https://www.ankitcodinghub.com/product/machine-learning-labs-4/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;110205&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Machine Learning Exercise 10 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
Security and robustness of machine learning models have been often overlooked, for the sake of greater performance and accuracies. However, it is usually quite easy for an adversary to create inputs (e.g., images) that fool an ML model into thinking they are something else, while preserving the semantic content of the original input.

The goal of this exercise is to better understand how to generate adversarial examples in practice, use them in adversarial training to get a more robust model, and to check what adversarial examples correspond to in the simple case of linear models.

Problem 1 (Adversarial training for linear models):

It can be often very insightful to analyze what a method corresponds to in a simple setting of linear models.

Assume we have input points xi ∈ Rd and binary labels yi ∈ {−1,1}. Let ` be a monotonically decreasing marginbased loss function, for example the hinge loss `(z) = max{0,1 − z} or logistic loss `(z) = log(1 + exp(−z)) that you have seen before.

Consider the adversarial training objective for a linear model f(x) = w&gt;x with respect to `2 adversarial perturbations:

n min .

w

• Find a closed-form solution of the inner maximization problem and the minimizer .

• In case of the hinge loss, `(z) = max{0,1−z}, what is the connection between `2 adversarial training and the primal formulation of the soft-margin SVM?

• What if instead of `2 adversarial training, we performed `∞ adversarial training, how would the solution of the inner maximization problem change? Does the maximizer for `∞-perturbations resemble the Fast Gradient Sign Method (FGSM)?

Problem 2 (Adversarial training on MNIST):

In this problem you will:

1. Learn how to make small modifications in handwritten digit images that result in dramatic errors by ML models. However, humans can still recognize these adversarial examples.

2. Implement a simple defense against this attack.

Setup It is the easiest to run this notebook in Google Colab. You can make use of a free GPU there to train the models faster. If you want to run the notebook locally, you can also use template/ex10.ipynb. However, expect to have much longer running time if you don’t have GPUs.

1. Open the colab link for the lab 10:

https://colab.research.google.com/github/epfml/ML_course/blob/master/labs/ex10/template/ex10.ipynb

2. To save your progress, click on “File &gt; Save a Copy in Drive” to get your own copy of the Notebook.

3. Click ‘connect’ on top right to make the notebook executable (or ‘open in playground’)

4. Start solving the missing parts.
