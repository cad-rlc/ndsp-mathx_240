# Cadence NatureDSP Library for MathX 240 DSP cores

<p>This NatureDSP Library for MathX 240 DSP contains various optimized general purpose signal processing routines.</p>

<h1> Version: v1.2.0 </h1>
<p> 
This is an early access (v1.2.0) of NatureDSP library for MathX 240 DSP.
This version of library has been tested with RJ-2024.3 Xtensa tools 
and has the same APIs with its predecessor, FloatingPoint KQ8.

This release contains following changes when compared to the previous release of FloatingPoint KQ8 library v1.1.0:
</p> 
<h3>Changes:</h3>
        <p>
        <ol>
        <li>xt-clang LLVM15 migration related changes and fixes</li>
        </ol>
        </p>
<h3> Known issues:</h3>
     <p>
     <ol>
    <li>Performance of some functions may need further tuning for RJ-2024.3 tools.</li>
     </ol>
     </p>

<h1> Version: v1.1.0 </h1>
<p> 
This is an Early access of NatureDSP library for the floating point KQ8 DSP. In this revision new floating point functions for general signal processing 
applications are included in addition to the functions released in XPG v1.0.0.
</p> 
<h3>Library routines newly added in this version:</h3>
        <p>
        <ol>
        <li> Single Precision - Vector API variants from categories Math, Complex and Vector</li>
        <li> Double Precision  - Vector API variants from categories Math and Complex</li>
        </ol>
        </p>
 <h3> Details:</h3>
       <p>
       <ol>
      <li>This version of library has been optimized and tested with RI-2023.11 Xtensa tools.</li>
      </ol>
      </p>
<h3> Known issues:</h3>
     <p>
     <ol>
    <li> None based on the sanity testing. </li>
     </ol>
     </p>

<h1> Version: v1.0.0 </h1>
<p> 
<ol><li>This is the first version of the NatureDSP library on KQ8 DSP.</li>
</ol></p> 
 <h3> Details:</h3>
       <p>
       <ol>
      <li>This version of library has been optimized and tested with RI-2021.7 Xtensa tools.</li>
      </ol>
      </p>
<h3> Known issues:</h3>
     <p>
     <ol>
    <li> None</li>
     </ol>
     </p>



<h1>To use the library </h1>
<p>
<ol>
<li>Download the library & demo xws from the repository and import them into Xtensa Xplorer environment.</li>
<li>Upon importing, two directories i.e. mathx240_library & mathx240_demo  will be available in the Project Xplorer pane.</li>
<li>Refer to Chapter-3 of "NatureDSP_Library_Reference_MathX_240.pdf" document present inside the mathx240_library/doc directory for details on build and run.</li>
<li>Detailed Release notes can be found at mathx240_library/doc directory.</li>
</ol>
</p>

