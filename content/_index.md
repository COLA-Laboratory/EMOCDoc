---
title: EMOC
type: docs
BookToC: true
---

# EMOC: Evolutionary Multi-objective Optimization in C++

<style>

</style>

<div align="center">
<img src="./emoc_big.png" width = "300px" height = "100px" align=center />

</div>

EMOC stands for **E**volutionary **M**ulti-objective **O**ptimization in **C**++ which is a framework for single-objective and multi-objective optimization. This library is mainly for research and educational purposes.

For installing EMOC, please refer to the section [Install]({{< ref "/docs/install" >}}). We also provide a [Quick Start]({{< ref "/docs/quickstart/user_interface_mode" >}}) section for users to get started.



## Features

- **Rich algorithms and problems**

  EMOC implemented about 30 algorithms and more than 80 test problems which both include single-objective and multi-objective types.

- **Developed in C++ and Cross-platform**

  All the source code of EMOC are wrote in C++. So the running efficiency is guaranteed when comparing other implementation with python, java or matlab. We also provide cross-platform compatibility for users with different operator systems.

- **Friendly GUI**

  EMOC provides a user-friendly GUI with the function of configuring parameters of once-run and experiments without writing a single line of code.

- **Various Optimization Types**

  EMOC supports unconstraint optimization, constraint optimization and combinatorial optimization (including binary encoding and permutation encoding).

- **Save into Excel or Latex**

  Users can save the experiment results of EMOC in the format of Excel or Latex.

  
  
  

<a href="#/" onclick="toggle_visibility('foo');">Citation</a>

<div id="foo" style="display: none;">@ARTICLE{4358754,<br />
  	author={Zhang, Qingfu and Li, Hui},<br />
  	journal={IEEE Transactions on Evolutionary Computation}, <br />
  	title={MOEA/D: A Multiobjective Evolutionary Algorithm Based on Decomposition}, <br />
  	year={2007},<br />
  	volume={11},<br />
  	number={6},<br />
  	pages={712-731},<br />
  	doi={10.1109/TEVC.2007.892759}<br />
    }
</div>

<script>
    function toggle_visibility(id) {
       var e = document.getElementById(id);
       if(e.style.display == 'block')
          e.style.display = 'none';
       else
          e.style.display = 'block';
    }
</script>

## 3rd Party Libraries

- [GLFW](https://www.glfw.org/)
- [ALGLIB](https://www.alglib.net/)
- [Dear Imgui](https://github.com/ocornut/imgui)
- [pybind11](https://github.com/pybind/pybind11)
- [cxxopts](https://github.com/jarro2783/cxxopts)
- [stb_image](https://github.com/nothings/stb)
- [Gnuplot](http://www.gnuplot.info/)
- [CMake](https://cmake.org/)
- [Font-Awesome](https://github.com/FortAwesome/Font-Awesome)




