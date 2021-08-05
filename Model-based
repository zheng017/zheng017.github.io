Whether a model is parsimonious is judged by the number of parameters.

**LCM**: the variables are assumed to be conditionally independent knowing the latent cluster; data are supposed to be drawn independently from a mixture of $g$ multivariate multinomial distributions

$p(x;\theta)=\sum_{k=1}^g \pi_k p(x;\alpha_k)$

$p(x;\alpha_k)=\prod_{j=1}^d p(x^j;\alpha_k)=\prod_{j=1}^d \prod_{h=1}^{m_j} (\alpha_k^{j h})^{x^{j h}}$

with $\theta=(\pi_1,\dots,\pi_g,\alpha_1,\dots,\alpha_g)$ where $\alpha_k=(\alpha_k^{j h};j=1,\dots,d;h=1,\dots,m_j)$ , $\alpha_k^{j h}$ denotes the probability that variable $j$ has level $h$ is the object is in cluster $k$ ; $\pi_k>0, \sum_{k=1}^g \pi_k=1, \alpha_k^{j h}>0, \sum_{h=1}^{m_j} \alpha_k^{j h}=1$.

numbers of parameters: $\nu=(g-1)+d\sum_{k=1}^g (m_j-1)$.

identifiability: generically identifiable



**intra-class independence of blocks**: conditionally on class $k$, variables are grouped into $B_k$ independent blocks

$p(x;\sigma,\theta)=\sum_{k=1}^g p(x;\sigma_k,\theta_k)$

$p(x;\sigma_k,\theta_k)=\prod_{b=1}^{B_k} p(x^{\{k b\}};\theta_{k b})$

The interactions between variables of different blocks will be zero and those between variables of the same block can be modeled by the specific distribution of the block. The limiting case of this model where $B_k=d$ for each class is equivalent to the latent class model with the conditional independence assumption.

identifiability: The generic identifiability of the mixture model with conditionally independent blocks follows, under specific constraints by assuming that the distributions of each block is itself identifiable.

**intra-block parsimonious distribution**

The resulting conditional correlated model is also defined as a block model extension of the latent class model where the distribution inside the block is modeled by the bi-component mixture.

The goal is to define a parsimonious distribution for each block that takes into account the dependency between variables. Furthermore, the parameters of the distribution inside the block must be meaningful for the practitioner.

**maximum dependency distribution**

