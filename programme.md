---
layout: page
title: Programme
---

Clarity-2023 will be a one-day workshop with a single track.

The morning will focus on <b>hearing aid speech intelligibility prediction</b> and will present the outcomes 2nd Clarity Prediction Challenge. The afternoon will focus on <b>hearing aid speech enhancement</b> including a presentation of plans for 3rd Clarity Enhancement Challenge.

Provisional timings and session details are provided below. All times are in Dublin local time (UTC+1).

<div class="panel panel-default">
<div class="panel-body">

<div class="card  m-3">

<div class="card-body">

<table style="margin-left: 1em;">
<tbody>
<tr><td>9:00</td><td>Welcome</td></tr>
<tr><td>9:10</td><td><a href="#keynote1">Keynote 1</a> - Theme: Intelligibility Prediction - Fei Chen (SUSTech) </td> </tr>
<tr><td>10:00</td><td>The Clarity Prediction Challenge Overview </td></tr>
<tr><td>10:20</td><td>Break - Coffee/Tea</td></tr>
<tr><td>10:40</td><td>Clarity Prediction Challenge Systems</td></tr>
<tr><td>12:40</td><td>Prizes and conclusions </td> </tr>
<tr><td>12:50</td><td>Lunch</td></tr>
<tr><td>13:30</td><td>Hearing Aid Speech Enhancement - A user's perspective</td></tr>
<tr><td>13:50</td><td><a href="#keynote2">Keynote 2</a> - Theme: Speech Enhancement - DeLiang Wang (Ohio State University) </td> </tr>
<tr><td>14:50</td><td>Plans for the 3rd Clarity Enhancement Challenge</td></tr>
<tr><td>15:10</td><td>Discussion</td></tr>
<tr><td>15:30</td><td>Break - Coffee/Tea</td></tr>
<tr><td>15:50</td><td>Hearing Aid Speech Enhancement - Invited Talks</td></tr>
<tr><td>17:30</td><td>Close</td></tr>

</tbody>
</table>
</div>
</div>

<h1>Keynote talks</h1>

<div class="card m-3">
  <a name="keynote1"></a>

<div class="card-header">
<div class="row  align-items-center">

<div class="col-sm-3">
<img src="/clarity2023-workshop/assets/images/fei_chen.png" alt="Fei Chen" class="float-left rounded-circle" style="width:100%" />
</div>

<div class="col-sm-9">
<h1 class="lead">Fei Chen <div class="text-muted">SUSTech, China</div></h1>

<h1>Objective speech intelligibility prediction: Insights from human speech perception</h1>

<button class="btn btn-primary" style="color:white; margin: 10px; border-radius: 4px;" type="button" data-toggle="collapse" data-target="#collapseAbstractChen" aria-expanded="false" aria-controls="collapseAbstractChen">
    Abstract and Bio
  </button>

</div>

<div class="collapse" id="collapseAbstractChen">

<div class="card-body">
<h1 class="card-title">Objective speech intelligibility prediction: Insights from human speech perception</h1>

<h3>Abstract</h3>

<p>Speech intelligibility assessment plays an important role in speech and hearing studies. Designing a computational speech intelligibility model can significantly facilitate our studies, e.g., speech enhancement and speech coding. While many objective speech intelligibility prediction models are available, there are still challenges towards improving the prediction performance of intelligibility indices. Human speech perception studies provide us not only knowledge on various (e.g., acoustic, linguistic) impacts on speech understanding in different listening environments, but also insights on design a reliable objective intelligibility prediction index. In this talk, I will first introduce studies on important acoustic cues on human speech perception. Then, I will review the design of some existing intelligibility prediction models and efforts to improve their prediction power. Finally, I will briefly introduce new developments towards objective speech intelligibility prediction, e.g., machine learning and neurophysiological measurement methods.</p>

<h3>Bio</h3>

<p>Fei Chen (Senior Member, IEEE) received the B.Sc. and M.Phil. degrees from the Department of Electronic Science and Engineering, Nanjing University, Nanjing, China, in 1998 and 2001, respectively, and the Ph.D. degree from Department of Electronic Engineering, The Chinese University of Hong Kong, Hong Kong, in 2005. He continued his research as Postdoctor and Senior Research Fellow with the University of Texas at Dallas, supervised by Prof. Philipos Loizou, and The University of Hong Kong, Hong Kong. He is currently a Full Professor with the Department of Electrical and Electronic Engineering, Southern University of Science and Technology (SUSTech), Shenzhen, China. Dr. Chen is leading the speech and physiological signal processing Research Group in SUSTech. He has authored or coauthored more than 100 journal papers and more than 100 conference papers in IEEE journals/conferences, Interspeech, Journal of Acoustical Society of America. His research interests include speech communication and assistive hearing technologies, brain-computer interface, and biomedical signal processing. He was tutorial speaker of Interspeech2022, Interspeech2020, EUSIPCO2022, APSIPA2021, and APSIPA2019, and organized special session Signal processing for assistive hearing devices at ICASSP2015. Dr. Chen is an APSIPA distinguished Lecturer (2022-2023), and is currently an Associate Editor for Biomedical Signal Processing and Control and Frontiers in Human Neuroscience.</p>
</div>

</div>

</div>

</div>
</div>

<div class="card m-3">
  <a name="keynote2"></a>

<div class="card-header">
<div class="row  align-items-center">

<div class="col-sm-3">
<img src="/clarity2023-workshop/assets/images/deliang_wang.png" alt="DeLiang Wang" class="float-left rounded-circle" style="width:100%" />
</div>

<div class="col-sm-9">
<h1 class="lead">DeLiang Wang <div class="text-muted">Ohio State University, US</div></h1>

<h1>Neural Spectrospatial Filtering</h1>

<button class="btn btn-primary" style="color:white; margin: 10px; border-radius: 4px;" type="button" data-toggle="collapse" data-target="#collapseAbstractWang" aria-expanded="false" aria-controls="collapseAbstractWang">
    Abstract and Bio
  </button>

</div>

<div class="collapse" id="collapseAbstractWang">

<div class="card-body">
<h1 class="card-title">Neural Spectrospatial Filtering</h1>

<h3>Abstract</h3>

<p>As the most widely-used spatial filtering approach for multi-channel signal separation,
beamforming extracts the target signal arriving from a specific direction. We present an
emerging approach based on multi-channel complex spectral mapping, which trains a deep
neural network (DNN) to directly estimate the real and imaginary spectrograms of the target
signal from those of the multi-channel noisy mixture. In this all-neural approach, the trained
DNN itself becomes a nonlinear, time-varying spectrospatial filter. How does this conceptually
simple approach perform relative to commonly-used beamforming techniques on different array
configurations and in different acoustic environments? We examine this issue systematically on
speech dereverberation, speech enhancement, and speaker separation tasks. Comprehensive
evaluations show that multi-channel complex spectral mapping achieves very competitive speech
separation results compared to beamforming for different array geometries, and reduces to
monaural complex spectral mapping in single-channel conditions, demonstrating the versatility
of this new approach for multi-channel and single-channel speech separation. In addition, such
an approach is computationally more efficient than popular mask-based beamforming. We
conclude that this neural spectrospatial filter provides a broader approach than traditional and
DNN-based beamforming.</p>

<h3>Bio</h3>

<p>DeLiang Wang received the B.S. degree and the M.S. degree from Peking (Beijing) University and the Ph.D. degree in 1991 from the University of Southern California all in computer science. Since 1991,he has been with the Department of Computer Science & Engineering and the Center for Cognitive and Brain Sciences at The Ohio State University, where he is a Professor and University Distinguished Scholar. He received the U.S. Office of Naval Research Young Investigator Award in 1996, the 2008 Helmholtz Award and 2020 Ada Lovelace Service Award from the International Neural Network Society (INNS), the 2007 Outstanding Paper Award of the IEEE ComputationalIntelligence Society and the 2019 Best Paper Award of the IEEE Signal Processing Society. He is an IEEE Fellow and ISCA Fellow. He currently serves as Co-Editor-in-Chief of Neural Networks, and a member of the INNS Board of Governors.</p>
</div>

</div>

</div>

</div>
</div>

<h1>Invited talks</h1>

<!-- beginning of invited talk block -->

<div class="card m-3">
<a name="invited1"></a>
  
<div class="card-header">
<div class="row  align-items-center">
  
<div class="col-sm-3">
<img src="/clarity2023-workshop/assets/images/daniel_wong.png" alt="Daniel Wong" class="float-left rounded-circle" style="width:100%" />
</div>
  
<div class="col-sm-9">
<h1 class="lead">Daniel Wong<div class="text-muted">Meta Reality Labs, US</div></h1>
  
<h1>Project Aria: Investigating Ego-Centric Hearing Augmentation</h1>
  
<button class="btn btn-primary" style="color:white; margin: 10px; border-radius: 4px;" type="button" data-toggle="collapse" data-target="#collapseAbstractWong" aria-expanded="false" aria-controls="collapseAbstractWong">
Abstract
</button>
  
</div>

<div class="collapse" id="collapseAbstractWong">
  
<div class="card-body">
<h1 class="card-title">Project Aria: Investigating Ego-Centric Hearing Augmentation</h1>
  
<h3>Abstract</h3>
  
<p>Augmented reality glasses provide a practical wearable form-factor for speech enhancement that can leverage multi-microphone processing technology and sensor fusion. One application that Meta Reality Labs Research is focusing on is context-aware hearing augmentation in noisy environments. To help tackle this challenge, Project Aria provides a data-gathering platform for investigating the problem space of ego-centric scene understanding, user understanding and speech enhancement. In this talk, I will discuss the platform and some of the most recent work from Meta on ego-centric hearing augmentation.</p>

</div>
  
</div>
  
</div>

</div>
</div>

<!-- end of invited talk block -->

<div class="card m-3">
<a name="invited2"></a>
  
<div class="card-header">
<div class="row  align-items-center">
  
<div class="col-sm-3">
<img src="/clarity2023-workshop/assets/images/lorena_aldana.png" alt="Lorena Aldana" class="float-left rounded-circle" style="width:100%" />
</div>
  
<div class="col-sm-9">
<h1 class="lead">Lorena Aldana<div class="text-muted">University of Edinburgh, UK</div></h1>
  
<h1>Designing the Audio-Visual Speech Enhancement Challenge (AVSEC)</h1>
  
<button class="btn btn-primary" style="color:white; margin: 10px; border-radius: 4px;" type="button" data-toggle="collapse" data-target="#collapseAbstractAldana" aria-expanded="false" aria-controls="collapseAbstractAldana">
Abstract
</button>
  
</div>

<div class="collapse" id="collapseAbstractAldana">
  
<div class="card-body">
<h1 class="card-title">Designing the Audio-Visual Speech Enhancement Challenge (AVSEC)</h1>
  
<h3>Abstract</h3>
  
<p>The Audio-Visual Speech Enhancement Challenge (AVSEC) sets the first benchmark in the field of audio-visual speech enhancement, providing a carefully designed dataset and scalable protocol for human listening evaluation of AV-SE systems. AV scenes comprise audio and video of a target speaker mixed with an interferer that can be either noise or a competing speaker. Target speaker videos are selected from LRS3. AV-SE systems are evaluated in terms of intelligibility from listening tests with human participants. To evaluate the systems, we propose a scalable and efficient method to assess intelligibility from “in-the-wild stimuli” that does not require a specific sentence structure. This talk will present the scope and limitations of current design choices in AVSEC.</p>

</div>
  
</div>
  
</div>

</div>
</div>

<!-- end of invited talk block -->

<div class="card m-3">
<a name="invited3"></a>
  
<div class="card-header">
<div class="row  align-items-center">
  
<div class="col-sm-3">
<img src="/clarity2023-workshop/assets/images/michael_akeroyd.jpg" alt="Michael Akeroyd" class="float-left rounded-circle" style="width:100%" />
</div>
  
<div class="col-sm-9">
<h1 class="lead">Michael Akeroyd<div class="text-muted">University of Nottingham, UK</div></h1>
  
<h1>The COG-MHEAR project - Towards cognitively-inspired 5G-IoT enabled, multi-modal Hearing Aids</h1>
  
<button class="btn btn-primary" style="color:white; margin: 10px; border-radius: 4px;" type="button" data-toggle="collapse" data-target="#collapseAbstractAkeroyd" aria-expanded="false" aria-controls="collapseAbstractAkeroyd">
Abstract
</button>

</div>

<div class="collapse" id="collapseAbstractAkeroyd">
  
<div class="card-body">
<h1 class="card-title">The COG-MHEAR project - Towards cognitively-inspired 5G-IoT enabled, multi-modal Hearing Aids</h1>
  
<i>Michael A Akeroyd (University of Nottingham), Amir Hussain (Edinburgh Napier), Peter Bell (Edinburgh), Ahsan Adeel (Wolverhampton), Qammar Hussain Abbasi (Glasgow), Steve Renals (Edinburgh), Tughrul Arslan (Edinburgh), Tharmalingam Ratnarajah (Edinburgh), Lynne Baillie (Heriot-Watt), Mathini Sellathurai (Heriot-Watt) , Muhammad Imran (Glasgow), Emma Hart, (Edinburgh Napier), Ahmed Al-Dubai, (Edinburgh Napier), William Buchanan (Edinburgh Napier), Alexander Casson (Manchester), & Dorothy Hardy (Edinburgh Napier)</i>

<h3>Abstract</h3>
  
<p>The lack of take-up of hearing aids, their use, their stigma, the effort required to use them, and the limitations in what they can do for speech enhancement remain fundamental problems for auditory research. The COG-MHEAR project is a 4-year EPSRC-funded project that is taking a transformative, interdisciplinary approach to address some of these issues. We are creating prototypes of multi-modal aids which not only amplify sounds but also use information collected from a range of sensors to improve understanding of speech, including visual information of the movements of the speaker's lips, hand gestures, and similar. But such devices bring challenges in preserving privacy and operating with minimum power and minimum delay. In this talk we will give an overview of the project, some of the results, and some of the challenges.</p>

</div>

</div>
  
</div>

</div>
</div>

<!-- end of invited talk block -->

<div class="card m-3">
<a name="invited4"></a>
  
<div class="card-header">
<div class="row  align-items-center">
  
<div class="col-sm-3">
<img src="/clarity2023-workshop/assets/images/dominika_woszczyk.png" alt="Dominika Woszczyk" class="float-left rounded-circle" style="width:100%" />
</div>
  
<div class="col-sm-9">
<h1 class="lead">Dominika Woszczyk<div class="text-muted">Imperial College London, UK</div></h1>
  
<h1>Voice Conversion for Lombard Speaking Style with Implicit Acoustic Feature Conditioning</h1>
  
<button class="btn btn-primary" style="color:white; margin: 10px; border-radius: 4px;" type="button" data-toggle="collapse" data-target="#collapseAbstractWoszczyk" aria-expanded="false" aria-controls="collapseAbstractWoszczyk">
Abstract
</button>
  
</div>

<div class="collapse" id="collapseAbstractWoszczyk">
  
<div class="card-body">
<h1 class="card-title">Voice Conversion for Lombard Speaking Style with Implicit Acoustic Feature Conditioning</h1>
  
<i>Dominika C Woszczyk (Imperial College London); Sam Ribeiro (Amazon Alexa); Thomas Merritt (Amazon); Daniel Korzekwa (Nvidia)</i>

<h3>Abstract</h3>
  
<p>Lombard speaking style in Text-to-Speech (TTS) systems can enhance speech intelligibility and be advantageous in noisy environments and for individuals with hearing loss. However, training such models requires a large amount of data and the Lombard effect is challenging to record due to speaker and noise variability and tiring recording conditions. Voice conversion (VC) has been shown to be a useful augmentation technique to train TTS systems when data from the target speaker in the desired speaking style is unavailable. Our focus in this study is on Lombard speaking style conversion, aiming to convert speaker identity while retaining the distinctive acoustic characteristics of the Lombard style. We compare voice conversion models with implicit and explicit acoustic feature conditioning. Our results show that our implicit conditioning strategy achieves an intelligibility gain comparable to the model conditioned on explicit acoustic features, while also preserving speaker similarity.</p>

</div>
  
</div>
  
</div>

</div>
</div>

<!-- end of invited talk block -->

</div>

<br/>
