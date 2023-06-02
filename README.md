# Resources for phase acquisition
Here, we refer to the process of “calculating the wavefront phase from 
the amplitude/intensity measurement of the light field” as phase acquisition (PA). 
PA contains many techniques and algorithms, such as holography/interferometry, 
transfer of intensity equations (TIE), wavefront-sensing-based approaches, 
optimization-based approaches (phase retrieval), deep-learning(DL)-based approaches.
****
## Table of Contents:

- [Contributing](#contributing)
- [People and groups](#groups)
   - [Americas](#groups-Americas)
   - [Asia](#groups-Asia)
   - [Europe](#groups-Europe)
- [Companies](#companies)
- [Workshops](#workshops) (video or slides available)
- [Research papers](#Rpapers)
   - [Conventional phase acquisition](#PARpapers)
     - [Holography/Interferometry](#HoloRpapers)
     - [Transport of intensity equation](#TIERpapers)
     - [Wavefront-sensing-based approaches](#WSRpapers)
     - [Optimization-based approaches](#OPRpapers)
   - [Deep-learning(DL)-based phase acquisition ](#DLRpapers)
     - [DL-pre-processing for phase acquisition](#DLpreRpapers)
       - [Super-resolution](#DLpreSRRpapers)
       - [Noise reduction](#DLpreNRRpapers)
       - [Hologram generation](#DLpreHGRpapers)
       - [Autofocusing](#DLpreAFRpapers)
     - [DL-in-processing for phase acquisition](#DLinRpapers)
       - [Dataset-driven network-only strategy](#DLinDDnoRpapers)
       - [Physics-model-driven network-only strategy](#DLinPDnoRpapers)
       - [Physics-model-connect-network strategy](#DLinPcNRpapers)
       - [Network-in-physics-model strategy](#DLinNiPRpapers)
       - [Physics-model-in-network strategy](#DLinPiNRpapers)
     - [DL-post-processing for phase acquisition](#DLpostRpapers)
       - [Noise reduction](#DLpostNRRpapers)
       - [Resolution enhancement](#DLpostRERpapers)
       - [Aberration correction](#DLpostACRpapers)
       - [Phase unwrapping](#DLpostPURpapers)
     - [DL for phase processing](#DLppRpapers)
       - [Segmentation](#DLppSRpapers)
       - [Classification](#DLppCRpapers)
       - [Imaging modal transformation](#DLppIMTRpapers)
- [Review / Tutorial papers](#papers)
   - [Conventional phase acquisition](#PApapers) 
   - [Deep-learning-based phase acquisition](#DLpapers)
- [Books](#BK)
- [Dissertations and Thesis](#DT)
****
   
<a name="contributing"></a>
# Contributing

You are welcome to add or modify any related content via the ["fork and pull request"](https://docs.github.com/en/get-started/quickstart/contributing-to-projects).  

Please use the following guidelines:
- Edit the raw file with [Markdown Syntax](https://www.markdownguide.org/basic-syntax/).
- Avoid typos.
- Don't add what's already there.
- Uniform the format of new additions with that of the existing.
- Note the order of new additions (chronological or alphabetical).  

### Contributors  
This project exists thanks to all the people who contribute.  

<a href="https://github.com/kqwang/Phase_unwrapping_by_U-Net/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=kqwang/Phase_unwrapping_by_U-Net" />
</a>

 
****
<a name="groups"></a>
# People and groups
(In alphabetical order according to surnames)  
(Quick search by "Ctrl + F" with keywords:  
phase imaging, holography, interferometry, optical coherence tomography, phase retrieval, 
Fourier ptychography, inverse problem, transport of intensity equations, wavefront sensing, phase unwrapping,
fringe analysis, computational imaging)
<a name="groups-Americas"></a>
## Americas
- [George Barbastathis ](http://optics.mit.edu/)(Massachusetts Institute of Technology)   
Keywords: computational imaging, phase imaging, and optical coherence tomography etc.

- [Stephen Boppart ](https://biophotonics.illinois.edu/)(University of Illinois Urbana-Champaign)    
Keywords: optical coherence tomography, wavefront sensing, biomedical imaging etc.

- [Stanley H. Chan ](https://engineering.purdue.edu/ChanGroup/)(Purdue University)  
Keywords: wavefront sensing etc.

- [Ni Chen](https://ni-chen.github.io)(University of Arizona)  
Keywords: holography, phase imaging, and light field imaging etc.

- [James R. Fienup ](https://labsites.rochester.edu/fienup/)(University of Rochester)  
Keywords: phase retrieval, coherent diffraction imaging, and wavefront sensing etc.

- [Jason W. Fleischer ](https://www.princeton.edu/~jasonf/)(Mississippi State University)  
Keywords: phase retrieval etc.

- [Paul Hand ](https://khoury.northeastern.edu/home/hand/)(Northeastern University)  
Keywords: inverse problem and phase retrieval etc.

- [Babak Hassibi ](https://www.ee.caltech.edu/people/hassibi)(California Institute of Technology)  
Keywords: phase retrieval etc.

- [Roarke Horstmeyer ](http://horstmeyer.pratt.duke.edu/)(Duke University)  
Keywords: Fourier ptychography and single-photon detection etc.

- [Joseph A. Izatt ](http://biophotonics.pratt.duke.edu/)(Duke University)  
Keywords: biomedical imaging, optical coherence tomography and high-resolution imaging etc.

- [Rongguang Liang ](https://wp.optics.arizona.edu/ualiangaol/)(The University of Arizona)  
Keywords: phase imaging and biomedical imaging etc.

- [Christopher Metzler](https://www.cs.umd.edu/people/metzler)(The University of Maryland)  
Keywords: phase retrieval, inverse problem and computational imaging etc.

- [Jianwei (John) Miao ](https://www.physics.ucla.edu/research/imaging/)(University of California, Los Angeles)  
Keywords: coherent diffractive imaging and atomic electron tomography etc.

- [Aydogan Ozcan ](https://research.seas.ucla.edu/ozcan/)(University of California, Los Angeles)  
Keywords: phase imaging, holography, lensless imaging and optical diffraction neural network etc.

- [Ting-Chung Poon ](https://sites.google.com/vt.edu/oshandholographiclab/home/)(Virginia Polytechnic Institute and State University)  
Keywords: holography etc.

- [Gabriel Popescu ](https://light.ece.illinois.edu/)(University of Illinois at Urbana-Champaign)  
Keywords: phase imaging and biomedical imaging etc.

- [Mariano Rivera ](https://www.cimat.mx/~mrivera/mr.html)(Centro de Investigación en Matemáticas AC)  
Keywords: fringe analysis phase retrieval and phase unwrapping etc.

- [Jannick Rolland ](http://www.odalab-spectrum.org/)(University of Rochester)  
Keywords: optical coherence tomography etc.

- [Ju Sun ](https://glovex.umn.edu/)(University of Minnesota)  
Keywords: inverse problem and phase retrieval etc.

- [Philip Schniter](http://www2.ece.ohio-state.edu/~schniter/)(The Ohio State University)  
Keywords: inverse problem and phase retrieval etc.

- [Lei Tian ](https://sites.bu.edu/tianlab/)(Boston University)  
Keywords: Fourier ptychography, transport of intensity equations (TIE), and imaging through scattering media etc.

- [Ashok Veeraraghavan ](https://www.computationalimaging.org/)(Rice University)  
Keywords: wavefront sensing, imaging through scattering media, and lensless imaging etc.

- [Laura Waller ](https://www.laurawaller.com/)(University of California, Berkeley)  
Keywords: phase imaging, lensless imaging, and transport of intensity equations (TIE) etc.

- [Lihong Wang ](http://coilab.caltech.edu/)(California Institute of Technology)  
Keywords: optical coherence tomography and biomedical imaging etc.

- [Adam P. Wax ](http://bios.bme.duke.edu/)(Duke University)  
Keywords: interferometry and biomedical imaging etc.

- [Florian Willomitzer ](https://3dim.northwestern.edu/)(University of Arizona)  
Keywords: synthetic wavelength holography and interferometry etc.

- [Changhuei Yang ](https://biophot.caltech.edu/)(California Institute of Technology)  
Keywords: Fourier ptychography, wavefront shaping and non-line-of-sight imaging etc.

- [Guoan Zheng ](https://smartimaging.uconn.edu/)(University of Connecticut)  
Keywords: Fourier ptychography etc.
    
<a name="groups-Asia"></a>
## Asia
- [Anand Asundi ](https://www.doptron.com/)(d'Optron Pte Ltd)   
Keywords: phase imaging, holography, and transport of intensity equations (TIE) etc.

- [Liheng Bian ](https://bianlab.github.io/)(Beijing Institute of Technology)  
Keywords: multi-dimensional imaging (spectrum, phase) etc.

- [Liangcai Cao ](http://www.holoddd.com/)(Tsinghua University)  
Keywords: holography etc.

- [Wen Chen ](https://www.eie.polyu.edu.hk/~wenchen/)(The Hong Kong Polytechnic University)  
Keywords: holography and single-pixel imaging etc.

- [Chau-Jern Cheng ](https://scholar.lib.ntnu.edu.tw/en/persons/chau-jern-cheng)(National Taiwan Normal University)  
Keywords: holography etc.

- [Zachary J. Smith and Kaiqin Chu ](http://staff.ustc.edu.cn/)(The University of Science and Technology of China)  
Keywords: phase imaging and super-resolution imaging etc.

- [Jianglei Di ](https://www.researchgate.net/profile/Jianglei-Di)(GuangDong University of Technology)  
Keywords: computational imaging and holography etc.

- [Peng Gao ](https://faculty.xidian.edu.cn/GP3/zh_CN/index.htm)(Xidian University)  
Keywords: phase imaging and super-resolution imaging etc.

- [Ryoichi Horisaki](https://sites.google.com/view/horisaki)(The University of Tokyo)  
Keywords: wavefront sensing, holography and computational imaging etc.

- [Wolfgang Heidrich](https://vccimaging.org/)(King Abdullah University of Science and Technology)  
Keywords: phase imaging and computational imaging etc.

- [Cuifang Kuang ](https://person.zju.edu.cn/en/cfkuang)(Zhejiang University)  
Keywords: three-dimensional super-resolution phase microscopy and super-resolution imaging etc.

- [Edmund Y. Lam ](https://www.eee.hku.hk/~elam/)(The University of Hong Kong)  
Keywords: phase retrieval, holography and computational imaging etc.

- [Cheng Liu ](http://science.jiangnan.edu.cn/content_js.jsp?urltype=news.NewsContentUrl&wbtreeid=1034&wbnewsid=5799)(Jiangnan University)  
Keywords: phase imaging etc.

- [Yuan Luo ](https://optics.mc.ntu.edu.tw/)(National Taiwan University)  
Keywords: phase imaging etc.  

- [Dalip Singh Mehta ](https://web.iitd.ac.in/~mehtads/)(Indian Institute of Technology Delhi)  
Keywords: phase imaging and holograohy etc. 

- [Inkyu Moon](https://iivs.dgist.ac.kr/)(Daegu Gyeongbuk Institute of Science and Technology)  
Keywords: holograohy in cell imaging and analysis etc.

- [An Pan ](https://www.sites.google.com/site/dranpanblog/)(Chinese Academy of Sciences)  
Keywords: Fourier ptychography and biomedical imaging etc.

- [Jung-Hoon Park ](https://www.biooptics.org/)(Ulsan National Institute of Science and Technology)  
Keywords: phase imaging and biomedical imaging etc.

- [YongKeun Park ](https://bmokaist.wordpress.com/)(Korea Advanced Institute of Science and Technology)  
Keywords: phase imaging and biomedical imaging etc.

- [Kemao Qian ](https://www3.ntu.edu.sg/home/mkmqian/)(Nanyang Technological University)  
Keywords: phase unwrapping and fringe analysis etc.

- [Joseph Rosen ](https://www.ee.bgu.ac.il/~rosen/)(Ben-Gurion University of the Negev)  
Keywords: holography etc.

- [Natan T. Shaked](http://www.eng.tau.ac.il/~omni/index2.php/) (Tel Aviv University)  
Keywords: interferometry, optical coherence tomography, and biomedical imaging etc.

- [Guohai Situ ](https://people.ucas.edu.cn/~situ)(University of Chinese Academy of Sciences)  
Keywords: phase imaging, holography, and computational imaging etc.

- [Xiaodi Tan](http://www.io-lab.cn/)(Fujian Normal University)  
Keywords: holography etc.

- [Peter Wai Ming Tsang ](https://scholars.cityu.edu.hk/en/persons/wai-ming-peter-tsang(892d3f89-71e1-4348-9bd0-c27f242c0d00).html)(City University of Hong Kong)  
Keywords: holography etc.

- [Yang Wang ](https://facultyprofiles.hkust.edu.hk/profiles.php?profile=yang-wang-yangwang)(The Hong Kong University of Science and Technology)  
Keywords: phase retrieval etc.

- [Yuan Wu ](http://www.bme.cuhk.edu.hk/yuan/)(The Chinese University of Hong Kong)  
Keywords: optical coherence tomography and biomedical imaging etc.

- [Baoli Yao ](https://people.ucas.ac.cn/~yaobaoli?language=en)(University of Chinese Academy of Sciences)  
Keywords: holography and super-resolution imaging etc.

- [Jianlin Zhao ](https://teacher.nwpu.edu.cn/m/en/1982000067.html)(Northwestern Polytechnical University)  
Keywords: holography and computational imaging etc.

- [Renjie Zhou ](https://www.renjiezhou.com/)(The Chinese University of Hong Kong)  
Keywords: phase imaging and biomedical imaging etc.

- [Chao Zuo ](https://www.scilaboratory.com/)(Nanjing University of Science and Technology)  
Keywords: transport of intensity equations (TIE), phase imaging and computational imaging etc.
    
<a name="groups-Europe"></a>
## Europe
- [Radim Chmelik ](https://www.vut.cz/en/people/radim-chmelik-2190)(Brno University of Technology)  
Keywords: phase imaging and holography etc.

- [Pietro Ferraro](https://scholar.google.com/citations?user=yyFkAiQAAAAJ&hl=en)(Consiglio Nazionale delle Ricerche)  
Keywords: holography etc.

- [Hans-Werner Fink](https://www.physik.uzh.ch/groups/fink/)(University of Zurich)  
Keywords: electron holography etc.

- [Maxime Jacquot](https://www.femto-st.fr/en/femto-people/maximejacquot)(Université Bourgogne Franche-Comté)  
Keywords: holography etc.

- [Aykut Koc](http://aykutkoclab.ee.bilkent.edu.tr/)(Bilkent University)
Keywords: phase retrieval, inverse problem and computational imaging etc.

- [Figen S. Oktem](https://blog.metu.edu.tr/figeno/)(Middle East Technical University)
Keywords: phase retrieval, inverse problem and computational imaging etc.

- [Demetri Psaltis ](https://www.epfl.ch/labs/lo/)(The École polytechnique fédérale de Lausanne)  
Keywords: holography, imaging through scattering media, and linear and non-linear multimode fibers etc.

- [Pascal Picart ](http://perso.univ-lemans.fr/~ppicart/rech/perso/BooksPP.html)(Le Mans University)  
Keywords: holography and phase imaging etc.

- [Latychevskaia Tatiana ](https://coherentimaging.wordpress.com/)(University of Zurich)  
Keywords: holography, phase retrieval and coherent diffractive imaging etc.

- [Michael Unser ](http://bigwww.epfl.ch/)(The École polytechnique fédérale de Lausanne)  
Keywords: phase retrieval, phase unwrapping, transport of intensity equations (TIE) and biomedical imaging etc.

****
<a name="companies"></a>
# Companies
(In alphabetical order)

- [d'Optron](https://www.doptron.com/) 
- [Holmarc Opto-Mechatronics](https://holmarc.com/)  
- [Imaging Optic](https://www.imagine-optic.com/)  
- [Lyncee Tec](https://www.lynceetec.com/)  
- [Nanolive](https://www.nanolive.ch/)  
- [Phase Holographic Imaging PHI AB](https://phiab.com/)  
- [Phasics](https://www.phasics.com/)  
- [Phi Optics](https://phioptics.com/)
- [Telight](https://telight.eu/)
- [Tomocube](https://www.tomocube.com/)
- [Zygo](https://www.zygo.com/)  

****
<a name="workshops"></a>
# Workshops (video or slides available)
(In chronological order)

- ["Phase Retrieval"](https://www.bioxfel.org/phase-retrieval-2021) in BioXFEL (October 18 - 19, 2021)  
- ["Computational Microscopy"](http://www.ipam.ucla.edu/programs/long-programs/computational-microscopy/?tab=overview) in IPAM (September 12 - December 16, 2022)
   - ["Computational Microscopy Tutorials"](http://www.ipam.ucla.edu/programs/workshops/computational-microscopy-tutorials/)(September 13-16, 2022)
   - ["Diffractive Imaging with Phase Retrieval"](http://www.ipam.ucla.edu/programs/workshops/workshop-i-diffractive-imaging-with-phase-retrieval/)(October 10-14, 2022)
   

****
<a name="Rpapers"></a>
# Research papers
(In chronological order)

<a name="PARpapers"></a>
## Conventional phase acquisition 
(Here, we mention only the classic pioneering papers)
<a name="HoloRpapers"></a>
### Holography/Interferometry

- D. Gabor  
*[A New Microscopic Principle](https://doi.org/10.1038/161777a0)*  
Nature 161(4098), 777–778 (1948).
- E. N. Leith and J. Upatnieks  
*[Reconstructed Wavefronts and Communication Theory*](https://doi.org/10.1364/JOSA.52.001123)*  
J. Opt. Soc. Am. 52(10), 1123 (1962).
- I. Yamaguchi and T. Zhang  
*[Phase-shifting digital holography](https://doi.org/10.1364/OL.22.001268)*  
Opt. Lett. 22(16), 1268 (1997).
- G. Popescu, T. Ikeda, R. R. Dasari, and M. S. Feld  
*[Diffraction phase microscopy for quantifying cell structure and dynamics](https://doi.org/10.1364/OL.31.000775)*  
Opt. Lett. 31(6), 775 (2006). 
- Z. Wang, L. Millet, M. Mir, H. Ding, S. Unarunotai, J. Rogers, M. U. Gillette, and G. Popescu  
*[Spatial light interference microscopy (SLIM)](https://doi.org/10.1364/OE.19.001016)*  
Opt. Express 19(2), 1016 (2011).


<a name="TIERpapers"></a>
### Transport of intensity equation
- J. P. Guigay  
*[Fourier transform analysis of Fresnel diffraction patterns and in-line holograms](https://www.researchgate.net/publication/285917772_FOURIER_TRANSFORM_ANALYSIS_OF_FRESNEL_DIFFRACTION_PATTERNS_AND_IN-LINE_HOLOGRAMS)*  
Optik 49, 121–125 (1977).
- D. Paganin and K. A. Nugent  
*[Noninterferometric Phase Imaging with Partially Coherent Light](https://doi.org/10.1103/PhysRevLett.80.2586)*  
Phys. Rev. Lett. 80(12), 2586–2589 (1998).
- M. R. Teague  
*[Deterministic phase retrieval: a Green’s function solution](https://doi.org/10.1364/JOSA.73.001434)*  
J. Opt. Soc. Am. 73(11), 1434 (1983).


<a name="WSRpapers"></a>
### Wavefront-sensing-based approaches
(Mainly refers to the approaches of obtaining the phase gradient first and then integrating to calculate the phase)
- J. Hartmann  
*Bemerkungen uber den Bau und die Justirung von Spektrographen*  
Zeitschrift fuer Instrumentenkunde 20, 47–58 (1900).
- R. V. Shack and B. C. Platt  
*Production and use of a lenticular Hartmann screen*  
J. Opt. Soc. Am. 61, 656–660 (1971).
- J. S. Hartman, R. L. Gordon, and D. L. Lessor  
*[Development Of Nomarski Microscopy For Quantitative Determination Of Surface Topography(A)](https://doi.org/10.1117/12.957861)*  
in G. W. Hopkins, ed. (1979), pp. 223–230. (Conference)
- P. Bon, G. Maucort, B. Wattellier, and S. Monneret  
*[Quadriwave lateral shearing interferometry for quantitative phase microscopy of living cells](https://doi.org/10.1364/OE.17.0130804)*  
Opt. Express 17(15), 13080 (2009).


<a name="ORpapers"></a>
### Optimization-based approaches
#### Alternating projection
- R. W. Gerchberg  
*[A practical algorithm for determination of phase from image and diffraction plane pictures](https://www.scinapse.io/papers/1484412996)*  
Optik 35, 237–246 (1972).
- J. R. Fienup  
*[Reconstruction of an object from the modulus of its Fourier transform](https://doi.org/10.1364/OL.3.000027)*  
Opt. Lett. 3(1), 27 (1978).
- J. R. Fienup  
*[Phase retrieval algorithms: a comparison](https://doi.org/10.1364/AO.21.002758)*  
Appl. Opt. 21(15), 2758 (1982).

#### Axial multi-intensity alternating projection
- L. J. Allen and M. P. Oxley  
*[Phase retrieval from series of images obtained by defocus variation](https://doi.org/10.1364/10.1016/S0030-4018(01)01556-5)*  
Optics Communications 199(1–4), 65–75 (2001).
- G. Pedrini, W. Osten, and Y. Zhang  
*[Wave-front reconstruction from a sequence of interferograms recorded at different planes](https://doi.org/10.1364/OL.30.000833)*  
Opt. Lett. 30(8), 833 (2005).
- A. Greenbaum and A. Ozcan  
*[Maskless imaging of dense samples using pixel super-resolution based multi-height lensfree on-chip microscopy](https://doi.org/10.1364/OE.20.003129)*  
Opt. Express 20(3), 3129 (2012).

#### Radial multi-intensity alternating projection (Ptychographic iterative engine, PIE)
- H. M. L. Faulkner and J. M. Rodenburg  
*[Movable Aperture Lensless Transmission Microscopy: A Novel Phase Retrieval Algorithm](https://doi.org/10.1103/PhysRevLett.93.023903)*  
Phys. Rev. Lett. 93(2), 023903 (2004).
- J. M. Rodenburg and H. M. L. Faulkner  
*[A phase retrieval algorithm for shifting illumination](https://doi.org/10.1063/1.1823034)*  
Appl. Phys. Lett. 85(20), 4795–4797 (2004).

#### Angular multi-intensity alternating projection (Fourier ptychography, FP)
- G. Zheng, R. Horstmeyer, and C. Yang  
*[Wide-field, high-resolution Fourier ptychographic microscopy](https://doi.org/10.1038/nphoton.2013.187)*  
Nature Photon 7(9), 739–745 (2013).
- X. Ou, R. Horstmeyer, C. Yang, and G. Zheng  
*[Quantitative phase imaging via Fourier ptychographic microscopy](https://doi.org/10.1364/OL.38.004845)*  
Opt. Lett. 38(22), 4845 (2013).

#### Non-convex optimization
- E. J. Candes, X. Li, and M. Soltanolkotabi  
*[Phase Retrieval via Wirtinger Flow: Theory and Algorithms](https://doi.org/10.1109/TIT.2015.2399924)*  
IEEE Trans. Inform. Theory 61(4), 1985–2007 (2015).
- G. Wang, G. B. Giannakis, and Y. C. Eldar  
*[Solving Systems of Random Quadratic Equations via Truncated Amplitude Flow](https://doi.org/10.1109/TIT.2017.2756858)*  
IEEE Trans. Inform. Theory 64(2), 773–794 (2018).
 
#### Convex optimization
- E. J. Candès, T. Strohmer, and V. Voroninski  
*[PhaseLift: Exact and Stable Signal Recovery from Magnitude Measurements via Convex Programming](https://doi.org/10.1002/cpa.21432)*  
Comm. Pure Appl. Math. 66(8), 1241–1274 (2013).


<a name="DLRpapers"></a>
## Deep-learning(DL)-based phase acquisition
<a name="DLpreRpapers"></a>
### DL-pre-processing for phase acquisition
<a name="DLpreSRRpapers"></a>
#### Super-resolution
- Z. Luo, A. Yurt, R. Stahl, A. Lambrechts, V. Reumers, D. Braeken, and L. Lagae  
*[Pixel super-resolution for lens-free holographic microscopy using deep learning neural networks](https://doi.org/10.1364/OE.27.013581)*  
Opt. Express 27(10), 13581 (2019).
- H. Byeon, T. Go, and S. J. Lee  
*[Deep learning-based digital in-line holographic microscopy for high resolution with extended field of view](https://doi.org/10.1016/j.optlastec.2018.12.014)*  
Optics & Laser Technology 113, 77–86 (2019).
- Z. Ren, H. K.-H. So, and E. Y. Lam  
*[Fringe Pattern Improvement and Super-Resolution Using Deep Learning in Digital Holography](https://doi.org/10.1109/TII.2019.2913853)*  
IEEE Trans. Ind. Inf. 15(11), 6179–6186 (2019).
- L. Xin, X. Liu, Z. Yang, X. Zhang, Z. Gao, and Z. Liu  
*[Three-dimensional reconstruction of super-resolved white-light interferograms based on deep learning](https://doi.org/10.1016/j.optlaseng.2021.106663)*  
Optics and Lasers in Engineering 145, 106663 (2021).
<a name="DLpreNRRpapers"></a>
#### Noise reduction
- K. Yan, Y. Yu, C. Huang, L. Sui, K. Qian, and A. Asundi  
*[Fringe pattern denoising based on deep learning](https://doi.org/10.1016/j.optcom.2018.12.058)*  
Optics Communications 437, 148–152 (2019).
- F. Hao, C. Tang, M. Xu, and Z. Lei  
*[Batch denoising of ESPI fringe patterns based on convolutional neural network](https://doi.org/10.1364/AO.58.003338)*  
Appl. Opt. 58(13), 3338 (2019).
- W.-J. Zhou, S. Zou, D.-K. He, J.-L. Hu, H. Zhang, Y.-J. Yu, and T.-C. Poon  
*[Speckle noise reduction in digital holograms based on Spectral Convolutional Neural Networks (SCNN)](https://doi.org/10.1117/12.2537685)*  
in Holography, Diffractive Optics, and Applications IX, C. Zhou, Y. Sheng, and L. Cao, eds. (SPIE, 2019), p. 6.
- B. Lin, S. Fu, C. Zhang, F. Wang, and Y. Li  
*[Optical fringe patterns filtering based on multi-stage convolution neural network](https://doi.org/10.1016/j.optlaseng.2019.105853)*  
Optics and Lasers in Engineering 126, 105853 (2020).
- W.-J. Zhou, S. Liu, H. Zhang, Y. Yu, and T.-C. Poon  
*[A Deep Learning Approach for Digital Hologram Speckle Noise Reduction](https://doi.org/10.1364/DH.2020.HTu5B.5)*  
in Imaging and Applied Optics Congress (Optica Publishing Group, 2020), p. HTu5B.5.
- A. Reyes-Figueroa, V. H. Flores, and M. Rivera  
*[Deep neural network for fringe pattern filtering and normalization](https://doi.org/10.1364/AO.413404)*  
Appl. Opt. 60(7), 2022 (2021).
- J. Gurrola-Ramos, O. Dalmau, and T. Alarcón  
*[U-Net based neural network for fringe pattern denoising](https://doi.org/10.1016/j.optlaseng.2021.106829)*  
Optics and Lasers in Engineering 149, 106829 (2022).
<a name="DLpreHGRpapers"></a>
#### Hologram generation
(for phase-shifting)
- Q. Zhang, S. Lu, J. Li, W. Li, D. Li, X. Lu, L. Zhong, and J. Tian   
*[Deep Phase Shifter for Quantitative Phase Imaging](https://doi.org/10.48550/arXiv.2003.03027)*  
Preprint at Arxiv (2020).
- Q. Zhang, S. Lu, J. Li, D. Li, X. Lu, L. Zhong, and J. Tian   
*[Phase-shifting interferometry from single frame in-line interferogram using deep learning phase-shifting technology](https://doi.org/10.1016/j.optcom.2021.127226)*  
Optics Communications 498, 127226 (2021).
- K. Yan, A. Khan, A. Asundi, Y. Zhang, and Y. Yu   
*[Virtual temporal phase-shifting phase extraction using generative adversarial networks](https://doi.org/10.1364/AO.443685)*  
Appl. Opt. 61(10), 2525 (2022).
- Y. Zhao, K. Hu, and F. Liu   
*[One-shot phase retrieval method for interferometry using a multi-stage phase-shifting network](https://doi.org/10.1109/LPT.2022.3222814)*  
IEEE Photon. Technol. Lett. 35, 577–580 (2022).
- T. Huang, Q. Zhang, J. Li, X. Lu, J. Di, L. Zhong, and Y. Qin   
*[Single-shot Fresnel incoherent correlation holography via deep learning based phase-shifting technology](https://doi.org/10.1364/OE.486289)*  
Opt. Express 31(8), 12349 (2023).
- B. Wu, Q. Zhang, T. Liu, Q. Ma, and J. Li   
*[RSAGAN: Rapid self-attention generative adversarial nets for single-shot phase-shifting interferometry](https://doi.org/10.1016/j.optlaseng.2023.107672)*  
Optics and Lasers in Engineering 168, 107672 (2023).  

(to different defocus distances)
- J. Gurrola-Ramos,   
*[Diffraction-Net: a robust single-shot holography for multi-distance lensless imaging](https://doi.org/10.1364/OE.472658)*  
Opt. Express 30(23), 41724 (2022).  

(for multi-wavelength holography)
- J. Li, Q. Zhang, L. Zhong, J. Tian, G. Pedrini, and X. Lu   
*[Quantitative phase imaging in dual-wavelength interferometry using a single wavelength illumination and deep learning](https://doi.org/10.1364/OE.402808)*  
Opt. Express 28(19), 28140 (2020).
- J. Li, Q. Zhang, L. Zhong, and X. Lu   
*[Hybrid-net: a two-to-one deep learning framework for three-wavelength phase-shifting interferometry](https://doi.org/10.1364/OE.438444)*  
Opt. Express 29(21), 34656 (2021).
- X. Xu, M. Xie, Y. Ji, and Y. Wang   
*[Dual-wavelength interferogram decoupling method for three-frame generalized dual-wavelength phase-shifting interferometry based on deep learning](https://doi.org/10.1364/JOSAA.412433)*  
J. Opt. Soc. Am. A 38(3), 321 (2021).
<a name="DLpreAFRpapers"></a>
#### Autofocusing 
(by classification)
- T. Pitkäaho, A. Manninen, and T. J. Naughton   
*[Performance of Autofocus Capability of Deep Convolutional Neural Networks in Digital Holographic Microscopy](https://doi.org/10.1364/DH.2017.W2A.5)*  
in Digital Holography and Three-Dimensional Imaging (OSA, 2017), p. W2A.5.
- T. Pitkäaho, A. Manninen, and T. J. Naughton   
*[Focus classification in digital holographic microscopy using deep convolutional neural networks](https://doi.org/10.1117/12.2286161)*  
in E. Beaurepaire, F. S. Pavone, and P. T. C. So, eds. (2017), p. 104140K.
- Z. Ren, Z. Xu, and E. Y. M. Lam   
*[Autofocusing in digital holography using deep learning](https://doi.org/10.1117/12.2289282)*  
in Three-Dimensional and Multidimensional Microscopy: Image Acquisition and Processing XXV (SPIE, 2018), p. 56.
- K. Son, W. Jeong, W. Jeon, and H. Yang   
*[Autofocusing algorithm for a digital holographic imaging system using convolutional neural networks](https://doi.org/10.7567/JJAP.57.09SB02)*  
Jpn. J. Appl. Phys. 57(9S1), 09SB02 (2018).
- R. Couturier, M. Salomon, E. A. Zeid, and C. A. Jaoude   
*[Using Deep Learning for Object Distance Prediction in Digital Holography](https://doi.org/10.1109/ICCCR49711.2021.9349275)*  
in 2021 International Conference on Computer, Control and Robotics (ICCCR) (IEEE, 2021), pp. 231–235.

(by regression)
- Z. Ren, Z. Xu, and E. Y. Lam   
*[Learning-based nonparametric autofocusing for digital holography](https://doi.org/10.1364/OPTICA.5.000337)*  
Optica 5(4), 337 (2018).
- J.-S. Lee   
*[Autofocusing using deep learning in off-axis digital holography](https://doi.org/10.1364/DH.2018.DTh1C.4)*  
in Imaging and Applied Optics 2018 (3D, AO, AIO, COSI, DH, IS, LACSEA, LS&C, MATH, PcAOP) (OSA, 2018), p. DTh1C.4.
- T. Shimobaba, T. Kakue, and T. Ito   
*[Convolutional Neural Network-Based Regression for Depth Prediction in Digital Holography](https://doi.org/10.1109/ISIE.2018.8433651)*  
in 2018 IEEE 27th International Symposium on Industrial Electronics (ISIE) (IEEE, 2018), pp. 1323–1326.
- T. Pitkäaho, A. Manninen, and T. J. Naughton   
*[Focus prediction in digital holographic microscopy using deep convolutional neural networks](https://doi.org/10.1364/AO.58.00A202)*  
Appl. Opt. 58(5), A202 (2019).
- K. Jaferzadeh, S.-H. Hwang, I. Moon, and B. Javidi   
*[No-search focus prediction at the single cell level in digital holographic imaging with deep convolutional neural network](https://doi.org/10.1364/BOE.10.004276)*  
Biomed. Opt. Express 10(8), 4276 (2019).
- I. Moon and K. Jaferzadeh   
*[Automated digital holographic image reconstruction with deep convolutional neural networks](https://doi.org/10.1117/12.2554533)*  
in Three-Dimensional Imaging, Visualization, and Display 2020, (SPIE, 2020), p. 10.
- S. Cuenat and R. Couturier   
*[Convolutional Neural Network (CNN) vs Vision Transformer (ViT) for Digital Holography](https://doi.org/10.1109/ICCCR54399.2022.9790134)*  
in 2022 2nd International Conference on Computer, Control and Robotics (ICCCR) (IEEE, 2022), pp. 235–240.
- S. Cuenat, L. Andréoli, A. N. André, P. Sandoz, G. J. Laurent, R. Couturier, and M. Jacquot   
*[Fast autofocusing using tiny transformer networks for digital holographic microscopy](https://doi.org/10.1364/OE.458948)*  
Opt. Express 30(14), 24730 (2022).

<a name="DLinRpapers"></a>
### DL-in-processing for phase acquisition
<a name="DLinDDnoRpapers"></a>
#### Dataset-driven network-only strategy  
- A. Sinha, J. Lee, S. Li, and G. Barbastathis   
*[Lensless computational imaging through deep learning](https://doi.org/10.1364/OPTICA.4.001117)*  
Optica 4(9), 1117 (2017).
- H. Wang, M. Lyu, and G. Situ   
*[eHoloNet: a learning-based end-to-end approach for in-line digital holographic reconstruction](https://doi.org/10.1364/OE.26.022603)*  
Opt. Express 26(18), 22603 (2018).
- T. Nguyen, Y. Xue, Y. Li, L. Tian, and G. Nehmetallah   
*[Deep learning approach for Fourier ptychography microscopy](https://doi.org/10.1364/OE.26.026470)*  
Opt. Express 26(20), 26470 (2018).
- S. Li and G. Barbastathis   
*[Spectral pre-modulation of training examples enhances the spatial resolution of the phase extraction neural network (PhENN)](https://doi.org/10.1364/OE.26.029340)*  
Opt. Express 26(22), 29340 (2018).
- M. J. Cherukara, Y. S. G. Nashed, and R. J. Harder   
*[Real-time coherent diffraction inversion using deep generative networks](https://doi.org/10.1038/s41598-018-34525-1)*  
Sci Rep 8(1), 16520 (2018).
- <a name="Goy18prl"></a> A. Goy, K. Arthur, S. Li, and G. Barbastathis   
*[Low Photon Count Phase Retrieval Using Deep Learning](https://doi.org/PhysRevLett.121.243902)*  
Phys. Rev. Lett. 121(24), 243902 (2018).
- Y. F. Cheng, M. Strachan, Z. Weiss, M. Deb, D. Carone, and V. Ganapati   
*[Illumination pattern design with deep learning for single-shot Fourier ptychographic microscopy](https://doi.org/10.1364/OE.27.000644)*  
Opt. Express 27(2), 644 (2019).
- Z. Ren, Z. Xu, and E. Y. Lam   
*[End-to-end deep learning framework for digital holographic reconstruction](https://doi.org/10.1103/10.1117/1.AP.1.1.016004)*  
Adv. Photon. 1(01), 1 (2019).
- X. Li, H. Qi, S. Jiang, P. Song, G. Zheng, and Y. Zhang   
*[Quantitative phase imaging via a cGAN network with dual intensity images captured under centrosymmetric illumination](https://doi.org/10.1364/OL.44.002879)*  
Opt. Lett. 44(11), 2879 (2019).
- K. Wang, J. Dou, Q. Kemao, J. Di, and J. Zhao   
*[Y-Net: a one-to-two deep learning framework for digital holographic reconstruction](https://doi.org/10.1364/OL.44.004765)*  
Opt. Lett. 44(19), 4765 (2019).
- Y. Nishizaki, R. Horisaki, K. Kitaguchi, M. Saito, and J. Tanida   
*[Analysis of non-iterative phase retrieval based on machine learning](https://doi.org/10.1007/s10043-019-00574-8)*  
Opt Rev 27(1), 136–141 (2020).
- T. Zeng, H. K.-H. So, and E. Y. Lam   
*[RedCap: residual encoder-decoder capsule network for holographic image reconstruction](https://doi.org/10.1364/OE.383350)*  
Opt. Express 28(4), 4876 (2020).
- D. Yin, Z. Gu, Y. Zhang, F. Gu, S. Nie, J. Ma, and C. Yuan   
*[Digital Holographic Reconstruction Based on Deep Learning Framework With Unpaired Data](https://doi.org/10.1109/JPHOT.2019.2961137)*  
IEEE Photonics J. 12(2), 1–12 (2020).
- L. Hu, S. Hu, W. Gong, and K. Si   
*[Deep learning assisted Shack–Hartmann wavefront sensor for direct wavefront detection](https://doi.org/10.1364/OL.395579)*  
Opt. Lett. 45(13), 3741 (2020).
- K. Wang, Q. Kemao, J. Di, and J. Zha   
*[Y4-Net: a deep learning solution to one-shot dual-wavelength digital holographic reconstruction](https://doi.org/10.1364/OL.395445)*  
Opt. Lett. 45(15), 4220 (2020).
- M. Deng, S. Li, Z. Zhang, I. Kang, N. X. Fang, and G. Barbastathis   
*[On the interplay between physical and content priors in deep learning for computational imaging](https://doi.org/10.1364/OE.395204)*  
Opt. Express 28(16), 24152 (2020).
- K. Wang, J. Di, Y. Li, Z. Ren, Q. Kemao, and J. Zhao   
*[Transport of intensity equation from a single intensity image via deep learning](https://doi.org/10.1016/j.optlaseng.2020.106233)*  
Opt. Lasers Eng. 134, 106233 (2020).
- L. Wu, P. Juhas, S. Yoo, and I. Robinson   
*[Complex imaging of phase domains by deep neural networks](https://doi.org/10.1107/S2052252520013780)*  
IUCrJ 8(1), 12–21 (2021).
- <a name="Huang21acsp"></a> L. Huang, T. Liu, X. Yang, Y. Luo, Y. Rivenson, and A. Ozcan   
*[Holographic Image Reconstruction with Phase Recovery and Autofocusing Using Recurrent Neural Networks](https://doi.org/10.1021/acsphotonics.1c00337)*  
ACS Photonics 8(6), 1763–1774 (2021).
- T. Uelwer, T. Hoffmann, and S. Harmeling   
*[Non-iterative Phase Retrieval with Cascaded Neural Networks](https://doi.org/10.1007/978-3-030-86340-1_24)*  
in Artificial Neural Networks and Machine Learning – ICANN 2021 (Springer International Publishing, 2021), 12892, pp. 295–306.
- R. Castaneda, C. Trujillo, and A. Doblas   
*[Video-Rate Quantitative Phase Imaging Using a Digital Holographic Microscope and a Generative Adversarial Network](https://doi.org/10.3390/s21238021)*  
Sensors 21(23), 8021 (2021).
- D. Pirone, D. Sirico, L. Miccio, V. Bianco, M. Mugnano, P. Ferraro, and P. Memmolo   
*[Speeding up reconstruction of 3D tomograms in holographic flow cytometry via deep learning](https://doi.org/10.1039/D1LC01087E)*  
Lab Chip 22(4), 793–804 (2022).
- W. Luo, Y. Zhang, X. Shu, M. Niu, and R. Zhou   
*[Learning end-to-end phase retrieval using only one interferogram with mixed-context network](https://doi.org/10.1117/12.2610502)*  
in Quantitative Phase Imaging VIII, G. Popescu, Y. Park, and Y. Liu, eds. (SPIE, 2022), p. 26.
- K. Jaferzadeh and T. Fevens   
*[HoloPhaseNet: fully automated deep-learning-based hologram reconstruction using a conditional generative adversarial model](https://doi.org/10.1364/BOE.452645)*  
Biomed. Opt. Express 13(7), 4032 (2022).
- H. Ding, F. Li, X. Chen, J. Ma, S. Nie, R. Ye, and C. Yuan   
*[ContransGAN: Convolutional Neural Network Coupling Global Swin-Transformer Network for High-Resolution Quantitative Phase Imaging with Unpaired Data](https://doi.org/10.3390/cells11152394)*  
Cells 11(15), 2394 (2022).
- H. Chen, L. Huang, T. Liu, and A. Ozcan   
*[Fourier Imager Network (FIN): A deep neural network for hologram reconstruction with superior external generalization](https://doi.org/10.1038/s41377-022-00949-8)*  
Light Sci Appl 11(1), 254 (2022).
- Q. Ye, L.-W. Wang, and D. P. K. Lun   
*[SiSPRNet: end-to-end learning for single-shot phase retrieval](https://doi.org/10.1364/OE.464086)*  
Opt. Express 30(18), 31937 (2022).
- X. Shu, M. Niu, Y. Zhang, and R. Zhou   
*[NAS-PRNet: Neural Architecture Search generated Phase Retrieval Net for Off-axis Quantitative Phase Imaging](https://doi.org/10.48550/arXiv.2210.14231)*  
Preprint at Arxiv (2022).
- C. Lee, G. Song, H. Kim, J. C. Ye, and M. Jang   
*[Deep learning based on parameterized physical forward model for adaptive holographic imaging with unpaired data](https://doi.org/10.1038/s42256-022-00584-3)*  
Nat Mach Intell 5, 35–45 (2023).
- H. Chen, L. Huang, T. Liu, and A. Ozcan   
*[eFIN: Enhanced Fourier Imager Network for Generalizable Autofocusing and Pixel Super-Resolution in Holographic Imaging](https://doi.org/10.1109/JSTQE.2023.3248684)*  
PhysIEEE J. Select. Topics Quantum Electron. 29(4: Biophotonics), 1–10 (2023).

(Distortion intensity of target objects → Network → the wavefront phase or its Zernike coefficient)
(Applications in Adaptive Optics)
1.  S. W. Paine and J. R. Fienup, "Machine learning for improved image-based wavefront sensing," Opt. Lett. 43(6), 1235 (2018).
2.  Y. Jin, Y. Zhang, L. Hu, H. Huang, Q. Xu, X. Zhu, L. Huang, Y. Zheng, H.-L. Shen, W. Gong, and K. Si, "Machine learning guided rapid focusing with sensor-less aberration corrections," Opt. Express 26(23), 30162 (2018).
3.  G. Ju, X. Qi, H. Ma, and C. Yan, "Feature-based phase retrieval wavefront sensing approach using machine learning," Opt. Express 26(24), 31767 (2018).
4.  Y. Nishizaki, M. Valdivia, R. Horisaki, K. Kitaguchi, M. Saito, J. Tanida, and E. Vera, "Deep learning wavefront sensing," Opt. Express 27(1), 240 (2019).
5.  H. Ma, H. Liu, Y. Qiao, X. Li, and W. Zhang, "Numerical study of adaptive optics compensation based on Convolutional Neural Networks," Optics Communications 433, 283–289 (2019).
6.  Q. Tian, C. Lu, B. Liu, L. Zhu, X. Pan, Q. Zhang, L. Yang, F. Tian, and X. Xin, "DNN-based aberration correction in a wavefront sensorless adaptive optics system," Opt. Express 27(8), 10765 (2019).
7.  J. Liu, P. Wang, X. Zhang, Y. He, X. Zhou, H. Ye, Y. Li, S. Xu, S. Chen, and D. Fan, "Deep learning based atmospheric turbulence compensation for orbital angular momentum beam distortion and communication," Opt. Express 27(12), 16671 (2019).
8.  Y. Zhang, C. Wu, Y. Song, K. Si, Y. Zheng, L. Hu, J. Chen, L. Tang, and W. Gong, "Machine learning based adaptive optics for doughnut-shaped beam," Opt. Express 27(12), 16871 (2019).
9.  H. Guo, Y. Xu, Q. Li, S. Du, D. He, Q. Wang, and Y. Huang, "Improved Machine Learning Approach for Wavefront Sensing," Sensors 19(16), 3533 (2019).
10.  Y. Xu, D. He, Q. Wang, H. Guo, Q. Li, Z. Xie, and Y. Huang, "An Improved Method of Measuring Wavefront Aberration Based on Image with Machine Learning in Free Space Optical Communication," Sensors 19(17), 3665 (2019).
11.  Q. Xin, G. Ju, C. Zhang, and S. Xu, "Object-independent image-based wavefront sensing approach using phase diversity images and deep learning," Opt. Express 27(18), 26102 (2019).
12.  T. Andersen, M. Owner-Petersen, and A. Enmark, "Neural networks for image-based wavefront sensing for astronomy," Opt. Lett. 44(18), 4618 (2019).
13.  M. Chen, X. Jin, and Z. Xu, "Investigation of Convolution Neural Network-Based Wavefront Correction for FSO Systems," in 2019 11th International Conference on Wireless Communications and Signal Processing (WCSP) (IEEE, 2019), pp. 1–6.
14.  B. P. Cumming, M. Gu, and M. Gu, "Direct determination of aberration functions in microscopy by an artificial neural network," Opt. Express, OE 28(10), 14511–14521 (2020).
15.  I. Vishniakou and J. D. Seelig, "Wavefront correction for adaptive optics with reflected light and deep neural networks," Opt. Express 28(10), 15459 (2020).
16.  Y. Wu, Y. Guo, H. Bao, and C. Rao, "Sub-Millisecond Phase Retrieval for Phase-Diversity Wavefront Sensor," Sensors 20(17), 4877 (2020).
17.  X. Wang, T. Wu, C. Dong, H. Zhu, Z. Zhu, and S. Zhao, "Integrating deep learning to achieve phase compensation for free-space orbital-angular-momentum-encoded quantum key distribution under atmospheric turbulence," Photon. Res. 9(2), B9 (2021).
18.  E. Vera, F. Guzmán, and C. Weinberger, "Boosting the deep learning wavefront sensor for real-time applications [Invited]," Appl. Opt. 60(10), B119 (2021).
19.  Y. He, Z. Liu, Y. Ning, J. Li, X. Xu, and Z. Jiang, "Deep learning wavefront sensing method for Shack-Hartmann sensors with sparse sub-apertures," Opt. Express 29(11), 17669 (2021).
20.  S. Hu, L. Hu, W. Gong, Z. Li, and K. Si, "Deep learning based wavefront sensor for complex wavefront detection in adaptive optical microscopes," Front Inform Technol Electron Eng 22(10), 1277–1288 (2021).
21.  K. Wang, M. Zhang, J. Tang, L. Wang, L. Hu, X. Wu, W. Li, J. Di, G. Liu, and J. Zhao, "Deep learning wavefront sensing and aberration correction in atmospheric turbulence," PhotoniX 2(1), 8 (2021).


<a name="DLinPDnoRpapers"></a>
#### Physics-model-driven network-only strategy 
(with untrained/initialized networks)
- L. Boominathan, M. Maniparambil, H. Gupta, R. Baburajan, and K. Mitra   
*[Phase retrieval for Fourier Ptychography under varying amount of measurements](https://doi.org/10.48550/arXiv.1805.03593)*  
Preprint at Arxiv (2018).
- F. Wang, Y. Bian, H. Wang, M. Lyu, G. Pedrini, W. Osten, G. Barbastathis, and G. Situ   
*[Phase imaging with an untrained neural network](https://doi.org/10.1038/s41377-020-0302-3)*  
Light Sci Appl 9(1), 77 (2020).
- D. Yang, J. Zhang, Y. Tao, W. Lv, S. Lu, H. Chen, W. Xu, and Y. Shi   
*[Dynamic coherent diffractive imaging with a physics-driven untrained learning method](https://doi.org/10.1364/OE.433507)*  
Opt. Express 29(20), 31426 (2021).
- C. Bai, T. Peng, J. Min, R. Li, Y. Zhou, and B. Yao   
*[Dual-wavelength in-line digital holography with untrained deep neural networks](https://doi.org/10.1364/PRJ.441054)*  
Photon. Res. 9(12), 2501 (2021).
- X. Zhang, F. Wang, and G. Situ   
*[BlindNet: an untrained learning approach toward computational imaging with model uncertaint](https://doi.org/10.1088/1361-6463/ac2ad4)*  
J. Phys. D: Appl. Phys. 55(3), 034001 (2022).
- D. Yang, J. Zhang, Y. Tao, W. Lv, Y. Zhu, T. Ruan, H. Chen, X. Jin, Z. Wang, J. Qiu, and Y. Shi   
*[Coherent modulation imaging using a physics-driven neural network](https://doi.org/10.1364/OE.472083)*  
Opt. Express 30(20), 35647 (2022).
- A. S. Galande, V. Thapa, H. P. R. Gurram, and R. John   
*[Untrained deep network powered with explicit denoiser for phase recovery in inline holography](https://doi.org/10.1063/5.0144795)*  
Appl. Phys. Lett. 122(13), 133701 (2023).

(with trained networks)
- Y. Yao, H. Chan, S. Sankaranarayanan, P. Balaprakash, R. J. Harder, and M. J. Cherukara    
*[AutoPhaseNN: unsupervised physics-aware deep learning of 3D nanoscale Bragg coherent diffraction imagin](https://doi.org/10.1038/s41524-022-00803-w)*  
npj Comput Mater 8(1), 124 (2022).
- R. Li, G. Pedrini, Z. Huang, S. Reichelt, and L. Cao    
*[Physics-enhanced neural network for phase retrieval from two diffraction patterns](https://doi.org/10.1364/OE.469080)*  
Opt. Express 30(18), 32680 (2022).
- L. Huang, H. Chen, T. Liu, and A. Ozcan    
*[GedankenNet: Self-supervised learning of hologram reconstruction using physics consistency](https://doi.org/10.48550/arXiv.2209.08288)*  
Preprint at Arxiv (2022).
- L. Bouchama, B. Dorizzi, J. Klossa, and Y. Gottesman    
*[A physics-inspired deep learning framework for an efficient FPM reconstruction under low overlap conditions](https://doi.org/10.1364/opticaopen.22310506.v1)*  
Preprint at Arxiv (2023).


<a name="DLinPcNRpapers"></a>
#### Physics-model-connect-network strategy 
- Y. Rivenson, Y. Zhang, H. Günaydın, D. Teng, and A. Ozcan    
*[Phase recovery and holographic image reconstruction using deep learning in neural networks](https://doi.org/)*  
Light Sci Appl 7(2), 17141 (2018).
- Y. Wu, Y. Rivenson, Y. Zhang, Z. Wei, H. Günaydin, X. Lin, and A. Ozcan    
*[Extended depth-of-field in holographic imaging using deep-learning-based autofocusing and phase recovery](https://doi.org/)*  
Optica 5(6), 704 (2018).
- [Goy et al., Phys. Rev. Lett. 2018](#Goy18prl), 
*Low Photon Count Phase Retrieval Using Deep Learning*
- J. Zhang, T. Xu, Z. Shen, Y. Qiao, and Y. Zhang    
*[Fourier ptychographic microscopy reconstruction with multiscale deep residual network](https://doi.org/)*  
Opt. Express 27(6), 8612 (2019).
- M. Deng, A. Goy, S. Li, K. Arthur, and G. Barbastathis    
*[Probing shallower: perceptual loss trained Phase Extraction Neural Network (PLT-PhENN) for artifact-free reconstruction at low photon budget](https://doi.org/)*  
Opt. Express 28(2), 2511 (2020).
- M. Deng, S. Li, A. Goy, I. Kang, and G. Barbastathis    
*[Learning to synthesize: robust phase retrieval at low photon counts](https://doi.org/)*  
Light Sci Appl 9(1), 36 (2020).
- I. Kang, F. Zhang, and G. Barbastathis    
*[Phase extraction neural network (PhENN) with coherent modulation imaging (CMI) for phase retrieval at low photon counts](https://doi.org/)*  
Opt. Express 28(15), 21578 (2020).
- I. Moon, K. Jaferzadeh, Y. Kim, and B. Javidi    
*[Noise-free quantitative phase imaging in Gabor holography with conditional generative adversarial network](https://doi.org/)*  
Opt. Express 28(18), 26284 (2020).
- [Huang et al., ACS Photonics 2021](#Huang21acsp), 
*Holographic Image Reconstruction with Phase Recovery and Autofocusing Using Recurrent Neural Networks*


<a name="DLinNiPRpapers"></a>
#### Network-in-physics-model strategy 
(trained networks as denoiser regularization)
- C. A. Metzler, P. Schniter, A. Veeraraghavan, and R. G. Baraniuk    
*[prDeep: Robust Phase Retrieval with a Flexible Deep Network](http://arxiv.org/abs/1803.00212)*  
Preprint at Arxiv (2018).
- Ç. Işıl, F. S. Oktem, and A. Koç    
*[Deep iterative reconstruction for phase retrieval](https://doi.org/10.1364/AO.58.005422)*  
Appl. Opt. 58(20), 5422 (2019).
- Z. Wu, Y. Sun, J. Liu, and U. Kamilov    
*[Online Regularization by Denoising with Applications to Phase Retrieval](https://doi.org/10.1109/ICCVW.2019.00482)*  
in 2019 IEEE/CVF International Conference on Computer Vision Workshop (ICCVW) (IEEE, 2019), pp. 3887–3895.
- C. Bai, M. Zhou, J. Min, S. Dang, X. Yu, P. Zhang, T. Peng, and B. Yao    
*[Robust contrast-transfer-function phase retrieval via flexible deep learning networks](https://doi.org/10.1364/OL.44.005141)*  
Opt. Lett. 44(21), 5141 (2019).
- Y. Wang, X. Sun, and J. W. Fleischer    
*[When deep denoising meets iterative phase retrieval](http://arxiv.org/abs/2003.01792)*  
Preprint at Arxiv (2020).
- X. Chang, L. Bian, and J. Zhang    
*[Large-scale phase retrieval](https://doi.org/10.1186/s43593-021-00004-w)*  
eLight 1(1), 4 (2021).
- S. Kumar    
*[Phase retrieval with physics informed zero-shot network](https://doi.org/10.1364/OL.433625)*  
Opt. Lett. 46(23), 5942 (2021).
- 
(untrained networks as structural-priori regularization)
- G. Jagatap and C. Hegde    
*[Phase Retrieval using Untrained Neural Network Priors](https://doi.org/)*  
in NeurIPS 2019 Workshop on Solving Inverse Problems with Deep Networks (2019).
- G. Jagatap and C. Hegde    
*[Algorithmic Guarantees for Inverse Imaging with Untrained Network Priors](https://doi.org/)*  
in Advances in Neural Information Processing Systems 32 (2019).
- K. C. Zhou and R. Horstmeyer    
*[Diffraction tomography with a deep image prior](https://doi.org/)*  
Opt. Express 28(9), 12872 (2020).
- F. Shamshad, A. Hanif, and A. Ahmed    
*[Subsampled Fourier Ptychography using Pretrained Invertible and Untrained Network Priors](http://arxiv.org/abs/2005.07026)*  
Preprint at Arxiv (2020).
- E. Bostan, R. Heckel, M. Chen, M. Kellman, and L. Waller    
*[Deep phase decoder: self-calibrating phase microscopy with an untrained deep neural network](https://doi.org/)*  
Optica 7(6), 559 (2020).
- H. Lawrence, D. A. Barmherzig, H. Li, M. Eickenberg, and M. Gabrié    
*[Phase Retrieval with Holography and Untrained Priors: Tackling the Challenges of Low-Photon Nanoscale Imaging](http://arxiv.org/abs/2012.07386)*  
Preprint at Arxiv (2021).
- F. Niknam, H. Qazvini, and H. Latifi    
*[Holographic optical field recovery using a regularized untrained deep decoder network](https://doi.org/)*  
Sci Rep 11(1), 10903 (2021).
- L. Ma, H. Wang, N. Leng, and Z. Yuan    
*[ADMM based Fourier phase retrieval with untrained generative prior](http://arxiv.org/abs/2210.12646)*  
Preprint at Arxiv (2022)
- Q. Chen, D. Huang, and R. Chen    
*[Fourier ptychographic microscopy with untrained deep neural network priors](https://doi.org/)*  
Opt. Express 30(22), 39597 (2022).

(trained networks as generative-priori regularization)
- P. Hand, O. Leong, and V. Voroninski    
*[Phase Retrieval Under a Generative Prior](https://doi.org/10.48550/arXiv.1807.04261)*  
in Advances in Neural Information Processing Systems 31 (2018).
- F. Shamshad and A. Ahmed  
*[Robust Compressive Phase Retrieval via Deep Generative Priors](https://doi.org/10.48550/arXiv.1808.05854)*  
Preprint at Arxiv (2018).
- R. Hyder, V. Shah, C. Hegde, and M. S. Asif    
*[Alternating Phase Projected Gradient Descent with Generative Priors for Solving Compressive Phase Retrieval](https://doi.org/10.1109/ICASSP.2019.8682811)*  
in ICASSP 2019 - 2019 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) (IEEE, 2019), pp. 7705–7709.
- F. Shamshad, F. Abbas, and A. Ahmed    
*[Deep Ptych: Subsampled Fourier Ptychography Using Generative Priors](https://doi.org/10.1109/ICASSP.2019.8682179)*  
in ICASSP 2019 - 2019 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) (IEEE, 2019), pp. 7720–7724.
- F. Shamshad and A. Ahmed    
*[Compressed Sensing-Based Robust Phase Retrieval via Deep Generative Priors](https://doi.org/10.1109/JSEN.2020.3018751)*  
IEEE Sensors J. 21(2), 2286–2298 (2021).
- T. Uelwer, S. Konietzny, and S. Harmeling    
*[Optimizing Intermediate Representations of Generative Models for Phase Retrieval](https://doi.org/10.48550/arXiv.2205.15617)*  
Preprint at Arxiv (2022).

<a name="DLinPiNRpapers"></a>
#### Physics-model-in-network strategy 
- C.-J. Wang, C.-K. Wen, S.-H. Tsai, and S. Jin    
*[Phase Retrieval With Learning Unfolded Expectation Consistent Signal Recovery Algorithm](https://doi.org/10.1109/LSP.2020.2990767)*  
IEEE Signal Process. Lett. 27, 780–784 (2020).
- N. Naimipour, S. Khobahi, and M. Soltanalian    
*[UPR: A Model-Driven Architecture for Deep Phase Retrieval](https://doi.org/10.1109/IEEECONF51394.2020.9443438)*  
in 2020 54th Asilomar Conference on Signals, Systems, and Computers (IEEE, 2020), pp. 205–209.
- N. Naimipour, S. Khobahi, and M. Soltanalian    
*[Unfolded Algorithms for Deep Phase Retrieval](https://doi.org/10.48550/arXiv.2012.11102)*  
Preprint at Arxiv (2020).
- F. Zhang, X. Liu, C. Guo, S. Lin, J. Jiang, and X. Ji    
*[Physics-based Iterative Projection Complex Neural Network for Phase Retrieval in Lensless Microscopy Imaging](https://doi.org/10.1109/CVPR46437.2021.01038)*  
in 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) (IEEE, 2021), pp. 10518–10526.
- B. Shi, Y. Gao, K. Jiang, and Q. Lian.    
*[Convolutional Sparse Coding with Weighted L1 Norm for Phase Retrieval: Algorithm and Its Deep Unfolded Network](https://doi.org/10.1109/ICIP46576.2022.9897593)*  
in 2022 IEEE International Conference on Image Processing (ICIP) (IEEE, 2022), pp. 1746–1750.
- X. Wu, Z. Wu, S. C. Shanmugavel, H. Z. Yu, and Y. Zhu    
*[Physics-informed neural network for phase imaging based on transport of intensity equation](https://doi.org/10.1364/OE.462844)*  
Opt. Express 30(24), 43398 (2022).
- Y. Yang, Q. Lian, X. Zhang, D. Zhang, and H. Zhang    
*[HIONet: Deep priors based deep unfolded network for phase retrieval](https://doi.org/10.1016/j.dsp.2022.103797)*  
Digital Signal Processing 132, 103797 (2022).

<a name="DLpostRpapers"></a>
### DL-post-processing for phase acquisition
<a name="DLpostNRRpapers"></a>
#### Noise reduction
- W. Jeon, W. Jeong, K. Son, and H. Yang    
*[Speckle noise reduction for digital holographic images using multi-scale convolutional neural networks](https://doi.org/7)*  
Opt. Lett. 43(17), 4240 (2018).
- G. Choi, D. Ryu, Y. Jo, Y. S. Kim, W. Park, H. Min, and Y. Park    
*[Cycle-consistent deep learning approach to coherent noise reduction in optical diffraction tomography](https://doi.org/7)*  
Opt. Express 27(4), 4927 (2019).
- J. Zhang, X. Tian, J. Shao, H. Luo, and R. Liang    
*[Phase unwrapping in optical metrology via denoised and convolutional segmentation networks](https://doi.org/7)*  
Opt. Express 27(10), 14903 (2019).
- K. Yan, Y. Yu, T. Sun, A. Asundi, and Q. Kemao    
*[Wrapped phase denoising using convolutional neural networks](https://doi.org/7)*  
Optics and Lasers in Engineering 128, 105999 (2020).
- S. Montresor, M. Tahon, A. Laurent, and P. Picart    
*[Computational de-noising based on deep learning for phase data in digital holographic interferometry](https://doi.org/7)*  
APL Photonics 5(3), 030802 (2020).
- K. Yan, L. Chang, M. Andrianakis, V. Tornari, and Y. Yu    
*[Deep Learning-Based Wrapped Phase Denoising Method for Application in Digital Holographic Speckle Pattern Interferometry](https://doi.org/7)*  
Applied Sciences 10(11), 4044 (2020).
- M. Tahon, S. Montresor, and P. Picart    
*[Towards Reduced CNNs for De-Noising Phase Images Corrupted with Speckle Noise](https://doi.org/7)*  
Photonics 8(7), 255 (2021).
- Q. Fang, H. Xia, Q. Song, M. Zhang, R. Guo, S. Montresor, and P. Picart    
*[Speckle denoising based on deep learning via a conditional generative adversarial network in digital holographic interferometry](https://doi.org/7)*  
Opt. Express 30(12), 20666 (2022).
- M. Tahon, S. Montrésor, and P. Picart    
*[Deep Learning Network for Speckle De-Noising in Severe Conditions](https://doi.org/7)*  
J. Imaging 8(6), 165 (2022).
- G. Murdaca, A. Rucci, and C. Prati    
*[Deep Learning for InSAR Phase Filtering: An Optimized Framework for Phase Unwrapping](https://doi.org/7)*  
Remote Sensing 14(19), 4956 (2022).



<a name="DLpostRERpapers"></a>
#### Resolution enhancement
- Y    
*[HIONet](https://doi.org/7)*  
Digital
- Y    
*[HIONet](https://doi.org/7)*  
Digital
- Y    
*[HIONet](https://doi.org/7)*  
Digital

1.  T. Liu, K. de Haan, Y. Rivenson, Z. Wei, X. Zeng, Y. Zhang, and A. Ozcan, "Deep learning-based super-resolution in coherent imaging systems," Preprint at https://doi.org/10.48550/arXiv.1810.06611 (2018).
2.  T. Liu, K. de Haan, Y. Rivenson, Z. Wei, X. Zeng, Y. Zhang, and A. Ozcan, "Deep learning-based super-resolution in coherent imaging systems," Sci Rep 9(1), 3926 (2019).
3.  J. Lim, A. B. Ayoub, and D. Psaltis, "Three-dimensional tomography of red blood cells using deep learning," Adv. Photon. 2(02), 1 (2020).
4.  A. Butola, S. R. Kanade, S. Bhatt, V. K. Dubey, A. Kumar, A. Ahmad, D. K. Prasad, P. Senthilkumaran, B. S. Ahluwalia, and D. S. Mehta, "High space-bandwidth in quantitative phase imaging using partially spatially coherent digital holographic microscopy and a deep neural network," Opt. Express 28(24), 36229 (2020).
5.  Y. Jiao, Y. R. He, M. E. Kandel, X. Liu, W. Lu, and G. Popescu, "Computational interference microscopy enabled by deep learning," APL Photonics 6(4), 046103 (2021).
6.  D. Ryu, D. Ryu, Y. Baek, H. Cho, G. Kim, Y. S. Kim, Y. Lee, Y. Kim, J. C. Ye, H.-S. Min, and Y. Park, "DeepRegularizer: Rapid Resolution Enhancement of Tomographic Imaging Using Deep Learning," IEEE Trans. Med. Imaging 40(5), 1508–1518 (2021).
7.  Z. Meng, G. Pedrini, X. Lv, J. Ma, S. Nie, and C. Yuan, "DL-SI-DHM: a deep network generating the high-resolution phase and amplitude images from wide-field images," Opt. Express 29(13), 19247 (2021).
8.  A.-C. Li, S. Vyas, Y.-H. Lin, Y.-Y. Huang, H.-M. Huang, and Y. Luo, "Patch-Based U-Net Model for Isotropic Quantitative Differential Phase Contrast Imaging," IEEE Trans. Med. Imaging 40(11), 3229–3237 (2021).
9.  R. K. Gupta, N. Hempler, G. P. A. Malcolm, K. Dholakia, and S. J. Powis, "High throughput hemogram of T cells using digital holographic microscopy and deep learning," Opt. Continuum 2(3), 670 (2023).

<a name="DLpostACRpapers"></a>
#### Aberration correction
- Y    
*[HIONet](https://doi.org/7)*  
Digital
- Y    
*[HIONet](https://doi.org/7)*  
Digital
- Y    
*[HIONet](https://doi.org/7)*  
Digital
1.  T. Nguyen, V. Bui, V. Lam, C. B. Raub, L.-C. Chang, and G. Nehmetallah, "Automatic phase aberration compensation for digital holographic microscopy based on deep learning background detection," Opt. Express 25(13), 15043 (2017).
2.  G. Zhang, T. Guan, Z. Shen, X. Wang, T. Hu, D. Wang, Y. He, and N. Xie, "Fast phase retrieval in off-axis digital holographic microscopy through deep learning," Opt. Express 26(15), 19388 (2018).
3.  W. Xiao, L. Xin, R. Cao, X. Wu, R. Tian, L. Che, L. Sun, P. Ferraro, and F. Pan, "Sensing morphogenesis of bone cells under microfluidic shear stress by holographic microscopy and automatic aberration compensation with deep learning," Lab Chip 21(7), 1385–1394 (2021).
4.  S. Ma, R. Fang, Y. Luo, Q. Liu, S. Wang, and X. Zhou, "Phase-aberration compensation via deep learning in digital holographic microscopy," Meas. Sci. Technol. 32(10), 105203 (2021).
5.  L.-C. Lin, C.-H. Huang, Y.-F. Chen, D. Chu, and C.-J. Cheng, "Deep learning-assisted wavefront correction with sparse data for holographic tomography," Optics and Lasers in Engineering 154, 107010 (2022).

<a name="DLpostPURpapers"></a>
#### Phase unwrapping
(Deep-learning-performed regression method, dRG)
1.  G. Dardikman and N. T. Shaked, "Phase Unwrapping Using Residual Neural Networks," in Imaging and Applied Optics 2018 (3D, AO, AIO, COSI, DH, IS, LACSEA, LS&C, MATH, PcAOP) (OSA, 2018), p. CW3B.5.
2.  G. Dardikman, N. A. Turko, and N. T. Shaked, "Deep learning approaches for unwrapping phase images with steep spatial gradients: a simulation," in 2018 IEEE International Conference on the Science of Electrical Engineering in Israel (ICSEE) (IEEE, 2018), pp. 1–4.
3.  K. Wang, Y. Li, Q. Kemao, J. Di, and J. Zhao, "One-step robust deep learning phase unwrapping," Opt. Express 27(10), 15100 (2019).
4.  J. J. He, C. Sandino, D. Zeng, S. Vasanawala, and J. Cheng, "Deep spatiotemporal phase unwrapping of phase-contrast MRI data," in Proceedings of the 27th ISMRM Annual Meeting & Exhibition, Montréal, QC, Canada (2019), pp. 11–16.
5.  K. Ryu, S.-M. Gho, Y. Nam, K. Koch, and D.-H. Kim, "Development of a deep learning method for phase unwrapping MR images," in Proc. Intl. Soc. Mag. Reson. Med. (2019), 27, p. ,4707.
6.  G. Dardikman, D. Roitshtain, S. K. Mirsky, N. A. Turko, M. Habaza, and N. T. Shaked, "PhUn-Net: ready-to-use neural network for unwrapping quantitative phase images of biological cells," Biomed. Opt. Express 11(2), 1107 (2020).
7.  Y. Qin, S. Wan, Y. Wan, J. Weng, W. Liu, and Q. Gong, "Direct and accurate phase unwrapping with deep neural network," Appl. Opt. 59(24), 7258 (2020).
8.  M. V. Perera and A. De Silva, "A Joint Convolutional and Spatial Quad-Directional LSTM Network for Phase Unwrapping," in IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) (2021), pp. 4055–4059.
9.  H. Zhou, C. Cheng, H. Peng, D. Liang, X. Liu, H. Zheng, and C. Zou, "The PHU‐NET: A robust phase unwrapping method for MRI based on deep learning," Magn Reson Med 86(6), 3321–3333 (2021).
10.  S. Park, Y. Kim, and I. Moon, "Automated phase unwrapping in digital holography with deep learning," Biomed. Opt. Express 12(11), 7064 (2021).
11.  L. Zhou, H. Yu, V. Pascazio, and M. Xing, "PU-GAN: A One-Step 2-D InSAR Phase Unwrapping Based on Conditional Generative Adversarial Network," IEEE Trans. Geosci. Remote Sensing 60, 1–10 (2022).
12.  M. Xu, C. Tang, Y. Shen, N. Hong, and Z. Lei, "PU-M-Net for phase unwrapping with speckle reduction and structure protection in ESPI," Optics and Lasers in Engineering 151, 106824 (2022).
13.  X. Xie, X. Tian, Z. Shou, Q. Zeng, G. Wang, Q. Huang, M. Qin, and X. Gao, "Deep learning phase-unwrapping method based on adaptive noise evaluation," Appl. Opt. 61(23), 6861 (2022).
14.  J. Zhao, L. Liu, T. Wang, X. Wang, X. Du, R. Hao, J. Liu, Y. Liu, and J. Zhang, "VDE-Net: a two-stage deep learning method for phase unwrapping," Opt. Express 30(22), 39794 (2022).

(Deep-learning-performed wrap count method, dWC)
1.  G. E. Spoorthi, S. Gorthi, and R. K. S. S. Gorthi, "PhaseNet: A Deep Convolutional Neural Network for Two-Dimensional Phase Unwrapping," IEEE Signal Process. Lett. 26(1), 54–58 (2018).
2.  G. Dardikman, N. A. Turko, and N. T. Shaked, "Deep learning approaches for unwrapping phase images with steep spatial gradients: a simulation," in 2018 IEEE International Conference on the Science of Electrical Engineering in Israel (ICSEE) (IEEE, 2018), pp. 1–4.
3.  J. Zhang, X. Tian, J. Shao, H. Luo, and R. Liang, "Phase unwrapping in optical metrology via denoised and convolutional segmentation networks," Opt. Express 27(10), 14903 (2019).
4.  T. Zhang, S. Jiang, Z. Zhao, K. Dixit, X. Zhou, J. Hou, Y. Zhang, and C. Yan, "Rapid and robust two-dimensional phase unwrapping via deep learning," Opt. Express 27(16), 23173 (2019).
5.  G. E. Spoorthi, R. K. Sai Subrahmanyam Gorthi, and S. Gorthi, "PhaseNet 2.0: Phase Unwrapping of Noisy Data Based on Deep Learning Approach," IEEE Trans. on Image Process. 29, 4862–4872 (2020).
6.  C. Wu, Z. Qiao, N. Zhang, X. Li, J. Fan, H. Song, D. Ai, J. Yang, and Y. Huang, "Phase unwrapping based on a residual en-decoder network for phase images in Fourier domain Doppler optical coherence tomography," Biomed. Opt. Express 11(4), 1760 (2020).
7.  Z. Zhao, B. Li, X. Kang, J. Lu, and T. Liu, "Phase unwrapping method for point diffraction interferometer based on residual auto encoder neural network," Optics and Lasers in Engineering 138, 106405 (2020).
8.  S. Zhu, Z. Zang, X. Wang, Y. Wang, X. Wang, and D. Liu, "Phase unwrapping in ICF target interferometric measurement via deep learning," Appl. Opt. 60(1), 10 (2021).
9.  K. S. Vengala, N. Paluru, and R. K. S. Subrahmanyam Gorthi, "3D deformation measurement in digital holographic interferometry using a multitask deep learning architecture," J. Opt. Soc. Am. A 39(1), 167 (2022).
10.  K. S. Vengala, V. Ravi, and G. R. K. Sai Subrahmanyam, "A Multi-task Learning for 2D Phase Unwrapping in Fringe Projection," IEEE Signal Process. Lett. 29, 797–801 (2022).
11.  J. Zhang and Q. Li, "EESANet: edge-enhanced self-attention network for two-dimensional phase unwrapping," Opt. Express 30(7), 10470 (2022).
12.  W. Huang, X. Mei, Y. Wang, Z. Fan, C. Chen, and G. Jiang, "Two-dimensional phase unwrapping by a high-resolution deep learning network," Measurement 200, 111566 (2022).
13.  Y. Wang, C. Zhou, and X. Qi, "PEENet for phase unwrapping in fringe projection profilometry," in Thirteenth International Conference on Information Optics and Photonics (CIOP 2022), Y. Yang, ed. (SPIE, 2022), p. 163.

(Deep-learning-assisted method, dAS)
1.  W. Schwartzkopf, T. E. Milner, J. Ghosh, B. L. Evans, and A. C. Bovik, "Two-dimensional phase unwrapping using neural networks," in 4th IEEE Southwest Symposium on Image Analysis and Interpretation (IEEE Comput. Soc, 2000), pp. 274–277.
2.  L. Zhou, H. Yu, and Y. Lan, "Deep Convolutional Neural Network-Based Robust Phase Gradient Estimation for Two-Dimensional Phase Unwrapping Using SAR Interferograms," IEEE Trans. Geosci. Remote Sensing 58(7), 4653–4665 (2020).
3.  F. Sica, F. Calvanese, G. Scarpa, and P. Rizzoli, "A CNN-Based Coherence-Driven Approach for InSAR Phase Unwrapping," IEEE Geosci. Remote Sensing Lett. 19, 1–5 (2020).
4.  Z. Wu, T. Wang, Y. Wang, and D. Ge, "A New Phase Unwrapping Method Combining Minimum Cost Flow with Deep Learning," in 2021 IEEE International Geoscience and Remote Sensing Symposium IGARSS (IEEE, 2021), pp. 3177–3180.
5.  H. Wang, J. Hu, H. Fu, C. Wang, and Z. Wang, "A Novel Quality-Guided Two-Dimensional InSAR Phase Unwrapping Method via GAUNet," IEEE J. Sel. Top. Appl. Earth Observations Remote Sensing 14, 7840–7856 (2021).
6.  L. Zhou, H. Yu, Y. Lan, and M. Xing, "Deep Learning-Based Branch-Cut Method for InSAR Two-Dimensional Phase Unwrapping," IEEE Trans. Geosci. Remote Sensing 60, 1–15 (2021).
7.  Z. Wu, T. Wang, Y. Wang, R. Wang, and D. Ge, "Deep-Learning-Based Phase Discontinuity Prediction for 2-D Phase Unwrapping of SAR Interferograms," IEEE Trans. Geosci. Remote Sensing 60, 1–16 (2021).
8.  L. Li, H. Zhang, Y. Tang, C. Wang, and F. Gu, "InSAR Phase Unwrapping by Deep Learning Based on Gradient Information Fusion," IEEE Geosci. Remote Sensing Lett. 19, 1–5 (2021).


<a name="DLppRpapers"></a>
### Deep learning for phase processing
<a name="DLppSRpapers"></a>
#### Segmentation
1.  T. H. Nguyen, S. Sridharan, V. Macias, A. Kajdacsy-Balla, J. Melamed, M. N. Do, and G. Popescu, "Automatic Gleason grading of prostate cancer using quantitative phase imaging and machine learning," J. Biomed. Opt 22(3), 036015 (2017).
2.  F. Yi, I. Moon, and B. Javidi, "Automated red blood cells extraction from holographic images using fully convolutional neural networks," Biomed. Opt. Express 8(10), 4466 (2017).
3.  J. Lee, H. Kim, H. Cho, Y. Jo, Y. Song, D. Ahn, K. Lee, Y. Park, and S.-J. Ye, "Deep-Learning-Based Label-Free Segmentation of Cell Nuclei in Time-Lapse Refractive Index Tomograms," IEEE Access 7, 83449–83460 (2019).
4.  E. Ahmadzadeh, K. Jaferzadeh, S. Shin, and I. Moon, "Automated single cardiomyocyte characterization by nucleus extraction from dynamic holographic images using a fully convolutional neural network," Biomed. Opt. Express 11(3), 1501 (2020).
5.  M. E. Kandel, M. Rubessa, Y. R. He, S. Schreiber, S. Meyers, L. Matter Naves, M. K. Sermersheim, G. S. Sell, M. J. Szewczyk, N. Sobh, M. B. Wheeler, and G. Popescu, "Reproductive outcomes predicted by phase imaging with computational specificity of spermatozoon ultrastructure," Proc. Natl. Acad. Sci. U.S.A. 117(31), 18302–18309 (2020).
6.  M. Lee, Y.-H. Lee, J. Song, G. Kim, Y. Jo, H. Min, C. H. Kim, and Y. Park, "Deep-learning-based three-dimensional label-free tracking and analysis of immunological synapses of CAR-T cells," eLife 9, e49023 (2020).
7.  J. Choi, H.-J. Kim, G. Sim, S. Lee, W. S. Park, J. H. Park, H.-Y. Kang, M. Lee, W. D. Heo, J. Choo, H. Min, and Y. Park, "Label-free three-dimensional analyses of live cells with deep-learning-based segmentation exploiting refractive index distributions," Preprint at https://doi.org/10.1101/2021.05.23.445351 (2021).
8.  N. Goswami, Y. R. He, Y.-H. Deng, C. Oh, N. Sobh, E. Valera, R. Bashir, N. Ismail, H. Kong, T. H. Nguyen, C. Best-Popescu, and G. Popescu, "Label-free SARS-CoV-2 detection and classification using phase imaging with computational specificity," Light Sci Appl 10(1), 176 (2021).
9.  C. Hu, S. He, Y. J. Lee, Y. He, E. M. Kong, H. Li, M. A. Anastasio, and G. Popescu, "Live-dead assay on unlabeled cells using phase imaging with computational specificity," Nat Commun 13(1), 713 (2022).
10.  J. K. Zhang, M. Fanous, N. Sobh, A. Kajdacsy-Balla, and G. Popescu, "Automatic Colorectal Cancer Screening Using Deep Learning in Spatial Light Interference Microscopy Data," Cells 11(4), 716 (2022).
11.  Y. R. He, S. He, M. E. Kandel, Y. J. Lee, C. Hu, N. Sobh, M. A. Anastasio, and G. Popescu, "Cell Cycle Stage Classification Using Phase Imaging with Computational Specificity," ACS Photonics 9(4), 1264–1273 (2022).
12.  S. Jiang, C. Guo, P. Song, T. Wang, R. Wang, T. Zhang, Q. Wu, R. Pandey, and G. Zheng, "High-throughput digital pathology via a handheld, multiplexed, and AI-powered ptychographic whole slide scanner," Lab Chip 22(14), 2657–2670 (2022).

<a name="DLppCRpapers"></a>
#### Classification
(via conventional machine learning)
1. C. L. Chen, A. Mahjoubfar, L.-C. Tai, I. K. Blaby, A. Huang, K. R. Niazi, and B. Jalali, "Deep Learning in Label-free Cell Classification," Sci Rep 6(1), 21471 (2016).
2. D. Roitshtain, L. Wolbromsky, E. Bal, H. Greenspan, L. L. Satterwhite, and N. T. Shaked, "Quantitative phase microscopy spatial signatures of cancer cells," Cytometry 91(5), 482–493 (2017).
3. J. Yoon, Y. Jo, M. Kim, K. Kim, S. Lee, S.-J. Kang, and Y. Park, "Identification of non-activated lymphocytes using three-dimensional refractive index tomography and machine learning," Sci Rep 7(1), 6654 (2017).
4. S. K. Mirsky, I. Barnea, M. Levi, H. Greenspan, and N. T. Shaked, "Automated analysis of individual sperm cells using stain-free interferometric phase microscopy and machine learning: Sperm Analysis Using Interferometry and Machine Learning," Cytometry 91(9), 893–900 (2017).
5. Y. Li, B. Cornelis, A. Dusa, G. Vanmeerbeeck, D. Vercruysse, E. Sohn, K. Blaszkiewicz, D. Prodanov, P. Schelkens, and L. Lagae, "Accurate label-free 3-part leukocyte recognition with single cell lens-free imaging flow cytometry," Computers in Biology and Medicine 96, 147–156 (2018).
6. B. Javidi, A. Markman, S. Rawat, T. O’Connor, A. Anand, and B. Andemariam, "Sickle cell disease diagnosis based on spatio-temporal cell dynamics analysis using 3D printed shearing digital holographic microscopy," Opt. Express 26(10), 13614 (2018).
7. G. Kim, Y. Jo, H. Cho, H. Min, and Y. Park, "Learning-based screening of hematologic disorders using quantitative phase imaging of individual red blood cells," Biosensors and Bioelectronics 123, 69–76 (2019).
8. Y. Ozaki, H. Yamada, H. Kikuchi, A. Hirotsu, T. Murakami, T. Matsumoto, T. Kawabata, Y. Hiramatsu, K. Kamiya, T. Yamauchi, K. Goto, Y. Ueda, S. Okazaki, M. Kitagawa, H. Takeuchi, and H. Konno, "Label-free classification of cells based on supervised machine learning of subcellular structures," PLoS ONE 14(1), e0211347 (2019).
9. V. Bianco, P. Memmolo, P. Carcagnì, F. Merola, M. Paturzo, C. Distante, and P. Ferraro, "Microplastic Identification via Holographic Imaging and Machine Learning," Advanced Intelligent Systems 2(2), 1900153 (2020).
10. A. V. Belashov, A. A. Zhikhoreva, T. N. Belyaeva, E. S. Kornilova, A. V. Salova, I. V. Semenova, and O. S. Vasyutinskii, "In vitro monitoring of photoinduced necrosis in HeLa cells using digital holographic microscopy and machine learning," J. Opt. Soc. Am. A 37(2), 346 (2020).
11. V. K. Lam, T. C. Nguyen, V. Bui, B. M. Chung, L.-C. Chang, G. Nehmetallah, and C. B. Raub, "Quantitative scoring of epithelial and mesenchymal qualities of cancer cells using machine learning and quantitative phase imaging," J. Biomed. Opt. 25(02), 026002–026002 (2020).
12. S. Park, J. W. Ahn, Y. Jo, H.-Y. Kang, H. J. Kim, Y. Cheon, J. W. Kim, Y. Park, S. Lee, and K. Park, "Label-Free Tomographic Imaging of Lipid Droplets in Foam Cells for Machine-Learning-Assisted Therapeutic Evaluation of Targeted Nanodrugs," ACS Nano 14(2), 1856–1865 (2020).
13. N. Nissim, M. Dudaie, I. Barnea, and N. T. Shaked, "Real‐Time Stain‐Free Classification of Cancer Cells and Blood Cells Using Interferometric Phase Microscopy and Machine Learning," Cytometry 99(5), 511–523 (2021).
14. V. Bianco, D. Pirone, P. Memmolo, F. Merola, and P. Ferraro, "Identification of Microplastics Based on the Fractal Properties of Their Holographic Fingerprint," ACS Photonics 8(7), 2148–2157 (2021).
15. S. K. Paidi, P. Raj, R. Bordett, C. Zhang, S. H. Karandikar, R. Pandey, and I. Barman, "Raman and quantitative phase imaging allow morpho-molecular recognition of malignancy and stages of B-cell acute lymphoblastic leukemia," Biosensors and Bioelectronics 190, 113403 (2021).
16. P. Memmolo, G. Aprea, V. Bianco, R. Russo, I. Andolfo, M. Mugnano, F. Merola, L. Miccio, A. Iolascon, and P. Ferraro, "Differential diagnosis of hereditary anemias from a fraction of blood drop by digital holography and hierarchical machine learning," Biosensors and Bioelectronics 201, 113945 (2022).
17. M. Valentino, J. Bĕhal, V. Bianco, S. Itri, R. Mossotti, G. D. Fontana, T. Battistini, E. Stella, L. Miccio, and P. Ferraro, "Intelligent polarization-sensitive holographic flow-cytometer: Towards specificity in classifying natural and microplastic fibers," Science of The Total Environment 815, 152708 (2022).
18. D. Pirone, L. Xin, V. Bianco, L. Miccio, W. Xiao, L. Che, X. Li, P. Memmolo, F. Pan, and P. Ferraro, "Identification of drug-resistant cancer cells in flow cytometry combining 3D holographic tomography with machine learning," Sensors and Actuators B: Chemical 375, 132963 (2023).

(via deep learning with only phase as input)
1.  Y. Jo, S. Park, J. Jung, J. Yoon, H. Joo, M. Kim, S.-J. Kang, M. C. Choi, S. Y. Lee, and Y. Park, "Holographic deep learning for rapid optical screening of anthrax spores," Sci. Adv. 3(8), e1700606 (2017).
2.  S. H. Karandikar, C. Zhang, A. Meiyappan, I. Barman, C. Finck, P. K. Srivastava, and R. Pandey, "Reagent-Free and Rapid Assessment of T Cell Activation State Using Diffraction Phase Microscopy and Deep Learning," Anal. Chem. 91(5), 3405–3411 (2019).
3.  M. Rubin, "TOP-GAN: Stain-free cancer cell classification using deep learning with a small training set," Medical Image Analysis 57, 176–185 (2019).
4.  J. K. Zhang, Y. R. He, and N. Sobh, "Label-free colorectal cancer screening using deep learning and spatial light interference microscopy (SLIM)," APL Photonics 5(4), 040805 (2020).
5.  A. Butola, D. Popova, D. K. Prasad, A. Ahmad, A. Habib, J. C. Tinguely, P. Basnet, G. Acharya, P. Senthilkumaran, D. S. Mehta, and B. S. Ahluwalia, "High spatially sensitive quantitative phase imaging assisted with deep neural network for classification of human spermatozoa under stressed condition," Sci Rep 10(1), 13118 (2020).
6.  Y. Li, J. Di, L. Ren, and J. Zhao, "Deep-learning-based prediction of living cells mitosis via quantitative phase microscopy," Chin. Opt. Lett. 19(5), 051701 (2021).
7.  X. Shu, S. Sansare, D. Jin, X. Zeng, K.-Y. Tong, R. Pandey, and R. Zhou, "Artificial‐Intelligence‐Enabled Reagent‐Free Imaging Hematology Analyzer," Advanced Intelligent Systems 3(8), 2000277 (2021).
8.  B. L. Reddy, R. N. Uma Mahesh, and A. Nelleri, "Deep convolutional neural network for three-dimensional objects classification using off-axis digital Fresnel holography," Journal of Modern Optics 69(13), 705–717 (2022).

(via deep learning with phase and amplitude as input)
1.  T. Pitkäaho, A. Manninen, and T. J. Naughton, "Temporal Deep Learning Classification of Digital Hologram Reconstructions of Multicellular Samples," in Biophotonics Congress: Biomedical Optics Congress 2018 (Microscopy/Translational/Brain/OTS) (OSA, 2018), p. JW3A.14.
2.  Y. Wu, A. Calis, Y. Luo, C. Chen, M. Lutton, Y. Rivenson, X. Lin, H. C. Koydemir, Y. Zhang, H. Wang, Z. Göröcs, and A. Ozcan, "Label-Free Bioaerosol Sensing Using Mobile Microscopy and Deep Learning," ACS Photonics 5(11), 4617–4627 (2018).
3.  H. H. Lam, P. W. M. Tsang, and T.-C. Poon, "Ensemble convolutional neural network for classifying holograms of deformable objects," Opt. Express 27(23), 34050 (2019).
4.  H. H. S. Lam, P. W. M. Tsang, and T.-C. Poon, "Hologram classification of occluded and deformable objects with speckle noise contamination by deep learning," J. Opt. Soc. Am. A 39(3), 411 (2022).
5.  D. Terbe, L. Orzó, and Á. Zarándy, "Classification of Holograms with 3D-CNN," Sensors 22(21), 8366 (2022).
6.  H. Lam, Y. Zhu, and P. Buranasiri, "Off-Axis Holographic Interferometer with Ensemble Deep Learning for Biological Tissues Identification," Applied Sciences 12(24), 12674 (2022).

(via deep learning with multi-wavelength phase as input)
1.  N. Singla and V. Srivastava, "Deep learning enabled multi-wavelength spatial coherence microscope for the classification of malaria-infected stages with limited labelled data size," Optics & Laser Technology 130, 106335 (2020).
2.  Ç. Işıl, K. de Haan, Z. Göröcs, H. C. Koydemir, S. Peterman, D. Baum, F. Song, T. Skandakumar, E. Gumustekin, and A. Ozcan, "Phenotypic Analysis of Microalgae Populations Using Label-Free Imaging Flow Cytometry and Deep Learning," ACS Photonics 8(4), 1232–1242 (2021).

(via deep learning with multi-temporal-dimension phase as input)
1.  H. Wang, H. Ceylan Koydemir, Y. Qiu, B. Bai, Y. Zhang, Y. Jin, S. Tok, E. C. Yilmaz, E. Gumustekin, Y. Rivenson, and A. Ozcan, "Early detection and classification of live bacteria using time-lapse coherent imaging and deep learning," Light Sci Appl 9(1), 118 (2020).
2.  S. Ben Baruch, N. Rotman-Nativ, A. Baram, H. Greenspan, and N. T. Shaked, "Cancer-Cell Deep-Learning Classification by Integrating Quantitative-Phase Spatial and Temporal Fluctuations," Cells 10(12), 3353 (2021).
3.  T. Liu, Y. Li, H. C. Koydemir, Y. Zhang, E. Yang, H. Wang, J. Li, B. Bai, and A. Ozcan, "Stain-free, rapid, and quantitative viral plaque assay using deep learning and holography," Preprint at https://doi.org/10.48550/arXiv.2207.00089 (2022).


(via deep learning with 3D refractive index as input)
1.  D. Ryu, J. Kim, D. Lim, H.-S. Min, I. Y. Yoo, D. Cho, and Y. Park, "Label-Free White Blood Cell Classification Using Refractive Index Tomography and Deep Learning," BME Front 2021, 2021/9893804 (2021).
2.  G. Kim, D. Ahn, M. Kang, J. Park, D. Ryu, Y. Jo, J. Song, J. S. Ryu, G. Choi, H. J. Chung, K. Kim, D. R. Chung, I. Y. Yoo, H. J. Huh, H. Min, N. Y. Lee, and Y. Park, "Rapid species identification of pathogenic bacteria from a minute quantity exploiting three-dimensional quantitative phase imaging and artificial neural network," Light Sci Appl 11(1), 190 (2022).

(via deep learning with amplitude or hologram as input)
1.  S.-J. Kim, C. Wang, B. Zhao, H. Im, J. Min, H. J. Choi, J. Tadros, N. R. Choi, C. M. Castro, R. Weissleder, H. Lee, and K. Lee, "Deep transfer learning-based hologram classification for molecular diagnostics," Sci Rep 8(1), 17003 (2018).
2.  Y. Zhu, C. Hang Yeung, and E. Y. Lam, "Digital holographic imaging and classification of microplastics using deep transfer learning," Appl. Opt. 60(4), A38 (2021).
3.  M. Delli Priscoli, P. Memmolo, G. Ciaparrone, V. Bianco, F. Merola, L. Miccio, F. Bardozzo, D. Pirone, M. Mugnano, F. Cimmino, M. Capasso, A. Iolascon, P. Ferraro, and R. Tagliaferri, "Neuroblastoma Cells Classification Through Learning Approaches by Direct Analysis of Digital Holograms," IEEE J. Select. Topics Quantum Electron. 27(5), 1–9 (2021).
4.  Y. Zhu, C. Hang Yeung, and E. Y. Lam, "Microplastic pollution monitoring with holographic classification and deep learning," J. Phys. Photonics 3(2), 024013 (2021).
5.  D. Chen, Z. Wang, K. Chen, Q. Zeng, L. Wang, X. Xu, J. Liang, and X. Chen, "Classification of unlabeled cells using lensless digital holographic images and deep neural networks," Quant Imaging Med Surg 11(9), 4137–4148 (2021).
6.  L. MacNeil, S. Missan, J. Luo, T. Trappenberg, and J. LaRoche, "Plankton classification with high-throughput submersible holographic microscopy and transfer learning," BMC Ecol Evo 21(1), 123 (2021).
7.  Y. Zhu, H. K. A. Lo, C. H. Yeung, and E. Y. Lam, "Microplastic pollution assessment with digital holography and zero-shot learning," APL Photonics 7(7), 076102 (2022).

<a name="DLppIMTRpapers"></a>
#### Imaging modal transformation
(Phase to bright-field or stained bright-field images)
1.  Y. Wu, Y. Luo, G. Chaudhari, Y. Rivenson, A. Calis, K. de Haan, and A. Ozcan, "Bright-field holography: cross-modality deep learning enables snapshot 3D imaging with bright-field contrast using a single hologram," Light Sci Appl 8(1), 25 (2019).
2.  T. Liu, Z. Wei, Y. Rivenson, K. Haan, Y. Zhang, Y. Wu, and A. Ozcan, "Deep learning‐based color holographic microscopy," J. Biophotonics 12(11), e201900107 (2019).
3.  Y. Rivenson, T. Liu, Z. Wei, Y. Zhang, K. de Haan, and A. Ozcan, "PhaseStain: the digital staining of label-free quantitative phase microscopy images using deep learning," Light Sci Appl 8(1), 23 (2019).
4.  Y. N. Nygate, M. Levi, S. K. Mirsky, N. A. Turko, M. Rubin, I. Barnea, G. Dardikman-Yoffe, M. Haifler, A. Shalev, and N. T. Shaked, "Holographic virtual staining of individual biological cells," Proc. Natl. Acad. Sci. U.S.A. 117(17), 9223–9231 (2020).
5.  R. Wang, P. Song, S. Jiang, C. Yan, J. Zhu, C. Guo, Z. Bian, T. Wang, and G. Zheng, "Virtual brightfield and fluorescence staining for Fourier ptychography via unsupervised deep learning," Opt. Lett. 45(19), 5405 (2020).
6.  D. Terbe, L. Orzó, and Á. Zarándy, "Deep-learning-based bright-field image generation from a single hologram using an unpaired dataset," Opt. Lett. 46(22), 5567 (2021).

(Phase to fluorescence images)
1.  S.-M. Guo, L.-H. Yeh, J. Folkesson, I. E. Ivanov, A. P. Krishnan, M. G. Keefe, E. Hashemi, D. Shin, B. B. Chhun, N. H. Cho, M. D. Leonetti, M. H. Han, T. J. Nowakowski, and S. B. Mehta, "Revealing architectural order with quantitative label-free imaging and deep learning," eLife 9, e55502 (2020).
2.  M. E. Kandel, Y. R. He, Y. J. Lee, T. H.-Y. Chen, K. M. Sullivan, O. Aydin, M. T. A. Saif, H. Kong, N. Sobh, and G. Popescu, "Phase imaging with computational specificity (PICS) for measuring dry mass changes in sub-cellular compartments," Nat Commun 11(1), 6256 (2020).
3.  M. E. Kandel, E. Kim, Y. J. Lee, G. Tracy, H. J. Chung, and G. Popescu, "Multiscale Assay of Unlabeled Neurite Dynamics Using Phase Imaging with Computational Specificity," ACS Sens. 6(5), 1864–1874 (2021).
4.  S. Guo, Y. Ma, Y. Pan, Z. J. Smith, and K. Chu, "Organelle-specific phase contrast microscopy enables gentle monitoring and analysis of mitochondrial network dynamics," Biomed. Opt. Express 12(7), 4363 (2021).
5.  X. Chen, M. E. Kandel, S. He, C. Hu, Y. J. Lee, K. Sullivan, G. Tracy, H. J. Chung, H. J. Kong, M. Anastasio, and G. Popescu, "Artificial confocal microscopy for deep label-free imaging," Preprint at https://doi.org/10.48550/arXiv.2110.14823 (2021).
6.  X. Chen, M. E. Kandel, S. He, C. Hu, Y. J. Lee, K. Sullivan, G. Tracy, H. J. Chung, H. J. Kong, M. Anastasio, and G. Popescu, "Artificial confocal microscopy for deep label-free imaging," Nat. Photon. 17(3), 250–258 (2023).

(3D refractive index to fluorescence images)
1.  Y. Jo, "Label-free multiplexed microtomography of endogenous subcellular dynamics using generalizable deep learning," Nature Cell Biology 23(12), 1329–1337 (2021).

****
<a name="papers"></a>
# Review/Tutorial papers
(In chronological order)

<a name="PApapers"></a>
## Conventional phase acquisition

- Y. Shechtman, Y. C. Eldar, O. Cohen, H. N. Chapman, J. Miao, and M. Segev  
*[Phase Retrieval with Application to Optical Imaging: A contemporary overview](https://doi.org/10.1109/MSP.2014.2352673),*  
IEEE Signal Process. Mag. 32(3), 87–109 (2015).

- Y. Park, C. Depeursinge, and G. Popescu  
*[Quantitative phase imaging in biomedicine](https://doi.org/10.1038/s41566-018-0253-x),*  
Nature Photon. 12(10), 578–589 (2018).

- T. Latychevskaia  
*[Iterative phase retrieval for digital holography: tutorial](https://doi.org/10.1364/JOSAA.36.000D31),*  
J. Opt. Soc. Am. A 36(12), D31 (2019).

- H. Yu, Y. Lan, Z. Yuan, J. Xu, and H. Lee  
*[Phase Unwrapping in InSAR: A Review](https://doi.org/10.1109/MGRS.2018.2873644),*  
IEEE Geosci. Remote Sens. Mag. 7(1), 40–58 (2019).

- T. Cacace, V. Bianco, and P. Ferraro  
*[Quantitative phase imaging trends in biomedical applications](https://doi.org/10.1016/j.optlaseng.2020.106188),*  
Optics and Lasers in Engineering 135, 106188 (2020).

- J. T. Sheridan, R. K. Kostuk, A. F. Gil, Y. Wang, W. Lu, H. Zhong, Y. Tomita, C. Neipp, J. Francés, S. Gallego, I. Pascual, V. Marinova, S.-H. Lin, K.-Y. Hsu, F. Bruder, S. Hansen, C. Manecke, R. Meisenheimer, C. Rewitz, T. Rölle, S. Odinokov, O. Matoba, M. Kumar, X. Quan, Y. Awatsuji, P. W. Wachulak, A. V. Gorelaya, A. A. Sevryugin, E. V. Shalymov, V. Yu Venediktov, R. Chmelik, M. A. Ferrara, G. Coppola, A. Márquez, A. Beléndez, W. Yang, R. Yuste, A. Bianco, A. Zanutta, C. Falldorf, J. J. Healy, X. Fan, B. M. Hennelly, I. Zhurminsky, M. Schnieper, R. Ferrini, S. Fricke, G. Situ, H. Wang, A. S. Abdurashitov, V. V. Tuchin, N. V. Petrov, T. Nomura, D. R. Morim, and K. Saravanamuttu  
*[Roadmap on holography](https://doi.org/10.1088/2040-8986/abb3a4),*  
J. Opt. 22(12), 123002 (2020).

- C. Zuo, J. Li, J. Sun, Y. Fan, J. Zhang, L. Lu, R. Zhang, B. Wang, L. Huang, and Q. Chen  
*[Transport of intensity equation: a tutorial](https://doi.org/10.1016/j.optlaseng.2020.106187),*  
Optics and Lasers in Engineering 106187 (2020).

- V. Balasubramani, M. Kujawińska, C. Allier, V. Anand, C.-J. Cheng, C. Depeursinge, N. Hai, S. Juodkazis, J. Kalkman, A. Kuś, M. Lee, P. J. Magistretti, P. Marquet, S. H. Ng, J. Rosen, Y. K. Park, and M. Ziemczonok  
*[Roadmap on Digital Holography-Based Quantitative Phase Imaging](https://doi.org/10.3390/jimaging7120252),*  
J. Imaging 7(12), 252 (2021).

- B. Javidi, A. Carnicer, A. Anand, G. Barbastathis, W. Chen, P. Ferraro, J. W. Goodman, R. Horisaki, K. Khare, M. Kujawinska, R. A. Leitgeb, P. Marquet, T. Nomura, A. Ozcan, Y. Park, G. Pedrini, P. Picart, J. Rosen, G. Saavedra, N. T. Shaked, A. Stern, E. Tajahuerce, L. Tian, G. Wetzstein, and M. Yamaguchi  
*[Roadmap on digital holography [Invited]](https://doi.org/10.1364/OE.435915),*  
Opt. Express 29(22), 35078 (2021).

- G. Zheng, C. Shen, S. Jiang, P. Song, and C. Yang  
*[Concept, implementations and applications of Fourier ptychography](https://doi.org/10.1038/s42254-021-00280-y),*  
Nat. Rev. Phys. 3(3), 207–223 (2021).

- V. Petrov, A. Pogoda, V. Sementin, A. Sevryugin, E. Shalymov, D. Venediktov, and V. Venediktov  
*[Advances in Digital Holographic Interferometry](https://doi.org/10.3390/jimaging8070196),*  
J. Imaging 8(7), 196 (2022).

- T. L. Nguyen, S. Pradeep, R. L. Judson-Torres, J. Reed, M. A. Teitell, and T. A. Zangle  
*[Quantitative Phase Imaging: Recent Advances and Expanding Potential in Biomedicine](https://doi.org/10.1021/acsnano.1c11507),*  
ACS Nano 16(8), 11516–11544 (2022).

- G. Baffou  
*[Wavefront Microscopy Using Quadriwave Lateral Shearing Interferometry: From Bioimaging to Nanophotonics](https://doi.org/10.1021/acsphotonics.2c01238),*  
ACS Photonics 10(2), 322–339 (2023).

<a name="DLpapers"></a>
## Deep-learning-based phase acquisition

- Y. Jo, H. Cho, S. Y. Lee, G. Choi, G. Kim, H. Min, and Y. Park  
*[Quantitative Phase Imaging and Artificial Intelligence: A Review](https://doi.org/10.1109/JSTQE.2018.2859234),*  
IEEE J. Select. Topics Quantum Electron. 25(1), 1–14 (2019).

- Y. Rivenson, Y. Wu, and A. Ozcan  
*[Deep learning in holography and coherent imaging](https://doi.org/10.1038/s41377-019-0196-0),*  
Light Sci. Appl. 8(1), 85 (2019).

- G. Ongie, A. Jalal, C. A. Metzler, R. G. Baraniuk, A. G. Dimakis, and R. Willett  
*[Deep Learning Techniques for Inverse Problems in Imaging](https://doi.org/10.48550/arXiv.2005.06001),*  
arXiv:2005.06001 (2020).

- T. Zeng, Y. Zhu, and E. Y. Lam  
*[Deep learning for digital holography: a review](https://doi.org/10.1364/OE.443367),*  
Opt. Express 29(24), 40572 (2021).

- L. Zhou, H. Yu, Y. Lan, and  m. Xing  
*[Artificial Intelligence In Interferometric Synthetic Aperture Radar Phase Unwrapping: A Review](https://doi.org/10.1109/MGRS.2021.3065811),*  
IEEE Geosci. Remote Sens. Mag. 2–20 (2021).

- C. Zuo, J. Qian, S. Feng, W. Yin, Y. Li, P. Fan, J. Han, K. Qian, and Q. Chen  
*[Deep learning in optical metrology: a review](https://doi.org/10.1038/s41377-022-00714-x),*  
Light Sci. Appl. 11(1), 39 (2022).

- Y. Guo, L. Zhong, L. Min, J. Wang, Y. Wu, K. Chen, K. Wei, and C. Rao  
*[Adaptive optics based on machine learning: a review](https://doi.org/10.37188/lam.2022.013),*  
Opto-Electronic Advances 5(7), 200082–200082 (2022).

- T. Shimobaba, D. Blinder, T. Birnbaum, I. Hoshi, H. Shiomi, P. Schelkens, and T. Ito  
*[Deep-Learning Computational Holography: A Review](https://doi.org/10.3389/fphot.2022.854391),*  
Front. Photon. 3, 854391 (2022).

- A. Qayyum, I. Ilahi, F. Shamshad, F. Boussaid, M. Bennamoun, and J. Qadir  
*[Untrained Neural Network Priors for Inverse Imaging Problems: A Survey](https://doi.org/10.1109/TPAMI.2022.3204527),*  
IEEE Trans. Pattern Anal. Mach. Intell. 45(5), 6511–6536 (2022).

- G. Situ  
*[Deep holography](https://doi.org/10.37188/lam.2022.013),*  
Light Advanced Manufacturing 3(2), 1 (2022).

- K. Wang, Q. Kemao, J. Di, and J. Zhao  
*[Deep learning spatial phase unwrapping: a comparative review](https://doi.org/10.1117/1.APN.1.1.014001),*  
Adv. Photon. Nexus 1(1), 014001 (2022).

- J. Dong, L. Valzania, A. Maillard, T. Pham, S. Gigan, and M. Unser  
*[Phase Retrieval: From Computational Imaging to Machine Learning: A tutorial](https://doi.org/10.1109/MSP.2022.3219240),*  
IEEE Signal Process. Mag. 40(1), 45–57 (2023).


****
<a name="BK"></a>
# Books
(In chronological order)  

- D. C. Ghiglia and M. D. Pritt  
*[Two-Dimensional Phase Unwrapping: Theory, Algorithms, and Software](https://www.wiley.com/en-dk/Two+Dimensional+Phase+Unwrapping:+Theory,+Algorithms,+and+Software-p-9780471249351),*  
(Wiley, 1998).

- J. W. Goodman  
*[Introduction to Fourier Optics](https://link.springer.com/book/9780974707723),*  
3rd ed (Roberts & Co, 2005).

- E. H. Duke and S. R. Aguirre  
*[3D Imaging: Theory, Technology and Applications, Computer Science, Technology and Applications](https://www.proquest.com/legacydocview/EBC/3018197?accountid=14548),*  
(Nova Science Publishers, 2010).

- T. Tishko, D. Tishko, and V. P. Titar  
*[Holographic Microscopy of Phase Microscopic Objects: Theory and Practice](https://doi.org/10.1142/7512),*  
(World Scientific Publishing Co., 2011).

- M. Mir, B. Bhaduri, R. Wang, R. Zhu, and G. Popescu  
*[Quantitative Phase Imaging](https://doi.org/10.1016/B978-0-44-459422-8.00003-5),*  
in Progress in Optics (Elsevier, 2012), 57, pp. 133–217.

- Q. Kemao   
*[Windowed Fringe Pattern Analysis](https://doi.org/10.1117/3.1002080),*  
(SPIE, 2013).

- B. Javidi, E. Tajahuerce, and P. Andres  
*[Multi-Dimensional Imaging](https://ieeexplore.ieee.org/servlet/opac?bknumber=6798070),*  
(Cambridge University Press, (John Wiley & Sons Inc, 2014).

- T.-C. Poon and J.-P. Liu  
*[Introduction to Modern Digital Holography: With MATLAB](https://doi.org/10.1017/CBO9781139061346),*  
(Cambridge University Press, 2014).

- M. Servín, J. Antonio Quiroga, J. Moisés Padilla, J. A. Quiroga, J. M. Padilla, and J. M. Padilla  
*[Fringe Pattern Analysis for Optical Metrology: Theory, Algorithms, and Applications](https://www.wiley.com/en-us/Fringe+Pattern+Analysis+for+Optical+Metrology:+Theory,+Algorithms,+and+Applications-p-9783527411528),*  
(Wiley-VCH, 2014).

- C. Liu, S. Wang, and S. P. Veetil  
*[Computational Optical Phase Imaging, Progress in Optical Science and Photonics](https://link.springer.com/book/10.1007/978-981-19-1641-0),*  
(Springer Singapore, 2022), 21.




****
<a name="DT"></a>
# Dissertations and Thesis
(In chronological order)

- George Barbastathis,  
*[Intelligent holographic databases](https://resolver.caltech.edu/CaltechETD:etd-03172008-142604)*,  
Ph.D. Thesis, California Institute of Technology, 1997. [PDF](https://thesis.library.caltech.edu/986/1/Barbastathis_g_1998.pdf)  

- Stephen A. Boppart,  
*[Surgical diagnostics, guidance, and intervention using optical coherence tomography](http://hdl.handle.net/1721.1/9889)*,  
Ph.D. Thesis, Massachusetts Institute of Technology, 1998. [PDF](https://dspace.mit.edu/bitstream/handle/1721.1/9889/41862022-MIT.pdf)

- Changhuei Yang,  
*[Harmonic phase based low coherence interferometry : a method for studying the dynamics and structures of cells](http://hdl.handle.net/1721.1/28242)*,  
Ph.D. Thesis, Massachusetts Institute of Technology, 2002. [PDF](https://dspace.mit.edu/bitstream/handle/1721.1/28242/50547882-MIT.pdf)

- Laura Waller,  
*[Computational phase imaging based on intensity transport](http://hdl.handle.net/1721.1/60821)*,  
Ph.D. Thesis, Massachusetts Institute of Technology, 2010.  [PDF](https://dspace.mit.edu/bitstream/handle/1721.1/60821/696796127-MIT.pdf)

- Guoan Zheng,  
*[Innovations in Imaging System Design: Gigapixel, Chip-Scale and MultiFunctional Microscopy](https://resolver.caltech.edu/CaltechTHESIS:10102012-101657790)*,  
Ph.D. Thesis, California Institute of Technology, 2012.  [PDF](https://thesis.library.caltech.edu/7234/4/Zheng_Guoan_Final_Thesis_12_17_2012.pdf)

- YongKeun Park,  
*[Pathophysiology of human red blood cell probed by quantitative phase microscopy](http://hdl.handle.net/1721.1/58092)*,  
Ph.D. Thesis, Massachusetts Institute of Technology, 2013.  [PDF](https://dspace.mit.edu/bitstream/handle/1721.1/58092/656250904-MIT.pdf)

- Hoa Pham,  
*[Real-time quantitative phase imaging for cell studies](http://hdl.handle.net/2142/45508)*,   
Ph.D. Thesis, University of Illinois at Urbana-Champaign, 2013.  [PDF](https://www.ideals.illinois.edu/items/45490/bitstreams/134768/object?dl=1)

- Lei Tian,  
*[Compressive phase retrieval](http://hdl.handle.net/1721.1/81756)*,  
Ph.D. Thesis, Massachusetts Institute of Technology, 2013.  [PDF](https://dspace.mit.edu/bitstream/handle/1721.1/81756/860986128-MIT.pdf)

- Mustafa Mir,    
*[Quantitative phase imaging for cellular biology](http://hdl.handle.net/2142/45668)*,   
Ph.D. Thesis, University of Illinois at Urbana-Champaign, 2013.  [PDF](https://www.ideals.illinois.edu/items/45650/bitstreams/135201/object?dl=1)

- Renjie Zhou,  
*[Interferometric light microscopy for wafer defect inspection and three-dimensional object reconstruction](http://hdl.handle.net/2142/88067)*,   
Ph.D. Thesis, University of Illinois at Urbana-Champaign, 2013.  [PDF](https://www.ideals.illinois.edu/items/73166/bitstreams/193614/object?dl=1)

- Nathan D. Shemonski,   
*[In vivo human computed optical interferometric tomography](http://hdl.handle.net/2142/73035)*,   
Ph.D. Thesis, University of Illinois at Urbana-Champaign, 2015.  [PDF](https://www.ideals.illinois.edu/items/73224/bitstreams/193791/object?dl=1)

- Dennis J. Lee,  
*[Computational optical imaging: Applications in synthetic aperture imaging, phase retrieval, and digital holography](https://docs.lib.purdue.edu/open_access_dissertations/500)*,   
Ph.D. Thesis, Purdue University, 2015.  [PDF](https://docs.lib.purdue.edu/cgi/viewcontent.cgi?article=1406&context=open_access_dissertations)

- Tae-Woo Kim,   
*[Quantitative phase imaging: advances to 3D imaging and applications to neuroscience](https://hdl.handle.net/2142/72977)*,   
Ph.D. Thesis, University of Illinois at Urbana-Champaign, 2015.  [PDF](https://www.ideals.illinois.edu/items/89347/bitstreams/229128/object?dl=1)

- Chien-Hung Lu,   
*[Computational Phase Imaging in Nonlinear and Quantum Systems](http://arks.princeton.edu/ark:/88435/dsp01k643b3556)*,   
Ph.D. Thesis, Princeton University, 2015.  [PDF](https://dataspace.princeton.edu/bitstream/88435/dsp01k643b3556/1/Lu_princeton_0181D_11552.pdf)

- Shamira Sridharan,   
*[Applications of quantitative phase imaging for pathology](http://hdl.handle.net/2142/88244)*,   
Ph.D. Thesis, University of Illinois at Urbana-Champaign, 2015.  [PDF](https://www.ideals.illinois.edu/items/89524/bitstreams/229508/object?dl=1)

- Tan Huu Nguyen,   
*[Computational phase imaging for biomedical applications](http://hdl.handle.net/2142/95321)*,   
Ph.D. Thesis, University of Illinois at Urbana-Champaign, 2016.  [PDF](https://www.ideals.illinois.edu/items/98436/bitstreams/315324/object?dl=1)

- Chandrabhan Seniya,  
*[A flexible low-cost quantitative phase imaging microscopy system for label-free imaging of multi-cellular biological samples]( http://webcat.warwick.ac.uk/record=b3184498~S1)*,   
Ph.D. Thesis, University of Warwick, 2018.  [PDF](http://wrap.warwick.ac.uk/106451/1/WRAP_Theses_Seniya_2018.pdf)

- Aamod Shanker,  
*[Differential methods in phase imaging for optical lithography](http://www2.eecs.berkeley.edu/Pubs/TechRpts/2018/EECS-2018-160.html)*,   
Ph.D. Thesis, University of California, Berkeley, 2018.  [PDF](http://www2.eecs.berkeley.edu/Pubs/TechRpts/2018/EECS-2018-160.pdf)

- Shuai Li,  
*[Computational imaging through deep learning](https://hdl.handle.net/1721.1/122070)*,   
Ph.D. Thesis, Massachusetts Institute of Technology, 2019.  [PDF](https://dspace.mit.edu/bitstream/handle/1721.1/122070/1117711022-MIT.pdf)

- David A. Barmherzig,  
*[The Phase Retrieval Problem: Theory, Algorithms, and Applications](https://purl.stanford.edu/tw768tw9748)*,   
Ph.D. Thesis, Stanford University, 2019. [PDF](https://stacks.stanford.edu/file/druid:tw768tw9748/BarmherzigDissertationUpload-augmented.pdf)  

- Yichen Wu,  
*[Deep Learning-enabled Computational Imaging in Optical Microscopy and Air Quality Monitoring](https://escholarship.org/uc/item/1249c1bv)*,   
Ph.D. Thesis, University of California, Los Angeles, 2019.  [PDF](https://escholarship.org/content/qt1249c1bv/qt1249c1bv.pdf?t=pzmaiu)

- Michael Kellman,  
*[Physics-based Learning for Large-scale Computational Imaging](https://www2.eecs.berkeley.edu/Pubs/TechRpts/2020/EECS-2020-167.html)*,   
Ph.D. Thesis, University of California, Berkeley, 2020.  [PDF](http://www2.eecs.berkeley.edu/Pubs/TechRpts/2020/EECS-2020-167.pdf)

- Zhuoqun Zhang,  
*[Analysis and Development of Phase Retrieval Algorithms for Ptychography](https://etheses.whiterose.ac.uk/30033/)*,   
Ph.D. Thesis, University of Sheffield, 2021. [PDF](https://etheses.whiterose.ac.uk/30033/1/zhuoqun_zhang_thesis_160251201_Corrected.pdf)

- Obed A. Ayisi,  
*[Multiple-Wavelength Phase Retrieval With Digital Holographic Microscopy](https://openknowledge.nau.edu/id/eprint/5717)*,   
Masters Thesis, Northern Arizona University, 2021.

- Tairan Liu,  
*[Deep Learning in Optical Microscopy, Holographic Imaging and Sensing](https://escholarship.org/uc/item/8k03d1g2)*,   
Ph.D. Thesis, University of California, Los Angeles, 2022. 

- Marissa A. Morado,  
*[Solving the phase retrieval problem using an artificial neural network](http://hdl.handle.net/20.500.12680/cv43p355k)*,   
Ph.D. Thesis, California State University, Fresno, 2022. [PDF](https://scholarworks.calstate.edu/downloads/44558m79w)
