# eecs182-homework-0-solved
**TO GET THIS SOLUTION VISIT:** [EECS182 Homework 0 Solved](https://www.ankitcodinghub.com/product/eecs182-solved-9/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116531&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EECS182 Homework 0 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
1. Surveys

Below we have attached a google form link for you to fill out. This is a demographic survey that will help us understand more about you and your background. Getting to know you will only help us improve your experience in CS182/282.

(a) Survey Form

2. Course Policies

Go to the course website and read the course policies carefully. Leave a followup in the Homework 0, Question 2 thread on Ed if you have any questions. Are the following situations violations of course policy? Write “Yes” or “No”, and a short explanation for each.

(a) Alice and Bob work on a problem in a study group. They write up a solution together and submit it, noting on their submissions that they wrote up their homework answers together.

(b) Carol goes to a homework party and listens to Dan describe his approach to a problem on the board, taking notes in the process. She writes up her homework submission from her notes, crediting Dan.

(d) Frank is having trouble with his homework and asks Grace for help. Grace lets Frank look at her written solution. Frank copies it onto his notebook and uses the copy to write and submit his homework, crediting Grace.

(e) Heidi has completed her homework. Her friend Irene has been working on a homework problem for hours, and asks Heidi for help. Heidi sends Irene her photos of her solution through an instant messaging service, and Irene uses it to write her own solution with a citation to Heidi.

3. Gradient Descent Doesn’t Go Nuts with Ill-Conditioning

Suppose instead of inverting the matrix we decide to use gradient descent instead. We run k iterations of gradient descent to minimize the loss starting from w0 = 0. We use a learning rate η which is small enough that gradient descent cannot possibly diverge for the given problem. (This is important. You will need to use this.)

The gradient-descent update for t &gt; 0 is:

w .

We are interested in the error . We want to show that in the worst case, this error can grow at most linearly with iterations k and in particular ∥wk − w∗∥2 ≤ kηα∥y∥2 + ∥w∗∥2.

i.e. The error cannot go “nuts,” at least not very fast.

For the purposes of the homework, you only have to prove the key idea, since the rest follows by applying induction and the triangle inequality.

Show that for t &gt; 0,∥wt∥2 ≤ ∥wt−1∥2 + ηα∥y∥2.

(HINT: What do you know about (I − ηF⊤F) if gradient descent cannot diverge? What are its eigenvalues like? Use this fact.)

4. Regularization from the Augmentation Perspective

Assume w is a d-dimensional Gaussian random vector w ∼ N(0,Σ) and Σ is symmetric positive-definite. Our model for how the {yi} training data is generated is

y = w⊤x + Z, Z ∼ N(0,1), (1)

where the noise variables Z are independent of w and iid across training samples. Notice that all the training {yi} and the parameters w are jointly normal/Gaussian random variables conditioned on the training inputs {xi}. Let us define the standard data matrix and measurement vector:

 T x1

xT2 ,

X =  …  

  xTn   y1

y2

y =  … .



  yn

In this model, the MAP estimate of w is given by the Tikhonov regularization counterpart of ridge regression: w = (X⊤X + Σ−1)−1X⊤y, (2) b

In this question, we explore Tikhonov regularization from the data augmentation perspective.

Define the matrix Γ as a d × d matrix that satisfies Γ⊤Γ = Σ−1. Consider the following augmented design matrix (data) Xˆ and augmented measurement vector yˆ:

, and yˆ ,

where 0d is the zero vector in Rd. Show that the ordinary least squares problem

argmin w

has the same solution as (2).

(HINT: Feel free to just use the formula you know for the OLS solution. You don’t have to rederive that. This problem is not intended to be hard or time consuming.)

5. Vector Calculus Review

(a) Show ∂∂x(xTc) = cT

(b) Show xT

(c) Show

(d) Show

(e) Under what condition is the previous derivative equal to 2xTA?

6. ReLU Elbow Update under SGD

In this question we will explore the behavior of the ReLU nonlinearity with Stochastic Gradient Descent

(SGD) updates. The hope is that this problem should help you build a more intuitive understanding for how SGD works and how it iteratively adjusts the learned function.

We want to model a 1D function y = f(x) using a 1-hidden layer network with ReLU activations and no biases in the linear output layer. Mathematically, our network is

where x,y ∈ R, b ∈ Rd, W(1) ∈ Rd×1, and W(2) ∈ R1×d. We define our loss function to be the squared error,

.

For the purposes of this problem, we define the gradient of a ReLU at 0 to be 0.

(a) Let’s start by examining the behavior of a single ReLU with a linear function of x as the input,

.

Notice that the slope of ϕ(x) is w in the non-zero domain.

We define a loss function . Find the following:

(i) The location of the ‘elbow’ e of the function, where it transitions from 0 to something else. (ii) The derivative of the loss w.r.t. ϕ(x), namely

(iii) The partial derivative of the loss w.r.t. w, namely

(iv) The partial derivative of the loss w.r.t. b, namely

(b) Now suppose we have some training point (x,y) such that ϕ(x)−y = 1. In other words, the prediction ϕ(x) is 1 unit above the target y — we are too high and are trying to pull the function downward.

Describe what happpens to the slope and elbow of ϕ(x) when we perform gradient descent in the following cases:

(i) ϕ(x) = 0.

(ii) w &gt; 0, x &gt; 0, and ϕ(x) &gt; 0. It is fine to check the behavior of the elbow numerically in this case.

(iii) w &gt; 0, x &lt; 0, and ϕ(x) &gt; 0.

(iv) w &lt; 0, x &gt; 0, and ϕ(x) &gt; 0. It is fine to check the behavior of the elbow numerically in this case.

Additionally, draw and label ϕ(x), the elbow, and the qualitative changes to the slope and elbow after a gradient update to w and b. You should label the elbow location and a candidate (x,y) pair. Remember that the update for some parameter vector p and loss ℓ under SGD is

p′ = p − λ∇p(ℓ), λ &gt; 0.

(c) Now we return to the full network function fˆ(x). Derive the location ei of the elbow of the i’th elementwise ReLU activation.

(d) Derive the new elbow location e′i of the i’th elementwise ReLU activation after one stochastic gradient update with learning rate λ.

7. Using PyTorch to Learn the Color Organ

One of the greatest recent developments in easy-to-use software packages is the easy availability of automatic differentiation. Although the underlying technology had been well established for over four decades (originally developed for control and scientific modeling applications in the context of differential equations), today packages like PyTorch expose this power to us in an easy to use way. This means that we as human engineers no longer have to worry about manually computing derivatives for any purpose other than taking exams, doing proofs, and basically learning material. In practical applications, the computer can do it for us without any bugs. As students whose careers will span the next four decades, we want you to consider this as a part of your engineering inheritance so that you can use it freely without thinking of it as being any more special than a hash table.

This problem and the accompanying Jupyter Notebook color_organ_learning.ipynb will show you how this power can be used to learn the value for the resistors in the color organ simply by having examples of where you want the LEDs to be on and off. This will build on the use of PyTorch that you will have seen in discussion.

(NOTE: A “color organ” is a fun hardware lab exercise where students build an analog circuit where different LEDs light up depending on whether a particular tone is a low frequency, high frequency, etc. This shows the intimate connection between filters and classifiers. Students in 16B often have to build such a circuit and manually tune it so that it recognizes the right kind of tones.)

(a) Let’s start with an example low pass filter where, given a desired transfer function, we can determine a resistor value manually for our predicted transfer function such that the transfer functions match. In the interactive plot, we show a transfer function of a desired low pass filter (orange dotted line); we want to design our circuit (given a fixed capacitor value) such that predicted transfer function (blue solid line) is equivalent. For the following problems, we provide a function evaluate_lp_circuit that evaluates the transfer function magnitude given a resistor value. Note that these functions use torch functions instead of numpy as we will typically use torch tensors instead of numpy arrays in this notebook for training. Use the slider to find a resistor value such that the predicted and desired transfer functions match and report the resistor value.

The use of torch tensors instead of numpy arrays allows the package to do the bookkeeping behind the scenes that allows derivatives to be easily calculated. This will be important in later parts.

(b) Now, suppose that instead of seeing the entire transfer function that we want to match, we are only given some data about which frequencies lie in the pass band (i.e., which frequencies cause the LED on our color organ to be lit). Again, we can determine a resistor value manually. In the interactive plot, we show a transfer function of a low pass filter with its corresponding cutoff frequency. The table shows the desired behavior (red bars denote that the LED is on for a given frequency while black bars denote that the LED is off); we want to design the circuit such that the LEDs light up in the same way. Use the slider to find a resistor value and corresponding cutoff frequency such that the predicted lights match the desired lights and report the corresponding resistor value and cutoff frequency.

(c) Assume that we are able to query the desired transfer function directly (i.e., we can play a frequency and record the magnitude of the output). Can we learn the resistor value in the low pass circuit directly from this data (instead of manually designing the circuit as you did in the first part)?

The code for this part creates a model of the low pass filter in PyTorch, generates training data, and then trains the circuit using mean squared error loss until convergence (i.e., loss or gradients are very small) or the maximum number of training steps are reached. Here, we use the torch.autograd.grad function to automatically find the derivative of the loss with respect to the input (the resistor value of the low pass circuit). All we need to do is input the transfer function and define the loss!

The plots show how the transfer function of the learned circuit evolved during training, the loss surface, the derivative with respect to each training point at each iteration, and the total gradient at each training iteration. Note that the learned transfer function and resistor value change more slowly when the gradient is small, and more quickly when the gradient is large, but if we continue to iterate, we will converge to a local minimum in the loss surface. Try initializing the circuit with different resistor values (there is an optional argument for the circuit class constructor; if you leave it blank it will be initialized to a random value between 0 and 1000). How long does the circuit take to converge with different initializations? Does it converge to the same value you found in the previous parts? Try changing the learning rate (this parameter controls how far we step at each iteration in the direction of the negative gradient). What values of lr cause training to diverge? What values cause the circuit to converge quickly?

(d) Now, using the same loss function as in the previous part, let’s try to learn the resistor value using only the binary data we have (LED on the color organ being on or off). Change the code to use binary data instead of the transfer function magnitudes. What is the learned resistor value? (Hints: Some potentially useful constants are defined at the start of the notebook. The loss function must take in floats (not boolean values).)

(e) What happened in the previous part? We did not converge to the same resistor value as we did in the previous part. Why? Because in trying to fit to the binary data, we can see that the positive and negative samples in our training data are pulling the resistor value in opposite directions (bottom left plot) and the final solution we end up at is where this “tug of war” situation achieves a balance. This balance need not end up where we would like it to. Can we fix this problem by adjusting the loss function? Adjust the loss function such that the negative samples (where the LEDs should be off) are demanding an output other than 0 in a way that helps get the balance to end up where you want it. Can you find a loss function that yields the same resistor value as when training with the full transfer function?

(f) Let’s use what we learned in the previous parts to also learn our high pass filter from binary data. Input the high pass filter transfer function into the high pass circuit module (use the same loss_fn as you found in the previous part) and fill in the code that updates the value of the resistor at each training step (Hint: use the low pass filter as an example). What is the learned resistor value?

(g) Now let’s extend the problem to a circuit with multiple parameters and learn both resistors for a band pass filter. Input the band pass filter transfer function into the band pass circuit module. (Hint: you can use the functions previously defined for high and low pass circuits). Then complete the code for updating both resistors (note that torch.autograd.grad returns a tuple of gradients corresponding to each input). What are the learned resistor values? What happens if the initial resistor values are far from the solution? Try training with initial resistor values of 900 Ohms each. Does the circuit converge within the maximum number of training steps? How much longer does it take to converge? How large are the gradients and what does the loss surface look like when the resistor values are very far from the correct solution?

(h) Now that we have tried learning the resistor values for a band pass filter directly from binary data, let’s explore a different parametrization of our filter: the Bode Plot. Let’s again start by trying to learn cutoff frequencies from samples of a transfer function using two ReLU functions. Run the code. Does the resulting Bode plot match what you would draw given the underlying transfer function data? Do the cutoff frequencies match those corresponding to the resistor values that were found in the previous part?

(i) Let’s put all of these together to try and learn a color organ circuit from a low pass, high pass, and band pass circuits. Here, we train with a vector of size (3, n) which is one-hot encoded, meaning that for each of the n datapoints, one of the three values is 1 and the rest are 0. This encoding corresponds to our LEDs being on or off for one and only one of the three filters at a given frequency. Train the color organ circuit and verify that the learned resistor values match those from the previous parts. Try initializing the resistors to different values; does it take longer or shorter to learn the entire color organ circuit than a single one of the filters (low pass, high pass, or band pass)?

The final part of the notebook visualizes the computation graph that PyTorch is using to compute the derivatives of each transfer function with respect to the resistor values. See if you can match each operation in the graph to the transfer functions for each filter. Hopefully, this graph gives you an idea of how PyTorch can determine the partial derivatives that you have been using throughout the notebook. Congratulations, you now know how to use the considerable power of PyTorch to automatically differentiate arbitrary functions and find the corresponding local minima of these functions via gradient descent!

8. Homework Process and Study Group

We also want to understand what resources you find helpful and how much time homework is taking, so we can change things in the future if possible.

(a) What sources (if any) did you use as you worked through the homework?

(b) If you worked with someone on this homework, who did you work with?

List names and student ID’s. (In case of homework party, you can also just describe the group.)

(c) Roughly how many total hours did you work on this homework? Write it down here where you’ll need to remember it for the self-grade form.

Contributors:

• Yaodong Yu. • Anant Sahai.

• Saagar Sanghavi.

• Josh Sanz.

• Michael Danielczuk.

• Kumar Krishna Agrawal.
