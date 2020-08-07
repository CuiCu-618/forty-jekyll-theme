---
title: Research
layout: landing
description: 'Research and Interests'
image: assets/res_bc.jpg
nav-menu: true
---

<!-- Main -->
<div id="main">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h2>About</h2>
		</header>
		<p>I am a master student at Sun Yat-Sen University in Computational Mathematics. My study is in the area of Numerical Solution of Partial Difference Equations with main focus on Stable Generalized Finite Element Method. Through the undergraduate and graduate studies of mathematics, I am now more interested in the fields of computational science and engineering, and hope to learn more about how to apply the knowledge I have learned to practical problems. In this page there are some of my research experience and computer skills.</p>
	</div>
</section>

<!-- Two -->
<section id="two" class="spotlights">
	<section>
		<a href="assets/Research.jpg" class="image">
			<img src="assets/Research.jpg" alt="" data-position="right center"/>
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Stable Generalized Finite Element Method (SGFEM)</h3>
				</header>
				<p>Generalized or eXtended finite element methods (GFEM/XFEM) for crack problems have been studied extensively. A GFEM/XFEM is referred to as stable GFEM (SGFEM) if it reaches optimal convergence orders, and its SCN is of same order as that of FEM. In this article we propose the SGFEM for elasticity crack problems; both extrinsic and DOF-gathering schemes are addressed. <b>My main work is numerical experiments
which demonstrate that the proposed SGFEM and DOF-gathering SGFEM are of optimal convergence and have the SCNs of same order as in the FEM</b>. We also propose a SGFEM for 3D crack problems. The numerical experiments for both the planar and fully 3D crack problems are executed to verified efficiency of the proposed SGFEM.</p>
				<ul class="actions">
					<li><a href="https://doi.org/10.1002/nme.6347" class="button">Learn more</a></li>
				</ul>
			</div>
		</div>
	</section>
	<section>
		<a href="landing.html" class="image">
			<div class="box alt">
				<div class="row 50% uniform">
					<div class="4u"><span class="image fit"><img src="assets/edge192x128.jpg" alt="" /></span></div>
					<div class="4u"><span class="image fit"><img src="assets/edge512x384.jpg" alt="" /></span></div>
					<!-- Break -->
					<div class="4u"><span class="image fit"><img src="assets/edge768x768.jpg" alt="" /></span></div>
					<div class="4u"><span class="image fit"><img src="assets/mpi_image192x128.jpg" alt="" /></span></div>
					<!-- Break -->
					<div class="4u"><span class="image fit"><img src="assets/mpi_image512x384.jpg" alt="" /></span></div>
					<div class="4u"><span class="image fit"><img src="assets/mpi_image768x768.jpg" alt="" /></span></div>
				</div>
			</div>
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>The Message Passing Interface (MPI)</h3>
				</header>
				<p>MPI (Message-Passing Interface) is a message-passing library interface specification. Here are some simple examples I have done. These pictures show the result of the case study. The aim of this case study is to write a complete MPI parallel program that does a very basic form of image processing. The case study is actually to do the reverse operation and construct the initial image given the edges. 
				<ul>
					<li><a href="http://archer.ac.uk/training/course-material/2014/07/MPI_Edi/">Material</a></li>
					<li><a href="https://github.com/CuiCu-618/MPI">GitHub</a></li>
				</ul>
				</p>
				<ul class="actions">
					<li><a href="https://github.com/CuiCu-618" class="button">Learn more</a></li>
				</ul>
			</div>
		</div>
	</section>
	<section>
		<a href="generic.html" class="image">
			<img src="assets/times_for_fixed_nel_129 copy.jpg" alt="" />
			<img src="assets/times_for_proc_40 copy.jpg" alt="" />
<!-- 			<div class="box alt">
				<div class="">
					<div class="4u"><span class="image fit"><img src="assets/times_for_fixed_nel_129 copy.jpg" alt="" /></span></div>
					<div class="4u"><span class="image fit"><img src="assets/times_for_proc_40 copy.jpg" alt="" /></span></div>
				</div>
			</div> -->
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>MATLAB</h3>
				</header>
				<p>MATLAB is a multi-paradigm numerical computing environment and proprietary programming language developed by MathWorks. I have used MATLAB to program some numerical algorithms since the undergraduate level. In addition to the tutor’s program, the learning of finite element method programming also involves learning through the book <b>Programming the Finite Element Method</b>. I have implemented most of the program algorithms in the book with MATLAB. Also I use SPMD module to parallelize the current program for acceleration. </p>		
<pre><code>
spmd
    statements
end
</code></pre>
				<ul>
					<li><a href="https://github.com/CuiCu-618/matlab_version">Programming the Finite Element Method Code</a></li>
					<li><a href="https://www.mathworks.com/help/parallel-computing/spmd.html?s_tid=srchtitle">SPMD</a></li>
				</ul>
				<ul class="actions">
					<li><a href="generic.html" class="button">Learn more</a></li>
				</ul>
			</div>
		</div>
	</section>
</section>

<!-- Three -->
<section id="three">
	<div class="inner">
		<header class="major">
			<h2>Massa libero</h2>
		</header>
		<p>Nullam et orci eu lorem consequat tincidunt vivamus et sagittis libero. Mauris aliquet magna magna sed nunc rhoncus pharetra. Pellentesque condimentum sem. In efficitur ligula tate urna. Maecenas laoreet massa vel lacinia pellentesque lorem ipsum dolor. Nullam et orci eu lorem consequat tincidunt. Vivamus et sagittis libero. Mauris aliquet magna magna sed nunc rhoncus amet pharetra et feugiat tempus.</p>
		<ul class="actions">
			<li><a href="generic.html" class="button next">Get Started</a></li>
		</ul>
	</div>
</section>

</div>
