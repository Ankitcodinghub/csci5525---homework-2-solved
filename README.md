# csci5525---homework-2-solved
**TO GET THIS SOLUTION VISIT:** [CSCI5525 – Homework 2 Solved](https://www.ankitcodinghub.com/product/csci5525-homework-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117046&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI5525 - Homework 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
1. (20 points) Recall that a function K : X ×X 7→ R is a valid kernel function if it is symmetric and positive semi-definite function. For the current problem, we assume that the domain X = R.

(a) (10 points) Let K1,…,Km be a set of valid kernel functions. Show that for any wj ≥ 0,j = 1,…,m, x,x0 ∈ Rp that the function ) is a valid kernel function.

(b) (10 points) Consider the function K(x,x0) = K1(x,x0) + K2(x,x0) where K1 and K2 are valid kernel functions. Show that K is a valid kernel function.

2. (20 points) The SVM classifier can be implemented in either primal or dual form. In this problem, implement a linear SVM in dual form using slack variables. Note, this will be a quadratic program with linear constraints. For this you need an optimizer. Use the optimizer cvxopt which can be installed in your environment either through pip or conda. Refer to the cvxopt document for more details about quadratic programming: https://cvxopt.org/ userguide/coneprog.html#quadratic-programming.

Please submit (a) summary of methods and results report and (b) code:

(a) Summary of methods and results: Briefly describe the approaches used above, along with relevant equations. Also, calculate the train and validation error rates over the 10 folds for each value of C = {10−4,10−3,10−2,0.1,1,10,100,1000}. Report the average train error rate and its associated standard deviation (over the 10 train error rates) and the average validation error rate and its associated standard deviation (over the 10 validation error rates). After running cross validation, choose the value of C which gives the lowest average validation error. Apply the learned model with that value of C to the held out test set and report the error rate on the test set (1 number). Make sure to explain why you chose that value of C beyond that it has the lowest validation error rate.

(b) Code: Submit the file SVM dual.py which contains the function def SVM dual(dataset: str) -&gt; None: where dataset is a string consisting of the name of the dataset and the function does not return anything but must print out to the terminal (stdout) the average train and validation error rates and standard deviations, the optimal value of C, and the test set error rate for the model with the lowest validation error rate.

(i) Linear kernel, (ii) RBF kernel.

Please submit (a) summary of methods and results report and (b) code:

(a) Summary of methods and results: Briefly describe the approaches used above, along with relevant equations. Also, for both (i) and (ii), report the average train and validation error rates and standard deviations (over the 10 folds) for each combination of the hyperparameter values (you choose the values to experiment with – they must be reasonable and you must be able to explain why they are reasonable). After running cross validation, choose the optimal hyperparameter values and apply the learned model with those values to the held out test set and report the error rate on the test set. Make sure to explain why you chose those hyperparameter values.

(b) Code: Submit the file kernel SVM.py which contains the function def kernel SVM(dataset: str) -&gt; None: where dataset is a string consisting of the name of the dataset and the function does not return anything but must print out to the terminal (stdout) the average train and validation error rates and standard deviations, the optimal hyperparameter values, and the test set error rate for the best model.

4. (30 points) In this problem, we consider multi-class classification using SVM. Implement a multi-class SVM using the one vs all strategy. Apply your SVM to the “mfeat” dataset which contains descriptors from MNIST for reducing the data dimensionality.

Split the dataset in the same way as in Problem 2 (80% train, 20% test) and apply k = 10 fold cross validation on the train data to choose to optimal hyperparameters (you must decide on reasonable hyperparameter ranges) for the following kernels:

(i) Linear kernel, (ii) RBF kernel.

Please submit (a) summary of methods and results report and (b) code:

(a) Summary of methods and results: Briefly describe the approaches used above, along with relevant equations. Also, for both (i) and (ii), report the average train and validation error rates and standard deviations (over the 10 folds) for each combination of the hyperparameter values (you choose the values to experiment with – they must be reasonable and you must be able to explain why they are reasonable). After running cross validation, choose the optimal hyperparameter values and apply the learned model with those values to the held out test set and report the error rate on the test set. Make sure to explain why you chose those hyperparameter values.

(b) Code: Submit the file multi SVM.py which contains the function def multi SVM(dataset: str) -&gt; None: where dataset is a string consisting of the name of the dataset and the function does not return anything but must print out to the terminal (stdout) the average train and validation error rates and standard deviations, the optimal hyperparameter values, and the test set error rate for the best model.

Additional instructions: Code can only be written in Python 3.6+; no other programming languages will be accepted. One should be able to execute all programs from the Python command prompt or terminal. Please specify instructions on how to run your program in the README file.

Each function must take the inputs in the order specified in the problem and display the textual output via the terminal and plots/figures should be included in the report.

Your code must be runnable on a CSE lab machine (e.g., csel-kh1260-01.cselabs.umn.edu). One option is to SSH into a machine. Learn about SSH at these links: https://cseit.umn.edu/ knowledge-help/learn-about-ssh, https://cseit.umn.edu/knowledge-help/choose-ssh-tool, and https://cseit.umn.edu/knowledge-help/remote-linux-applications-over-ssh.

Instructions

Follow the rules strictly. If we cannot run your code, you will not get any credit.

• Things to submit

1. hw2.pdf: The report that contains the solutions to Problems 1, 2, 3, and 4 including thesummary of methods and results.

2. dual SVM.py: Code for Problem 2.

3. kernel SVM.py: Code for Problem 3.

4. multi SVM.py: Code for Problem 4.

5. README.txt: README file that contains your name, student ID, email, instructionson how to run your code, any assumptions you are making, and any other necessary details.

6. Any other files, except the data, which are necessary for your code.

Homework Policy. (1) You are encouraged to collaborate with your classmates on homework problems, but each person must write up the final solutions individually. You need to list in the README.txt which problems were a collaborative effort and with whom. (2) Regarding online resources, you should not:

• Google around for solutions to homework problems,

• Ask for help on online,

• Look up things/post on sites like Quora, StackExchange, etc.
