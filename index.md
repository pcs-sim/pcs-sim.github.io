title: Progressive Simulation for Cloth Quasistatics
author: Jiayi Eris Zhang, Jérémie Dumas, Yun (Raymond) Fei, Alec Jacobson, Doug L. James, Danny M. Kaufman
html header: <meta property="og:image" content="./pcs-teaser.png" />
<meta property="og:description" content="The trade-off between speed and fidelity in cloth simulation is a fundamental computational problem in computer graphics and computational design. Coarse cloth models provide the interactive performance required by designers, but they can not be simulated at higher resolutions (“up-resed”) without introducing simulation artifacts and/or unpredicted outcomes, such as different folds, wrinkles and drapes. But how can a coarse simulation predict the result of an unconstrained, high-resolution simulation that has not yet been run?
We propose Progressive Cloth Simulation (PCS), a new forward simulation method for efficient preview of cloth quasistatics on exceedingly coarse triangle meshes with consistent and progressive improvement over a hierarchy of increasingly higher-resolution models. PCS provides an efficient coarse previewing simulation method that predicts the coarse-scale folds and wrinkles that will be generated by a corresponding converged, high-fidelity C-IPC simulation of the cloth drape’s equilibrium. For each preview PCS can generate an increasing-resolution sequence of consistent models that progress towards this converged solution. This successive improvement can then be interrupted at any point, for example, whenever design parameters are updated. PCS then ensures feasibility at all resolutions, so that predicted solutions remain intersection-free and capture the complex folding and buckling behaviors of frictionally contacting cloth."/>
<meta name="twitter:card" content="summary"></meta>
<meta name="og:title" content="Progressive Simulation for Cloth Quasistatics"></meta>
css: style.css

# Progressive Simulation for Cloth Quasistatics _SIGGRAPH ASIA 2022_

<div class=authors>
  Jiayi Eris Zhang<sup>1,2</sup>, Jérémie Dumas<sup>1</sup>, Yun (Raymond) Fei<sup>1</sup>, Alec Jacobson<sup>1,3</sup>, Doug L. James<sup>2</sup>, Danny M. Kaufman<sup>1</sup><br><br>
  <sup>1</sup>Adobe Research, <sup>2</sup>Stanford University, <sup>3</sup>University of Toronto <br><br>
  <em>ACM Transactions on Graphics (SIGGRAPH Asia 2022)</em>
</div>


## Abstract
The trade-off between speed and fidelity in cloth simulation is a fundamental computational problem in computer graphics and computational design. Coarse cloth models provide the interactive performance required by designers, but they can not be simulated at higher resolutions (“up-resed”) without introducing simulation artifacts and/or unpredicted outcomes, such as different folds, wrinkles and drapes. But how can a coarse simulation predict the result of an unconstrained, high-resolution simulation that has not yet been run?<br><br>
We propose Progressive Cloth Simulation (PCS), a new forward simulation method for efficient preview of cloth quasistatics on exceedingly coarse triangle meshes with consistent and progressive improvement over a hierarchy of increasingly higher-resolution models. PCS provides an efficient coarse previewing simulation method that predicts the coarse-scale folds and wrinkles that will be generated by a corresponding converged, high-fidelity C-IPC simulation of the cloth drape’s equilibrium. For each preview PCS can generate an increasing-resolution sequence of consistent models that progress towards this converged solution. This successive improvement can then be interrupted at any point, for example, whenever design parameters are updated. PCS then ensures feasibility at all resolutions, so that predicted solutions remain intersection-free and capture the complex folding and buckling behaviors of frictionally contacting cloth.
