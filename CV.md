---
title: "Curriculum Vitae"
layout: page
sitemap:
  lastmod: 2024-12-07
  exclude: 'no'
---

<style>
  @media (max-width: 575.98px) {
    .logo {
      display: none;
    }
    .CV-subheader {
      padding-left: 5px;
    }
    .CV-desc {
      padding-left: 20px;
    }
  }

  @media (min-width: 576px) {
    .logo {
      display: initial;
    }
    .CV-subheader {
      padding-left: 60px;
    }
    .CV-desc {
      padding-left: 60px;
    }
  }
</style>

<!-- FontAwesome integration -->
<script src="https://kit.fontawesome.com/c8c14a8a7c.js" crossorigin="anonymous"></script>

<a id="Top" class="section-ID"></a>

<p>View the CV as a pdf: <a href="/assets/documents/Thomas_S_Binns-CV.pdf" target="_blank"><i class="fa-solid fa-file-pdf"></i></a></p>

<!-- Topbar for navigation of publications by year -->
<div class="dropdown">
  <button onclick="toggle_show()" class="dropdown_button"><i class="fa-solid fa-bars"></i>&nbsp;&nbsp;Sections</button>
  <div id="dropdown_menu" class="dropdown_content">
    <a href="#Top">Top</a>
    <a href="#Education">Education</a>
    <a href="#Experience">Experience</a>
    <a href="#OSS">Open-Source Software</a>
    <a href="#Publications">Publications & Talks</a>
    <a href="#Funding-Awards">Funding & Awards</a>
    <a href="#Organisations">Organisations</a>
    <a href="#Teaching">Teaching</a>
    <a href="#Courses">Courses</a>
    <a href="#References">References</a>
  </div>
</div>


<!-- Education -->
<!-- Main -->
<h1 style="padding-bottom: 0; margin-bottom: 0"><a id="Education" class="section-ID">Education</a></h1>

<div>
  <h3 class="CV-header"><a id="Charite_PhD" class="section-ID">2021 - Present</a></h3>
    <img class="logo" src="/assets/images/Logo-Charite.png">
    <h4 class="CV-subheader">
      &mdash; Charité - Universitätsmedizin Berlin, Germany<br>
      &mdash; PhD Computational Neuroscience
    </h4>
    <p class="CV-desc">
      For the project of my <a href="#PhD_Fellowship">fellowship-funded PhD</a>, I am investigating invasive neural recordings from Parkinson's disease patients to identify disease mechanisms and biomarkers for use in machine learning-based adaptive deep brain stimulation treatment. Supervisors: Prof. Wolf-Julian Neumann and Prof. Stefan Haufe. For results, see my pre-print in revision at <i>Nature Communications</i> (Binns <i>et al.</i>, DOI: <a href="https://doi.org/10.1101/2024.04.14.586969" target="_blank">10.1101/2024.04.14.586969</a>).
      <div style="margin-bottom: 30px;" id="PhD_Desc"> <!-- COLLAPSIBLE -->
        <button type="button" class="collapsible">View Description</button>
        <div class="collapsible_content">
          <p>
            Deep brain stimulation (DBS) is a brain circuit intervention that can modulate distinct neural pathways for the alleviation of neurological symptoms in patients with brain disorders. In Parkinson's disease, subthalamic DBS clinically mimics the effect of dopaminergic drug treatment, but the shared pathway mechanisms on cortex-basal ganglia networks are unknown. To address this critical knowledge gap, fully-invasive neural multisite recordings in patients undergoing DBS surgery were combined with MRI-based whole-brain connectomics.<br>
            <br>
            The findings demonstrate that dopamine and DBS exert distinct mesoscale effects through modulation of local neural population synchrony. In contrast, at the macroscale, DBS mimics dopamine in its suppression of excessive interregional network synchrony associated with indirect and hyperdirect cortex-basal ganglia pathways. Our results provide a better understanding of the circuit mechanisms of dopamine and DBS, laying the foundation for advanced closed-loop neurostimulation therapies.
          </p>
        </div>
      </div>
    </p>

  <h3 class="CV-header"><a id="Abdn_MSci" class="section-ID">2016 - 2021</a></h3>
    <img class="logo" src="/assets/images/Logo-UoA.png">
    <h4 class="CV-subheader">
      &mdash; University of Aberdeen, UK<br>
      &mdash; MSci (Hons) Neuroscience with Psychology with Industrial Placement, First-Class Honours
    </h4>
    <p class="CV-desc">
      <b>Industrial Placement (Master's) thesis:</b><br>
      “Investigating neural precursors of self-initiated action using machine learning techniques”. First-Class. Placement at the Bernstein Center for Computational Neuroscience, Berlin, Germany. Supervisors: Dr. Matthias Schultze-Kraft and Prof. John-Dylan Haynes. <a href="#Haynes_Lab">View associated experience.</a>
      <div style="margin-bottom: 30px;" id="Master_Desc"> <!-- COLLAPSIBLE -->
        <button type="button" class="collapsible">View Description</button>
        <div class="collapsible_content">
          <p>
            The readiness potential (RP) is a slow, negative electrical potential preceding voluntary actions observed in EEG recordings. According to the classical interpretation, the RP reflects movement preparation and should only be found immediately prior to voluntary action. In contrast, the stochastic accumulator model argues that the RP is the result of accumulated neural activity and does not reflect movement preparation. One prediction derived from this accumulator model is that events resembling the RP should be found throughout the EEG data of tasks where voluntary actions are permitted. This prediction was tested using machine learning techniques.<br>
            <br>
            Events resembling the spatio-temporal profiles of the RP were identified in the EEG data, however there were discrepancies between these events and details of the prediction of the model. Yet, these events were not found to be false positives resulting from noise in the EEG recordings, raising the possibility that these events were related to voluntary action and the RP in some manner. This provides tentative support for the stochastic accumulator model.
          </p>
        </div>
      </div>
    </p>
    <p class="CV-desc">
      <b>Honours (Bachelor's) thesis:</b><br>
      “Investigating the neuromodulation of striatal activity <i>in silico</i>”. First-Class. Supervisor: Dr. Antonio Gonzalez. <a href="#CAP_Lab">View associated experience.</a>
      <div style="margin-bottom: 30px;" id="Bachelor_Desc"> <!-- COLLAPSIBLE -->
        <button type="button" class="collapsible">View Description</button>
        <div class="collapsible_content">
          <p>
            The dendritic plateau potential is thought to shape information processing in striatal projection neurons. The effect of cholinergic and dopaminergic modulation on the plateau potential and the spiking activity of striatal projection neurons was investigated <i>in silico</i>. Plateau potentials were generated with spatially clustered excitatory inputs to dendrites, and the efficacy of cortico-striatal inputs at triggering cell spiking in the presence and absence of cholinergic and dopaminergic modulation were observed.<br>
            <br>
            There were some instances of dopaminergic modulation in which the probabilities of cells spiking were altered, however changes in spiking were largely attributed to alterations in cell excitability. It is concluded that acetylcholine and dopamine do not influence striatal information processing through altering plateau potentials induced by clustered excitatory inputs, with the persistence of the plateau potential supporting its proposed essential role in striatal information processing.
          </p>
        </div>
      </div>
    </p>
</div>


<!-- Experience -->
<hr>
<h1><a id="Experience" class="section-ID">Experience</a></h1>

<div>
  <h3 class="CV-header"><a id="ICN_Lab" class="section-ID">07/2021 - Present</a></h3>
    <img class="logo" src="/assets/images/Logo-ICN.png">
    <h4 class="CV-subheader">
      &mdash; Interventional and Cognitive Neuromodulation Group, Charité – Universitätsmedizin Berlin, Germany <a href="https://www.icneuromodulation.org/" target="_blank"><i class="fa-solid fa-link"></i></a><br>
      &mdash; Role: Research Scientist<br>
      &mdash; Supervisor: Prof. Wolf-Julian Neumann
    </h4>
    <p class="CV-desc">
      For the project of my <a href="#Charite_PhD">PhD</a>, I am investigating oscillatory activity in invasive neural recordings from Parkinson's disease patients to identify biomarkers for use in next-generation, machine learning-based deep brain stimulation treatments (see my pre-print in revision at <i>Nature Communications</i>, Binns <i>et al.</i>, DOI: <a href="https://doi.org/10.1101/2024.04.14.586969" target="_blank">10.1101/2024.04.14.586969</a> for results). Furthermore, I have written and contributed to open-source packages, making the advanced signal analysis techniques which I am using in my project available to the wider community (see my <a href="#OSS">open-source software work</a> for more information), in collaboration with my work in the <a href="#QAI_Lab">Quality in Artificial Intelligence Group</a>. Through this project, I am further developing my signal analysis and Python programming skills, gaining experience with open-source software development, as well as gaining an in-depth understanding of movement disorders and brain-computer interfaces.
    </p>

  <h3 class="CV-header"><a id="QAI_Lab" class="section-ID">03/2022 - Present</a></h3>
    <img class="logo" src="/assets/images/Logo-QAI.png">
    <h4 class="CV-subheader">
      &mdash; Quality in Artificial Intelligence Group, Technische Universität Berlin, Germany <a href="https://qai-labs.org/" target="_blank"><i class="fa-solid fa-link"></i></a><br>
      &mdash; Role: Research Scientist<br>
      &mdash; Supervisor: Prof. Stefan Haufe
    </h4>
    <p class="CV-desc">
      In parallel with my work in the <a href="#ICN_Lab">Interventional and Cognitive Neuromodulation Group</a>, I am developing advanced signal processing techniques for use in my PhD project, and bringing them to open-source packages for use in the wider community (see my <a href="#OSS">open-source software work</a> for more information). Accordingly, I am greatly developing my understanding of advanced concepts in linear algebra and calculus, as well as gaining much experience with open-source software development.
    </p>

  <h3 class="CV-header"><a id="Haynes_Lab" class="section-ID">08/2019 - &zwj;08/2020</a></h3>
    <img class="logo" src="/assets/images/Logo-BCCN.png">
    <h4 class="CV-subheader">
      &mdash; Haynes Laboratory, Bernstein Center for Computational Neuroscience, Berlin, Germany <a href="https://sites.google.com/site/hayneslab/home" target="_blank"><i class="fa-solid fa-link"></i></a><br>
      &mdash; Role: Research Scientist<br>
      &mdash; Supervisors: Dr. Matthias Schultze-Kraft, Prof. John-Dylan Haynes
    </h4>
    <p class="CV-desc">
      My <a href="#Master_Desc">Industrial Placement</a> at the Bernstein Center was funded by an <a href="#Erasmus_Grant">Erasmus+ Traineeship grant</a>. Here, I investigated movement initiation using machine learning and brain-computer interfaces. As part of this work, I co-authored a research article published in <i>eNeuro</i> <a href="https://www.doi.org/10.1523/eneuro.0425-20.2020" target="_blank"><i class="fa-solid fa-link"></i></a>.<br>
      <br>
      Through this placement, I developed an in-depth understanding of brain-computer interfaces and machine learning techniques, and furthered my understanding of core concepts such as linear algebra, calculus, signal analysis, and statistics. I also gained experience designing and conducting electrophysiological studies with human subjects.
    </p>
</div>

<!-- Additional Experience -->
<div style="margin-top: 30px;" id="CAP_Lab"> <!-- COLLAPSIBLE -->
  <button type="button" class="collapsible">View Additional Experience</button>
  <div class="collapsible_content">
    <h3 class="CV-header"><a id="CNT_Lab" class="section-ID">01/2022 - &zwj;03/2022</a></h3>
      <img class="logo" src="/assets/images/Logo-CNT.png">
        <h4 class="CV-subheader">
          &mdash; Clinical Neurotechnology Laboratory, Charité – Universitätsmedizin Berlin, Germany <a href="https://www.clinical-neurotechnology.com/" target="_blank"><i class="fa-solid fa-link"></i></a><br>
          &mdash; Role: Research Scientist<br>
          &mdash; Supervisor: Prof. Surjo Soekadar
        </h4>
        <p class="CV-desc">
          As one of my <a href="#Charite_PhD">PhD Fellowship</a> rotations, I began work for the development of a 3D-printed head phantom for improving our understanding of forward models of brain activity, and the effects of non-invasive stimulation on brain activity. Through this highly practical project, I improved my understanding of the technical aspects of electrophysiological research, 3D printing, and electrical engineering.
        </p>
    <h3 class="CV-header"><a id="Hons_Project" class="section-ID">12/2020 - &zwj;04/2021</a></h3>
      <img class="logo" src="/assets/images/Logo-UoA.png">
        <h4 class="CV-subheader">
          &mdash; School of Medicine, Medical Sciences and Nutrition, University of Aberdeen, UK <a href="https://www.abdn.ac.uk/smmsn/" target="_blank"><i class="fa-solid fa-link"></i></a><br>
          &mdash; Role: Research Scientist<br>
          &mdash; Supervisor: Dr. Antonio Gonzalez
        </h4>
        <p class="CV-desc">
          As part of my <a href="#Bachelor_Desc">Honour's project</a>, I investigated the regulation of striatal activity through computational modelling. My tasks involved conducting literature reviews, collecting and analysing simulated electrophysiological data using Python, as well as writing scientific reports. Through this placement I developed an in-depth understanding of the simulation and analysis of electrophysiological data.
        </p>
    <h3 class="CV-header"><a id="CAP_Lab" class="section-ID">05/2018 - &zwj;10/2018</a></h3>
      <img class="logo" src="/assets/images/Logo-UoA.png">
        <h4 class="CV-subheader">
          &mdash; Consciousness, Attention and Perception Laboratory, University of Aberdeen, UK <a href="https://homepages.abdn.ac.uk/rama/pages/index.html" target="_blank"><i class="fa-solid fa-link"></i></a><br>
          &mdash; Role: Research Assistant<br>
          &mdash; Supervisor: Dr. Rama Chakravarthi
        </h4>
        <p class="CV-desc">
          My work focused on the investigation of choice-predictive brain signals and movement initiation in the context of consequential decisions, and was funded by a <a href="#Wellcome_Scholarship">Wellcome Trust scholarship</a>. My tasks included conducting EEG and behavioural experiments, with analysis of the associated data using MATLAB. This provided me with a solid grounding in the scientific method, and experience as a researcher working in an academic laboratory setting.
        </p>
  </div>
</div>


<!-- OSS -->
<hr>
<h1><a id="OSS" class="section-ID">Open-Source Software</a></h1>

<div>
  <h3 class="CV-header"><a id="MNE" class="section-ID">MNE-Python</a></h3>
    <img class="logo" src="/assets/images/Logo-MNE.png">
      <h4 class="CV-subheader">
        &mdash; Maintainer
      </h4>
      <p class="CV-desc">
        I am a maintainer of the popular open-source <a href="https://github.com/mne-tools/mne-python">MNE signal analysis toolbox for Python</a>, a package with over 2,500 stars on GitHub, and citations in over 4,000 peer-reviewed scientific papers. My contributions have involved the addition of new features, bug fixes, project maintenance, and user support. This has included the implementation of several advanced, multivariate signal processing methods in the <a href="https://github.com/mne-tools/mne-connectivity">MNE-Connectivity</a> package (related to my work in the <a href="#QAI_Lab">Quality in Artificial Intelligence Group</a>), as well as a <a href="#GSoC">Google Summer of Code project</a> to implement a connectivity decoding module for real-time, data-driven analysis of high-dimensional data alongside statistical tools for distinguishing genuine interactions from background noise.
      </p>

  <h3 class="CV-header"><a id="PyBispectra" class="section-ID">PyBispectra</a></h3>
    <img class="logo" src="/assets/images/Logo-Python.jpg">
      <h4 class="CV-subheader">
        &mdash; Lead Developer
      </h4>
      <p class="CV-desc">
        I developed <a href="https://github.com/braindatalab/pybispectra">PyBispectra</a>, an open-source Python package for performing advanced signal analysis using the bispectrum (related to my work in the <a href="#QAI_Lab">Quality in Artificial Intelligence Group</a>). There is support for analysing: cross-frequency coupling (amplitude-amplitude, phase-phase, and phase-amplitude coupling); frequency-domain wave shape features; as well as time delay estimations between signals. The package uses multiprocessing and Numba-based C compilation for rapid, computationally efficient signal processing.
      </p>

  <h3 class="CV-header"><a id="PyPARRM" class="section-ID">PyPARRM</a></h3>
    <img class="logo" src="/assets/images/Logo-Python.jpg">
      <h4 class="CV-subheader">
        &mdash; Lead Developer
      </h4>
      <p class="CV-desc">
        I developed the <a href="https://github.com/neuromodulation/PyPARRM">PyPARRM package</a>, an open-source Python implementation of the PARRM algorithm for removing stimulation artefacts from electrophysiological recordings (related to my work in the <a href="#ICN_Lab">Interventional and Cognitive Neuromodulation Group</a>). This package is equipped with multiprocessing support for rapid signal processing, as well as an extensive interactive tool for exploring the effects of different filter parameters on the data.
      </p>
</div>


<!-- Publications -->
<hr>
<h1><a id="Publications" class="section-ID">Selected Publications & Talks</a></h1>

<p style="margin-bottom: 30px">For the full list of publications, <a href="/publications">click here.</a></p>

<p>
  <mark><b>Binns, T.S.</b></mark>, Köhler, R.M., Vanhoecke, J., Chikermane, M., Gerster, M., Merk, T., Pellegrini, F., ..., Haufe, S., Kühn, A.A., Neumann, W.-J. (In Revision). Shared pathway-specific network mechanisms of dopamine and deep brain stimulation for the treatment of Parkinson's disease. <i>Nature Communications</i>. DOI: <a href="https://doi.org/10.1101/2024.04.14.586969" target="_blank">10.1101/2024.04.14.586969</a>.
</p>
<div style="margin-bottom: 30px;"> <!-- COLLAPSIBLE -->
  <button type="button" class="collapsible">View Description</button>
  <div class="collapsible_content">
    <p>
      Deep brain stimulation (DBS) is a brain circuit intervention that can modulate distinct neural pathways for the alleviation of neurological symptoms in patients with brain disorders. In Parkinson's disease, subthalamic DBS clinically mimics the effect of dopaminergic drug treatment, but the shared pathway mechanisms on cortex-basal ganglia networks are unknown. To address this critical knowledge gap, we combined fully-invasive neural multisite recordings in patients undergoing DBS surgery with MRI-based whole-brain connectomics.<br>
      <br>
      Our findings demonstrate that dopamine and DBS exert distinct mesoscale effects through modulation of local neural population synchrony. In contrast, at the macroscale, DBS mimics dopamine in its suppression of excessive interregional network synchrony associated with indirect and hyperdirect cortex-basal ganglia pathways. Our results provide a better understanding of the circuit mechanisms of dopamine and DBS, laying the foundation for advanced closed-loop neurostimulation therapies.
    </p>
  </div>
</div>
<br>
<p>
  Köhler, R.M., <mark><b>Binns, T.S.</b></mark>, Merk, T., Zhu, G., Yin, Z., Zhao, B., Chikermane, M., ..., Kühn, A.A., Haynes, J.-D., Neumann, W.-J. (2024). Dopamine and deep brain stimulation accelerate the neural dynamics of volitional action in Parkinson's disease. <i>Brain</i>. DOI: <a href="https://doi.org/10.1093/brain/awae219" target="_blank">10.1093/brain/awae219</a>.
</p>
<div style="margin-bottom: 30px;"> <!-- COLLAPSIBLE -->
  <button type="button" class="collapsible">View Description</button>
  <div class="collapsible_content">
    <p>
      The ability to initiate volitional action is fundamental to human behaviour. Loss of dopaminergic neurons in Parkinson's disease is associated with impaired action initiation, also termed akinesia. Both dopamine and subthalamic deep brain stimulation (DBS) can alleviate akinesia, but the underlying mechanisms are unknown. An important question is whether dopamine and DBS facilitate de novo build-up of neural dynamics for motor execution or accelerate existing cortical movement initiation signals through shared modulatory circuit effects. Answering these questions can provide the foundation for new closed-loop neurotherapies with adaptive DBS, but the objectification of neural processing delays prior to performance of volitional action remains a significant challenge.<br>
      <br>
      To overcome this challenge, we studied readiness potentials and trained brain signal decoders on invasive neurophysiology signals in 25 DBS patients (12 female) with Parkinson's disease during performance of self-initiated movements. Combined sensorimotor cortex electrocorticography and subthalamic local field potential recordings were performed OFF therapy (n = 22), ON dopaminergic medication (n = 18) and on subthalamic deep brain stimulation (n = 8). This allowed us to compare their therapeutic effects on neural latencies between the earliest cortical representation of movement intention as decoded by linear discriminant analysis classifiers and onset of muscle activation recorded with electromyography.<br>
      <br>
      In the hypodopaminergic OFF state, we observed long latencies between motor intention and motor execution for readiness potentials and machine learning classifications. Both, dopamine and DBS significantly shortened these latencies, hinting towards a shared therapeutic mechanism for alleviation of akinesia. To investigate this further, we analysed directional cortico-subthalamic oscillatory communication with multivariate granger causality. Strikingly, we found that both therapies independently shifted cortico-subthalamic oscillatory information flow from antikinetic beta (13–35 Hz) to prokinetic theta (4–10 Hz) rhythms, which was correlated with latencies in motor execution.<br>
      <br>
      Our study reveals a shared brain network modulation pattern of dopamine and DBS that may underlie the acceleration of neural dynamics for augmentation of movement initiation in Parkinson's disease. Instead of producing or increasing preparatory brain signals, both therapies modulate oscillatory communication. These insights provide a link between the pathophysiology of akinesia and its’ therapeutic alleviation with oscillatory network changes in other non-motor and motor domains, e.g. related to hyperkinesia or effort and reward perception. In the future, our study may inspire the development of clinical brain computer interfaces based on brain signal decoders to provide temporally precise support for action initiation in patients with brain disorders.
    </p>
  </div>
</div>
<br>
<p>
  Merk, T., Köhler, R.M., Peterson, V., Lyra, L., Vanhoecke, J., Chikermane, M., <mark><b>Binns, T.S.</b></mark>, ..., Kühn, A.A., Richardson, R.M., Neumann, W.-J. (In Revision). Invasive neurophysiology and whole brain connectomics for neural decoding in patients with brain implants. <i>Nature Biomedical Engineering</i>. DOI: <a href="https://www.doi.org/10.21203/rs.3.rs-3212709/v1" target="_blank">10.21203/rs.3.rs-3212709/v1</a>.
</p>
<div style="margin-bottom: 30px;"> <!-- COLLAPSIBLE -->
  <button type="button" class="collapsible">View Description</button>
  <div class="collapsible_content">
    <p>
      Brain computer interfaces (BCI) provide unprecedented spatiotemporal precision that will enable significant expansion in how numerous brain disorders are treated. Decoding dynamic patient states from brain signals with machine learning is required to leverage this precision, but a standardized framework for identifying and advancing novel clinical BCI approaches does not exist. Here, we developed a platform that integrates brain signal decoding with connectomics and demonstrate its utility across 123 hours of invasively recorded brain data from 73 neurosurgical patients treated for movement disorders, depression and epilepsy.<br>
      <br>
      First, we introduce connectomics-informed movement decoders that generalize across cohorts with Parkinson’s disease and epilepsy from the US, Europe and China. Next, we reveal network targets for emotion decoding in left prefrontal and cingulate circuits in DBS patients with major depression. Finally, we showcase opportunities to improve seizure detection in responsive neurostimulation for epilepsy. Our platform provides rapid, high-accuracy decoding for precision medicine approaches that can dynamically adapt neuromodulation therapies in response to the individual needs of patients.
    </p>
  </div>
</div>


<!-- Funding & Awards-->
<hr>
<h1><a id="Funding-Awards" class="section-ID">Funding & Awards</a></h1>

<div>
  <h3 class="CV-header"><a id="PhD_Fellowship" class="section-ID">09/2021 - &zwj;09/2024</a></h3>
    <img class="logo" src="/assets/images/Logo-ECN.png">
    <h4 class="CV-subheader" style="margin-bottom: 0;">
      &mdash; <i>PhD Fellowship</i>. &euro;63,000.<br>
      &mdash; Einstein Center for Neurosciences Berlin.
    </h4>
    <p class="CV-desc" style="margin-top: 0;">
      Of almost 1,000 applicants, I was one of only a handful of people to be accepted for this prestigious and extremely competitive fellowship. Associated with my <a href="#Charite_PhD">PhD work at the Charité - Universitätsmedizin Berlin</a>, Germany.
    </p>

  <h3 class="CV-header"><a id="GSoC" class="section-ID">05/2024 - &zwj;08/2024</a></h3>
    <img class="logo" src="/assets/images/Logo-Google.png">
    <h4 class="CV-subheader" style="margin-bottom: 0;">
      &mdash; <i>Google Summer of Code - MNE-Python: Add connectivity decoding module and statistical tools</i>. &dollar;6,000.<br>
      &mdash; Google, Python Software Foundation.
    </h4>
    <p class="CV-desc" style="margin-top: 0;">
      I was awarded this stipend to expand the repertoire of open-source tools for analysing effective connectivity in electrophysiological data in the <a href="https://github.com/mne-tools/mne-python">MNE-Python</a> ecosystem. This will include the development of a new decoding module in <a href="https://github.com/mne-tools/mne-connectivity">MNE-Connectivity</a> for the real-time, data-driven analysis of high-dimensional data, as well as the addition of statistical tools to distinguish genuine interactions from background noise. Project details <a href="https://summerofcode.withgoogle.com/programs/2024/projects/QptYlp9M">here</a>.
    </p>

  <h3 class="CV-header"><a id="ReTune_Poster_Prize" class="section-ID">10/2023</a></h3>
    <img class="logo" src="/assets/images/Logo-ReTune.png">
    <h4 class="CV-subheader" style="margin-bottom: 0;">
      &mdash; <i>ReTune Poster Prize</i>.<br>
      &mdash; ReTune International Research Consortium, Germany.
    </h4>
    <p class="CV-desc" style="margin-top: 0;">
      My work on the first fully-invasive, within-patient analysis on the effects of medication and deep brain stimulation on cortico-subthalamic connectivity <a href="/assets/documents/2023_ReTune_Fall_School-Poster.pdf" target="_blank"><i class="fa-solid fa-file-pdf"></i></a> was awarded with the prize for best poster at the Early-Career Fall School of the German Research Foundation (DFG)-funded <a href="https://retune.science/" target="_blank">ReTune research centre</a>.
    </p>

  <h3 class="CV-header"><a id="Student_Prize" class="section-ID">07/2021</a></h3>
    <img class="logo" src="/assets/images/Logo-UoA.png">
    <h4 class="CV-subheader" style="margin-bottom: 0;">
      &mdash; <i>Neuroscience Student Prize</i>.<br>
      &mdash; University of Aberdeen, UK.
    </h4>
    <p class="CV-desc" style="margin-top: 0;">
      Upon completion of my <a href="#Abdn_MSci">MSci degree</a>, I was honoured to receive the University of Aberdeen’s prize for best neuroscience student, a yearly prize presented to a student on the Neuroscience degree programme in recognition of the individual’s excellent performance during their time at the university.
    </p>

  <h3 class="CV-header"><a id="Erasmus_Grant" class="section-ID">08/2019 - &zwj;08/2020</a></h3>
    <img class="logo" src="/assets/images/Logo-Erasmus+.png">
    <h4 class="CV-subheader" style="margin-bottom: 0;">
      &mdash; <i>Investigating choice-predictive brain signals using EEG-based brain-computer interfaces</i>. &euro;5,000.<br>
      &mdash; Erasmus+ Traineeship Grant, British Council.
    </h4>
    <p class="CV-desc" style="margin-top: 0;">
      This generous grant from the British Council allowed me to complete my Master's project in the <a href="#Haynes_Lab">Haynes Laboratory</a> of the Bernstein Center for Computational Neuroscience, Berlin, Germany.
    </p>

  <h3 class="CV-header"><a id="Wellcome_Scholarship" class="section-ID">05/2018 - &zwj;10/2018</a></h3>
    <img class="logo" src="/assets/images/Logo-Wellcome.png">
    <h4 class="CV-subheader" style="margin-bottom: 0;">
      &mdash; <i>Free Will and Neural Activity in Consequential Action.</i> &pound;2,000.<br>
      &mdash; Biomedical Vacation Scholarship, Wellcome Trust.
    </h4>
    <p class="CV-desc" style="margin-top: 0;">
      I was successful in receiving this highly competitive scholarship from the prestigious Wellcome Trust to complete my research in the <a href="#CAP_Lab">Consciousness, Attention, and Perception Laboratory</a> of the University of Aberdeen, UK.
    </p>
</div>


<!-- Organisations -->
<hr>
<h1><a id="Organisations" class="section-ID">Organisations</a></h1>

<div>
  <h3 class="CV-header"><a id="MNE_Maintainer" class="section-ID">11/2023 - Present</a></h3>
    <img class="logo" src="/assets/images/Logo-MNE.png">
    <h4 class="CV-subheader">
      &mdash; MNE-Connectivity, MNE-Python Ecosystem<br>
      &mdash; Maintainer
    </h4>
    <p class="CV-desc">
      I am a maintainer for <a href="https://github.com/mne-tools/mne-connectivity">MNE-Connectivity</a>, a toolbox for analysing effective connectivity in electrophysiological data in the <a href="https://github.com/mne-tools/mne-python">MNE-Python</a> ecosystem with over 2,500 stars on GitHub and citations in over 4,000 peer-reviewed scientific papers. My contributions have involved the addition of new features, bug fixes, project maintenance, and user support, including through the Google Summer of Code programme. See my <a href="#MNE">OSS MNE work</a> for more information.
    </p>

  <h3 class="CV-header"><a id="Code_Clinic_Cofounder" class="section-ID">12/2022 - 10/2024</a></h3>
    <img class="logo" src="/assets/images/Logo-ReTune.png">
    <h4 class="CV-subheader">
      &mdash; Code Clinic, ReTune International Research Consortium, Germany<br>
      &mdash; Co-founder
    </h4>
    <p class="CV-desc">
      I co-founded the Code Clinic of the <a href="https://sfb-retune.de/">ReTune research consortium</a>, with the goal of improving the quality and openness of academic programming, a crucial step for improving the quality and reproducibility of scientific research. Towards this, the Code Clinic organised reviews for code being released alongside scientific publications and as open-source packages, ensuring a high-degree of code quality. Furthermore, I organised a pair programming scheme in which junior programmers received personalised feedback on their code from experienced coders, improving the overall quality of the code and teaching coding best practice principles to these novice programmers.
    </p>

  <h3 class="CV-header"><a id="BNA_Member" class="section-ID">09/2018 - &zwj;09/2021</a></h3>
    <img class="logo" src="/assets/images/Logo-BNA.png">
    <h4 class="CV-subheader">
      &mdash; British Neuroscience Associsation (BNA), Bristol, UK<br>
      &mdash; Member
    </h4>
    <p class="CV-desc">
      As a member of the BNA I took full advantage of the Association’s activities, attending talks and symposia to broaden my understanding of various neuroscience topics. Furthermore, I contributed an article examining the neuroscientific study of free will to the BNA’s Summer 2020 Bulletin <a href="https://www.bna.org.uk/mediacentre/news/has-neuroscience-disproven-free-will/" target="_blank"><i class="fa-solid fa-link"></i></a> <a href="/assets/documents/2020_Free_Will-BNA_Article.pdf" target="_blank"><i class="fa-solid fa-file-pdf"></i></a> allowing me to demonstrate and further hone my academic writing skills.
    </p>
</div>


<!-- Teaching -->
<hr>
<h1><a id="Teaching" class="section-ID">Teaching</a></h1>

<div>
  <h3 class="CV-header"><a id="Charite_MedNeuro_2024" class="section-ID">Summer Semester 2024</a></h3>
    <img class="logo" src="/assets/images/Logo-Charite.png">
    <h4 class="CV-subheader">
      &mdash; Clinical Neuroscience and Invasive Neurophysiology Methods<br>
      &mdash; Charité - Universitätsmedizin Berlin, Germany
    </h4>
    <p class="CV-desc">
      I led teaching of the Charité's Medical Neurosciences Master's programme modules on clinical neuroscience and invasive neurophysiology. Topics included: machine learning for neural decoding; movement disorders from a brain network perspective; and research methods for invasive neurophysiology.
    </p>

  <h3 class="CV-header"><a id="iBOTS_MNE" class="section-ID">Winter Semester 2024</a></h3>
    <img class="logo" src="/assets/images/Logo-iBehave.png">
    <h4 class="CV-subheader">
      &mdash; Introduction to Signal Processing with MNE<br>
      &mdash; iBehave Network, Germany
    </h4>
    <p class="CV-desc">
      I taught an <a href="https://github.com/tsbinns/mne_course">interactive course</a> on signal processing with the MNE-Python and MNE-Connectivity packages as part of the <a href="https://ibehave.nrw/ibots-platform/about-ibots/">iBehave Network's Open Technology initiative</a>. The course provided a foundation to students in the analysis of electrophysiological data with Python, including topics on: machine learning; time-frequency analysis; connectivity analysis; and source reconstruction.
    </p>

  <h3 class="CV-header"><a id="Charite_MedNeuro_2023" class="section-ID">Summer Semester 2023</a></h3>
    <img class="logo" src="/assets/images/Logo-Charite.png">
    <h4 class="CV-subheader">
      &mdash; Clinical Neuroscience and Invasive Neurophysiology Methods<br>
      &mdash; Charité - Universitätsmedizin Berlin, Germany
    </h4>
    <p class="CV-desc">
      I led teaching of the Charité's Medical Neurosciences Master's programme modules on clinical neuroscience and invasive neurophysiology. Topics included: electrophysiological biomarkers of movement disorders in invasive neuronal recordings; basal ganglia anatomy, physiology, and pathophysiology; and research methods for invasive neurophysiology.
    </p>

  <h3 class="CV-header"><a id="TU_MLIP_Teacher" class="section-ID">Summer Semester 2023</a></h3>
    <img class="logo" src="/assets/images/Logo-TU.png">
    <h4 class="CV-subheader">
      &mdash; Machine Learning and Inverse Problems in Neuroimaging<br>
      &mdash; Technische Universität Berlin, Germany
    </h4>
    <p class="CV-desc">
      In this seminar series for Master's students, I supervised the topics of generalised eigendecompositions for multivariate analysis (common spatial pattern filters, spatio-spectral decomposition, etc...) and oscillatory connectivity in neuroimaging.
    </p>
</div>


<!-- Courses -->
<hr>
<h1><a id="Courses" class="section-ID">Courses</a></h1>

<div>
  <h3 class="CV-header"><a id="Cajal_Neurokit" class="section-ID">07/2023</a></h3>
    <img class="logo" src="/assets/images/Logo-Cajal.png">
    <h4 class="CV-subheader">
      &mdash; Cajal Experimental Neuroscience Bootcamp
    </h4>
    <p class="CV-desc">
      A week-long, intensive hands-on course in which students develop their understanding of electronics, microcontrollers, and machine vision through the construction of an increasingly capable robot.
    </p>

  <h3 class="CV-header"><a id="LOIS" class="section-ID">11/2022 - 06/2023</a></h3>
    <img class="logo" src="/assets/images/Logo-ECN.png">
    <h4 class="CV-subheader">
      &mdash; Lab for Open Innovation in Science<br>
      &mdash; Einstein Center for Neurosciences Berlin, Germany
    </h4>
    <p class="CV-desc">
      This course teaches principles of open and collaborative science, by which research can be integrated across academia, industry, and with the general public, ensuring that academic research is innovative and relevant to wider society.
    </p>

  <h3 class="CV-header"><a id="TU_MLIP" class="section-ID">10/2022 - &zwj;02/2023</a></h3>
    <img class="logo" src="/assets/images/Logo-TU.png">
    <h4 class="CV-subheader">
      &mdash; Machine Learning and Inverse Problems in Neuroimaging<br>
      &mdash; Technische Universität Berlin, Germany
    </h4>
    <p class="CV-desc">
      A course covering key aspects of machine learning and inverse modelling in neuroscience, including mathematical frameworks for inverse modelling, regularisation of inverse solutions, frameworks for supervised and unsupervised machine learning, and Bayesian inference.
    </p>

  <h3 class="CV-header"><a id="BCCN_Winter_School" class="section-ID">03/2022</a></h3>
    <img class="logo" src="/assets/images/Logo-BCCN.png">
    <h4 class="CV-subheader">
      &mdash; Ethics of Neuroscience and AI<br>
      &mdash; Bernstein Center for Computational Neuroscience, Berlin, Germany
    </h4>
    <p class="CV-desc">
      An intensive week-long course of lectures and workshops covering theoretical foundations and practical aspects of ethics in neuroscience, including topics such as deep brain stimulation, brain death, artificial intelligence, and data protection.
    </p>

  <h3 class="CV-header"><a id="ReproducibiliTeach" class="section-ID">02/2022 - &zwj;04/2022</a></h3>
    <img class="logo" src="/assets/images/Logo-BIH.jpg">
    <h4 class="CV-subheader">
      &mdash; ReproducibiliTeach<br>
      &mdash; Berlin Institute of Health, Charité – Universitätsmedizin Berlin, Germany
    </h4>
    <p class="CV-desc">
      An eight week-long course consisting of seminars and workshops in which participants are trained to identify common problems related to tranaparency and reproducibility in scientific research. In doing so, participants learn how to overcome these challenges, and implement best practices in their own work to make it more robust, transparent, and reproducible.
    </p>

  <h3 class="CV-header"><a id="NMA_CN20" class="section-ID">07/2020</a></h3>
    <img class="logo" src="/assets/images/Logo-NMA.png">
    <h4 class="CV-subheader">
      &mdash; Neuromatch Academy - Computational Neuroscience
    </h4>
    <p class="CV-desc">
      A three week-long, highly intensive online summer school covering modelling, statistics, and machine learning, focusing on traditional and emerging tools of computational neuroscience, with extensive group work and Python programming.
    </p>
</div>


<!-- References -->
<hr>
<h1><a id="References" class="section-ID">References</a></h1>

<p>Available upon request: <a href="mailto:t.s.binns@outlook.com" target="_blank"><i class="fa-solid fa-envelope"></i></a></p>

<!-- Scripts -->
<script>

  /* Makes collapsibles work */
  var coll = document.getElementsByClassName("collapsible");
  var i;
  for (i = 0; i < coll.length; i++) {
    coll[i].addEventListener("click", function() {
      this.classList.toggle("collapsible_active");
      var content = this.nextElementSibling;
      if (content.style.maxHeight){
        content.style.maxHeight = null;
      } else {
        content.style.maxHeight = content.scrollHeight + "px";
      }
    });
  }


  /* Trigger a click on collapsible when a link visits it */
  var links = document.querySelectorAll('a')
  links.forEach(link => {
    link.addEventListener('click', function(e) {
      const linkHref = link.getAttribute('href')
      const targetCollapsible = document.querySelector(`${linkHref} .collapsible`)
      if (targetCollapsible && targetCollapsible.nextElementSibling){
        targetCollapsible.classList.add("collapsible_active");
        targetCollapsible.nextElementSibling.style.maxHeight = targetCollapsible.nextElementSibling.scrollHeight + "px";
      }
    })
  })


  /* Makes dropdowns work */
  // When the user clicks on the button, toggle between hiding and showing the dropdown content (and change the colour of the button)
  function toggle_show() {
    document.getElementById("dropdown_menu").classList.toggle("dropdown_show");
    var dropdown_btn = document.getElementsByClassName("dropdown_button");
    var k;
      for (k = 0; k < dropdown_btn.length; k++) {
        dropdown_btn[k].classList.toggle("dropdown_button_active")
      }
  }
  // Close the dropdown menu if the user clicks outside of it
  window.onclick = function(event) {
    if (!event.target.matches('.dropdown_button')) {
      var dropdowns = document.getElementsByClassName("dropdown_content");
      var j;
      for (j = 0; j < dropdowns.length; j++) {
        var openDropdown = dropdowns[j];
        if (openDropdown.classList.contains('dropdown_show')) {
          openDropdown.classList.remove('dropdown_show');
        }
      }
      // When the button is clicked, switch the button colour back to the inactive colour
      var dropdown_btn = document.getElementsByClassName("dropdown_button");
      var k;
      for (k = 0; k < dropdown_btn.length; k++) {
        if (dropdown_btn[k].classList.contains('dropdown_button_active')) {
          dropdown_btn[k].classList.remove('dropdown_button_active');
        }
      }
    }
  }

  // Applies offset to section links
  // For the section links
  function offsetAnchor() {
    if (location.hash.length !== 0) {
      window.scrollTo(window.scrollX, window.scrollY - 100);
    }
  }
  // Captures click events of all <a> elements with href starting with #
  $(document).on('click', 'a[href^="#"]', function(event) {
    // Click events are captured before hashchanges. Timeout
    // causes offsetAnchor to be called after the page jump.
    window.setTimeout(function() {
      offsetAnchor();
    }, 0);
  });
  // Set the offset when entering page with hash present in the url
  window.setTimeout(offsetAnchor, 0);

  // For the page top link
  function offsetAnchor_top() {
    if (location.hash.length !== 0) {
      window.scrollTo(window.scrollX, window.scrollY - 1000);
    }
  }
  // Captures click events of all <a> elements with href starting with #Top
  $(document).on('click', 'a[href^="#Top"]', function(event) {
    // Click events are captured before hashchanges. Timeout
    // causes offsetAnchor to be called after the page jump.
    window.setTimeout(function() {
      offsetAnchor_top();
    }, 0);
  });
  // Set the offset when entering page with hash present in the url
  window.setTimeout(offsetAnchor_top, 0);

    // For the page thesis description links
  function offsetAnchor_thesisdesc() {
    if (location.hash.length !== 0) {
      window.scrollTo(window.scrollX, window.scrollY - 125);
    }
  }
  // Captures click events of all <a> elements with href starting with #*_Desc
  $(document).on('click', 'a[href^="#Master_Desc"]', function(event) {
    // Click events are captured before hashchanges. Timeout
    // causes offsetAnchor to be called after the page jump.
    window.setTimeout(function() {
      offsetAnchor_thesisdesc();
    }, 0);
  });
  $(document).on('click', 'a[href^="#Bachelor_Desc"]', function(event) {
    // Click events are captured before hashchanges. Timeout
    // causes offsetAnchor to be called after the page jump.
    window.setTimeout(function() {
      offsetAnchor_thesisdesc();
    }, 0);
  });
  // Set the offset when entering page with hash present in the url
  window.setTimeout(offsetAnchor_thesisdesc, 0);

</script>
