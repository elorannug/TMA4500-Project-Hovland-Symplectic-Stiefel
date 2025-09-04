## Riemannian Optimization using second order Information on the Symplectic Stiefel manifold

This repo contains 
* code for the project report "_Riemannian Optimization using second order Information on the Symplectic Stiefel manifold_",
* the LaTex code for the report, as well as the actual report in .pdf format, and
* an updated report in .pdf format, written after the course was completed, fixing some small mistakes and typos in the original report.
The original text is found in `Project text/Hovland_Specialization_Project_Report_Optimization_on_Symplectic_Stiefel.pdf`, and the new text is named `Project text/Updated_Hovland_Specialization_Project_Report_Optimization_on_Symplectic_Stiefel.pdf`.

Note that the scripts "gr_desc_SpGr_retract_comparison.jl", "grad_desc_nearest_sp_matrix.jl", and "pluto_warmup.jl" are not part of the report, but some users might find them insightful in how to use `Manopt.jl` and `Pluto` notebooks. 

Below is an exerpt of the abstract of the report:

This report explores optimization algorithms on Riemannian manifolds, which are problems where the cost function is defined on a smooth manifold. Riemannian optimization is used in many problems, for example in machine learning, robotics and scientific computing. The report reproduces some results from the two papers "_Riemannian optimization on the symplectic Stiefel manifold using second-order information_" by Jensen and Zimmermann and "_The real symplectic Stiefel and Grassmann man-
ifolds: metrics, geodesics and applications_" by Bendokat and Zimmermann. In particular we investigate the Riemannian gradient descent method and the Riemannian trust-region method. To compare the algorithms we apply them to multiple optimization problems of symplectic nature, as well as evaluating the impact of different retractions on the algorithms performance. All of the code have been implemented in Julia using the package Manopt.jl. Apart from mostly reaffirming the results in the aforementioned papers, we also find that the pseudo-Riemannian geodesic retraction, introduced by Bendokat and Zimmermann, performs competitively compared to the Cayley retraction.
