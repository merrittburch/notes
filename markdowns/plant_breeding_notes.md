### Some helpful notes for plant breeding related topics


#### 



##### From Lynch and Walsh 1998
__Difference between IBD and IBS__
- all measures of relatedness are based upon the concept og __idendity by descent (IBD)__. Genes that are identiicial by descent are direct descendants of a specific gene carried i some ancestral individual.
- Two genes that have identical nucleotide sequences but have descended from different copies in the refernce population are identical by state but not by descent.
- Genes that are identical by descent are necessarily identical by state, barring mutation
- Individuals that contain pairs of alleles that are IBD aree said it be __inbred__.

__Intro to Matrix Algebra and Linear Models__

Standard regression model
- Depending on the casual connections between two variables, $x$ and $y$, their true relationsip may be linear or non-linear. However, regardless of the true pattern of association, a lineara model can always serve as a first approximation

$$y=\alpha+\beta x+e$$

Where:
$\alpha$ is the y-intercept
$\beta$ is the slop of the line (or the regression coefficiient)
$e$ is the residual error

Letting:
$$\hat y= \alpha + \beta x$$

- be the value of $y$ predicted by the model, then the residual error is the deviation between the observed and predicted $y$ value, i.e., $e = y - \hat y$.
- When info on $x$ is used to predict $y$, $x$ is referred to as the predictor or independent variable and y as the response or dependent.
- The objective of linear regression analysis is to estimate the model parameters, $\alpha$ and $\beta$, that give the "best-fit" for the joint distribution of $x$ and $y$. The true parameters $\alpha$ and $\beta$ are only obtainable if the entire population is sampled


Standard multiple regression formula
$$y = \alpha + \beta_1z_1+\beta_2z_2+...+\beta_nz_n+e$$
Where:
$y$ is the response variable
$z_i$ is the predicitor (or explanitory) variable usued to predict the value of the response variable
$y, z_1, ..., z_n$ are observed measurees
$\alpha, \beta_1,...,\beta_n$ are constants to be measured
$e$ is the residual error --> is the deviation between the observed and fitted value of $y$
- Similar to a simple linear regression ($y= \alpha + \beta x + e$), except that $y$ iis now a function of $n$ predictor variables, rather than one
- No assumption on the relationship between $y$ and $z_1,...,z_n$, it simply gives the best linear apprroximation between observations

What's bookmarked for reading later on?
- pg 49, additive genetic varaiance (ch. covariance, regression, and correlation)
- pg 444 detected marker effects (mapping QTLs: inbred line crossing)
- pg 454 marker approximations, likelihood ratio (mapping QTLs)
- pg 784 maximum likelihood estimates of variance components in the general mixed model (variance comoponent estimation)

