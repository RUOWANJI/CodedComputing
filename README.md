## Large-scale Matrix Multiplication

Coded distributed matrix multiplication for straggler mitigation has received a lot of attention recently. In coded distributed matrix multiplication, a master node wishes to compute the matrix product AB with the help of several worker nodes.
The main idea %in coded distributed matrix multiplication 
is to partition A and B into several smaller submatrices, encode the submatrices using a carefully constructed code into a redundant set of submatrices, and transmit the encoded submatrices to different worker nodes. 
The worker nodes compute the smaller matrix products and return their computation to the master node which combines the results from each worker node to produce the final result.
The code is designed such that the final result can be recovered from a subset of the submatrix products, i.e., the system is resilient to straggling workers which do not return their computation in time.

Robust algorithms for such kind of large-scale distributed matrix multiplication need to address several important factors including 


(i) resilience to straggling workers, typically measured using a recovery threshold, which is the minimum number of workers that need to return their computation; (ii) communication cost - the amount of information that needs to be communicated to the worker nodes; and 
(iii) scalability - the numerical accuracy and implementation complexity of the distributed algorithms.


### Algorithm



```markdown


- Polynomial-Coded Computing
- Random Khatri-Rao-Product Coded Computing(RKRP)



[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/RUOWANJI/CodedComputing/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
