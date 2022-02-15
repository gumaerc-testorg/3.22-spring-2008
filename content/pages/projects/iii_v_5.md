---
content_type: page
learning_resource_types:
- Projects
ocw_type: CourseSection
parent_title: Projects
parent_type: CourseSection
parent_uid: 8388cfe3-4b2f-b7e7-0060-faf27a65e652
title: Effects of Multidimensional Defects on III-V Semiconductor Mechanics - Problem
  Set 5
uid: 3e7072d8-b2a1-1647-db86-2d7ac5cd83fa
---

_(b) Eq. 2 of Navamathavan, et al. \[[1](#ref)\] states an equivalence between fracture surface energy and K{{< sub "IC" >}}, the plane strain fracture toughness of the semiconductor films inferred from indentation cracking. From the definitions of K{{< sub "IC" >}} and Griffith's fracture criterion, prove whether this equation is true for a brittle material._

The Griffith fracture criterion is for brittle materials and K{{< sub "IC" >}} does not depend on whether the material deforms plastically or elastically. Thus, there is no reason why the Griffith fracture criterion and K{{< sub "IC" >}} cannot both be used to describe a brittle material.

However, strictly speaking, fracture surface energy for nanoindentation tests and K{{< sub "IC" >}} are not equivalent. K{{< sub "IC" >}} typically refers to the plane strain fracture toughness in Mode I loading. However, the loading behavior in nanoindentation need not be Mode I. Nanoindentation comprises of a more complicated stress state that implies a mixed-Mode loading situation. The K{{< sub "IC" >}} defined here, however, is inferred from the indentation test and therefore is the stress intensity factor for this particular type of mixed mode loading (calculated using equation (1) in the paper).

However, given the newly defined K{{< sub "IC" >}} from the paper, and

K{{< sub "IC" >}} = f\*σ\*√\[π\*a\] (although for Mode I)

If we take f = 1,

K{{< sub "IC" >}} = σ\*√\[π\*a\]

and the Griffith's fracture criterion

σ = √\[2E\*(γ)/(π\*a)\]

we can solve for the fracture surface energy:

σ = √\[2E\*(γ)/(π\*a)\]

σ\*√\[π\*a\] = √\[2E γ\]

K{{< sub "IC" >}} = √\[2E γ\]

γ{{< sub "f" >}} = (K{{< sub "IC" >}}{{< sup "2" >}} )/(2E).

Thus, we obtain Eq. (2), from Navamathavan, et al. under the given conditions, and with this definition of K{{< sub "IC" >}}.

_(c) Although they report these data in Table 3 \[[1](#ref)\], the authors do not appear to put the results in context by comparing the calculated K{{< sub "IC" >}} and surface energy with values reported for these (or similar) materials via other experiments. Do this, and discuss whether you feel the characterization of these fracture properties and surface energies of the materials is valid._

The fracture surface energy and the K{{< sub "IC" >}} values for InGaAs/InP epilayers reported in Table 3 range from 0.035-0.332 J/m{{< sup "2" >}} and 0.303-0.977 MPa(m){{< sup "1/2" >}} respectively. The only reference that we got that gave a measure of Fracture surface energy is Shi, et al. \[[2](#ref)\] They report of a value of 0.525J/m{{< sup "2" >}} for the fracture surface energy of GaAs/GaAs (and using the equation derived above we get a K{{< sub "IC" >}} of 0.3667 MPa m{{< sup "1/2" >}}). We see that this value is of the same range as that reported in Table 3 \[[1](#ref)\]. However the difference in values is obviously due to different compounds dealt in both the papers. Also, as pointed out before, fracture surface energy for nanoindentation tests and K{{< sub "IC" >}} are not equivalent. K{{< sub "IC" >}} typically refers to the plane strain fracture toughness in Mode I loading nanoindentation comprises of a more complicated stress state that implies a mixed-Mode loading situation. However these approximations seem to be giving values that are of the same range as that reported in a different experiment.

_(d) Why do you think the authors observed a film thickness dependence of K{{< sub "IC" >}} and fracture surface energy (in Table 3), if these are supposed to be properties of the material?_

K{{< sub "IC" >}} is a material property but it only becomes constant regardless of sample geometry at very large dimensions, on the order of meters, in the plane strain state. Here, authors are measuring a thin film. That, coupled with the fact that nanoindentation comprises mixed loading Mode, results in some dependence of K{{< sub "IC" >}} on thickness.

In addition, the films tested are grown epitaxially on InP. Thus, the films are stressed laterally and in thicker films, some of this residual stress is relaxed, as shown by \[[3](#ref)\]. Thus, some of the variation in K{{< sub "IC" >}} with respect to film thickness may be due to stress relaxation in the thicker films.

  
 

Image removed due to copyright restrictions. Please see Fig. 1 in \[[3](#ref)\].

  
 

{{< anchor "ref" >}}{{< /anchor >}}References
---------------------------------------------

\[1\] Navamathavana, R., D. Arivuolib, G. Attolinic, C. Pelosic, and Chi Kyu Choia. "Mechanical Properties of Some Binary, Ternary and Quaternary III-V Compound Semiconductor Alloys." _Physica B_ 392 (2007): 51-57.

\[2\] Shi, Frank, et al. "Hybrid Integrated GaAs-GaAs and InP-GaAs." _Journal of Applied Physics_ 93 (2003): 5750-5756.

\[3\] Attolini, G., et al. "Raman Scattering Study of Residual Strain in GaAs/InP Heterostructures." _Journal of Applied Physics_ 75 (April 1994): 4156-4160.

  
  
 

[Plasticity and fracture of microelectronic thin films/lines]({{< baseurl >}}/pages/projects/thinfilms_home)  
[Effects of multidimensional defects on III-V semiconductor mechanics]({{< baseurl >}}/pages/projects/iii_v_home) | [Problem Set 2]({{< baseurl >}}/pages/projects/iii_v_2) | [Problem Set 3]({{< baseurl >}}/pages/projects/iii_v_3) | Problem Set 5  
[Defect nucleation in crystalline metals]({{< baseurl >}}/pages/projects/defec_nuclea_hom)  
[Role of water in accelerated fracture of fiber optic glass]({{< baseurl >}}/pages/projects/fiber_optics_hom)  
[Carbon nanotube mechanics]({{< baseurl >}}/pages/projects/cnt_mech_home)  
[Superelastic and superplastic alloys]({{< baseurl >}}/pages/projects/superelasti_home)  
[Mechanical behavior of a virus]({{< baseurl >}}/pages/projects/virus_home)  
[Effects of radiation on mechanical behavior of crystalline materials]({{< baseurl >}}/pages/projects/radiation_home)