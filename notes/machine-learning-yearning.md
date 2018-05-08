# Machine Learning Yearning





> This diagram shows NNs doing better in the regime of small datasets. This effect is less consistent

## Setting up

> But if the dev and test sets come from different distributions, then your options are less
>
> 1. You had overfit to the dev set.
> 2. The test set is harder than the dev set. So your algorithm might be doing as well as could
> 3. The test set is not necessarily harder, but just different, from the dev set. So what works well on the dev set just does not work well on the test set. In this case, a lot of your work

> If you are trading off N different criteria, such as binary file size of the model \(which is

> If you later realize that your initial dev/test set or metric missed the mark, by all means
>
> There are three main possible causes of the dev set/metric incorrectly rating classifier A
>
> 1. The actual distribution you need to do well on is different from the dev/test sets.
> 2. You have overfit to the dev set.  
>    If you need to track your team’s progress, you can also evaluate your system regularly—say
>
>    once per week or once per month—on the test set. But do not use the test set to make any
>
>    decisions regarding the algorithm, including whether to roll back to the previous week’s
>
>    system. If you do so, you will start to overfit to the test set, and can no longer count on it to
>
>    give a completely unbiased estimate of your system’s performance \(which you would need if
>
>    you’re publishing research papers, or perhaps using this metric to make important business
>
>    decisions\).
>
> 3. The metric is measuring something other than what the project needs to optimize.

#### Takeaways: Setting up development and

> * Choose dev and test sets from a distribution that reflects what data you expect to get in
> * Choose dev and test sets from the same distribution if possible.
> * Choose a single-number evaluation metric for your team to optimize. If there are multiple
> * Machine learning is a highly iterative process: You may try many dozens of ideas before
> * Having dev/test sets and a single-number evaluation metric helps you quickly evaluate
> * When starting out on a brand new application, try to establish dev/test sets and a metric
> * The old heuristic of a 70%/30% train/test split does not apply for problems where you
> * Your dev set should be large enough to detect meaningful changes in the accuracy of your
> * If your dev set and metric are no longer pointing your team in the right direction, quickly

#### Examples of what can be tried to improve the model

> * Get more data: Collect more pictures of cats.
> * Collect a more diverse training set. For example, pictures of cats in unusual positions; cats
> * Train the algorithm longer, by running more gradient descent iterations.
> * Try a bigger neural network, with more layers/hidden units/parameters.
> * Try a smaller neural network.
> * Try adding regularization \(such as L2 regularization\).
> * Change the neural network architecture \(activation function, number of hidden units, etc.\)

> If you choose well among these possible directions, you’ll build the leading cat picture

## Basic Error

> * When you start a new project, especially if it is in an area in which you are not an expert,
> * So don’t start off trying to design and build the perfect system. Instead build and train a
> * Carry out error analysis by manually examining ~100 dev set examples the algorithm
> * Consider splitting the dev set into an Eyeball dev set, which you will manually examine,
> * The Eyeball dev set should be big enough so that your algorithm misclassifies enough
> * If your dev set is not big enough to split this way, just use an Eyeball dev set for manual

[Ng\_MLY01.pdf](https://www.dropbox.com/s/98cxhqe4uvdjz51/Ng_MLY01.pdf?dl=0)

[Ng\_MLY02.pdf](https://www.dropbox.com/s/jowspahz8w6j6w2/Ng_MLY02.pdf?dl=0)

[Ng\_MLY03.pdf](https://www.dropbox.com/s/u9y9j64htoz79gi/Ng_MLY03.pdf?dl=0)
