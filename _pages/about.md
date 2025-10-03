---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Researcher at the Technical University Dortmund (TU Dortmund) working on 3D Computer Vision and Robotics.  

My main research topic is High speed perception for mobile robots using a combination of stereo setup of event camera and RGB camera. 

## 📰Updates 

<ul class="small">
<li>[August 2025] MR6D paper accepted at <strong>ICCV R6D Workshop</strong></li>
<li>[June 2025] Presented at IFAC 2025: Human-UAV Collaboration in Warehousing</li>  
<li>[May 2025] Presented the MTevent paper <strong> CVPR – Event Vision workshop</strong></li>
<li>[October 2024] Our EventRec Project on high speed robot perception officially started with industrial partners.</li>
<li>[August 2024] 🏆 Secured the <strong> AIF funding </strong>strong>(Allianz for Industrie & research) for the Event camera project.</li>
<li>[September 2023] Published at Logistics Journal: Micro UAV swarm for industrial applications in indoor environment: a systematic literature review</li>
<li>[August 2022] Presented at <strong>ICPR </strong>: Video-based pose-estimation data as source for transfer learning in human activity recognition</li>
<li>[September 2022] Presented at MHCL: UAVs for industries and supply chain management</li>
  
</ul>


## Projects
<section class="projects">

<!-- Project: EventRec -->
<div class="project-item" style="text-align:center; margin:0.8rem 0; padding:1.5rem; border-radius:10px; background:#f8f9fb; box-shadow:0 12px 28px rgba(15,30,65,0.08);">
  <h3 style="margin:0 0 0.5rem 0;">
    EventRec <span style="font-size:0.9em; color:#666; font-weight:normal;"></span>
  </h3>
  <p style="margin:0 0 1rem 0; font-size:0.95em; color:#666;">
    TU Dortmund · (2023 – Ongoing)
  </p>
  <p style="margin:0.25rem 0 1rem 0;">
    <a href="https://flw.mb.tu-dortmund.de/research/research-projects/eventrec" target="_blank" rel="noopener"
       style="display:inline-block; background:#dbe4ff; color:#142d6f; padding:0.35em 0.9em; border-radius:0.4em; text-decoration:none; font-weight:600;">
      Project Page
    </a>
  </p>
  <div class="project-images" style="display:flex; justify-content:center; gap:0.75rem; flex-wrap:wrap; margin:0 auto 1rem auto; max-width:1000px;">
  <img src="/images_content/eventrec_cam_system.jpg" alt="EventRec camera system"
       loading="lazy"
       style="height:180px; width:auto;">
  <img src="/images_content/EventRec.jpg" alt="EventRec O³dyn robot"
       loading="lazy"
       style="height:180px; width:auto;">
  </div>
  <div class="project-desc" style="max-width:900px; margin:0 auto; line-height:1.5;">
    <p style="margin:0.4rem 0;">
      I proposed and led the EventRec project, taking it from concept to securing funding from the AIF/IGF in close collaboration with colleagues. 
    </p>
    <p style="margin:0.4rem 0;">
      The project aims to enable high-speed robots to perceive and interact with their environment using event cameras. As project lead, I managed a small research team that created the MTEvent dataset and am currently working on developing novel methods for 3D detection of moving objects, advancing real-time perception capabilities for robots to navigate safely and efficiently in dynamic environments at high speed.
    </p>
    <p style="margin:0.4rem 0;">
      <strong>Industry partners:</strong> KION, Jungheinrich, Framos, Safelog and others.
    </p>
  </div>
  
<h2>Publications</h2> 

<!-- MTevent 
  <!-- Left: 2:3 image box -->
  <div class="pub-thumb" style="position:relative; display:inline-block; background:#f9f9f9; border-radius:6px; overflow:hidden;">
  <img src="/images_content/MTevent_object.gif" alt="MTevent teaser image" loading="lazy"
       style="max-width:100%; height:auto; display:block;">
</div>

  <!-- Right: paper info -->
  <div class="pub-meta" style="line-height:1.35;">
    <h3 class="pub-title" style="margin:0 0 0.3em 0; color:#142d6f;">
      <a href="https://arxiv.org/abs/2504.02812" style="color:#142d6f; text-decoration:none;" target="_blank" rel="noopener">
        MTevent: A Multi-Task Event Camera Dataset for 6D Pose Estimation and Moving Object Detection
      </a>
    </h3>
    <p class="pub-authors" style="margin:0.2em 0; color:#1b2747;">
      <span style="font-weight:600;">*</span><strong>Shrutarv Awasthi</strong><sup>1</sup>, 
      *Anas Gouda<sup>1,2</sup>, 
      Sven Franke<sup>1</sup>, Jérôme Rutinowski<sup>1,2</sup>, 
      Frank Hoffmann<sup>1</sup>, Moritz Roidl<sup>1,2</sup>
    </p>
    <p class="pub-affiliations" style="margin:0.2em 0; font-size:0.95em; color:#53618f;">
      <sup>1</sup> TU Dortmund · <sup>2</sup> Lamarr Institute
    </p>
    <p class="pub-venue" style="margin:0.3em 0; font-style:italic; color:#2d3f74;">
      CVPR 2025 — Workshop on Event-based Vision
    </p>
    <p class="pub-links" style="margin:0.6em 0; display:flex; flex-wrap:wrap; gap:0.6rem;">
      <a href="https://arxiv.org/abs/2504.02812" target="_blank" rel="noopener"
         style="background:#dbe4ff; color:#142d6f; padding:0.25em 0.6em; border-radius:0.35em; font-size:0.9em; text-decoration:none; display:inline-flex; align-items:center; gap:0.35rem;">
         <img src="/images_content/arxiv-logo.png" alt="arXiv" style="height:16px;">
      </a>
      <a href="https://openaccess.thecvf.com/content/CVPR2025W/EventVision/html/Awasthi_MTevent_A_Multi-Task_Event_Camera_Dataset_for_6D_Pose_Estimation_CVPRW_2025_paper.html" target="_blank" rel="noopener"
         style="background:#dbe4ff; color:#142d6f; padding:0.25em 0.6em; border-radius:0.35em; font-size:0.9em; text-decoration:none; display:inline-flex; align-items:center; gap:0.35rem;">
         CVF
      </a>
      <a href="https://huggingface.co/datasets/anas-gouda/mtevent" target="_blank" rel="noopener"
         style="background:#dbe4ff; color:#142d6f; padding:0.25em 0.6em; border-radius:0.35em; font-size:0.9em; text-decoration:none; display:inline-flex; align-items:center; gap:0.35rem;">
         <img src="/images_content/hf-logo.png" alt="Hugging Face" style="height:16px;"> Dataset
      </a>
      <a href="https:https://github.com/shrutarv/MTevent_toolkit" target="_blank" rel="noopener"
         style="background:#dbe4ff; color:#142d6f; padding:0.25em 0.6em; border-radius:0.35em; font-size:0.9em; text-decoration:none; display:inline-flex; align-items:center; gap:0.35rem;">
         <img src="/images_content/github-logo.jpg" alt="GitHub" style="height:16px;"> MTevent Toolkit
      </a>
      
    </p>
  </div>
  
<!-- Event Camera as Region Proposal Network -->
<div id="event_roi" class="pub-item" style="display:grid; grid-template-columns:35% 65%; gap:1rem; align-items:start; margin:0.8rem 0; background:#f8f9fb; border-radius:10px; padding:1.2rem; box-shadow:0 12px 28px rgba(15,30,65,0.08);">
  <!-- Left: thumbnail -->
  <div class="pub-thumb" style="width:100%; text-align:center;">
    <img src="/images_content/Event_as_ROI.png" alt="Event Camera as RPN teaser image" loading="lazy"
         style="width:100%; height:auto; transform:scale(1.3), border-radius:6px; background:#f9f9f9; padding:2px;">
  </div>
  <!-- Right: paper info -->
  <div class="pub-meta" style="line-height:1.35;">
    <h3 class="pub-title" style="margin:0 0 0.3em 0; color:#142d6f;">
      <a href="https://arxiv.org/abs/2305.00718" style="color:#142d6f; text-decoration:none;" target="_blank" rel="noopener">
        Event Camera as Region Proposal Network
      </a>
    </h3>
    <!-- Authors -->
    <p class="pub-authors" style="margin:0.2em 0; color:#1b2747;">
      <strong>Shrutarv Awasthi</strong>, Richard Julian Lodenkaemper, Anas Gouda, Moritz Roidl
    </p>
    <p class="pub-affiliations" style="margin:0.2em 0; font-size:0.95em; color:#53618f;">
      TU Dortmund
    </p>
    <p class="pub-venue" style="margin:0.3em 0; font-style:italic; color:#2d3f74;">
      Preprint 2023
    </p>
    <p class="pub-links" style="margin:0.6em 0; display:flex; flex-wrap:wrap; gap:0.6rem;">
      <a href="https://arxiv.org/abs/2305.00718" target="_blank" rel="noopener"
         style="background:#dbe4ff; color:#142d6f; padding:0.25em 0.6em; border-radius:0.35em; font-size:0.9em; text-decoration:none; display:inline-flex; align-items:left; gap:0.35rem;">
         <img src="/images_content/arxiv-logo.png" alt="arXiv" style="height:16px;">
      </a>
      <a href="https://github.com/shrutarv/EventCamera_RPN" target="_blank" rel="noopener"
         style="background:#dbe4ff; color:#142d6f; padding:0.25em 0.6em; border-radius:0.35em; font-size:0.9em; text-decoration:none; display:inline-flex; align-items:left; gap:0.35rem;">
         <img src="/images_content/github-logo.svg" alt="GitHub" style="height:16px;"> GitHub
      </a>
    </p>
  </div>
</div>

<!-- Project: Human UAV Collaboration in Warehousing -->
<div class="project-item" style="text-align:center; margin:0.8rem 0; padding:1.5rem; border-radius:10px; background:#f8f9fb; box-shadow:0 12px 28px rgba(15,30,65,0.08);">
  <h3 style="margin:0 0 0.5rem 0;">
    Human UAV Collaboration in Warehousing <span style="font-size:0.9em; color:#666; font-weight:normal;"></span>
  </h3>
  <p style="margin:0 0 1rem 0; font-size:0.95em; color:#666;">
    TU Dortmund (2021 – 2024)
  </p>
   <div class="project-images" style="display:flex; justify-content:center; gap:0.75rem; flex-wrap:wrap; margin:0 auto 1rem auto; max-width:1000px;">
    <div style="width:200px; height:150px; overflow:hidden; position:relative; border:1px solid #ccc;">
      <img src="/images_content/HDI.svg" alt="HDI logo"
           loading="lazy"
           style="top:-5000px;   /* crop 50px from top */
              left:-900ßpx;  /* crop 30px from left */
              right:-300px; /* crop 40px from right (via container width) */
              bottom:-100px;/* crop 20px from bottom */
              width:auto; 
              height:280px">
    </div>
  </div>
  <div class="project-desc" style="max-width:900px; margin:0 auto; line-height:1.5;">
    <p style="margin:0.4rem 0;">Package for 2D segmentation of unseen objects and the main outcome of my PhD work.</p>
    <p style="margin:0.4rem 0;">The package segments arbitrary objects from only a few images, making it broadly applicable. I focused on two applications: bin picking and grasping for mobile robots, for which dedicated datasets were collected.</p>
    <p style="margin:0.4rem 0;">While the package itself targets segmentation, our centroid triplet loss (CTL) built on top of it achieved strong results on ArmBench. This line of work is especially relevant to logistics, where countless items must be segmented and classified, and parts have already been transferred to industry.</p>
  </div>
    
</div>


</section>


## Publications

<section class="publications">

<!-- MR6D -->
<div id="mr6d" class="pub-item" style="display:grid; grid-template-columns:35% 65%; gap:1rem; align-items:start; margin:0.8rem 0; background:#f8f9fb; border-radius:10px; padding:1.2rem; box-shadow:0 12px 28px rgba(15,30,65,0.08);">
  <!-- Left: 16:9 image box -->
  <div class="pub-thumb" style="position:relative; width:100%; aspect-ratio:16/9; background:#f9f9f9; border-radius:6px; overflow:hidden; display:flex; align-items:center; justify-content:center;">
    <img src="/images_content/MR6D_optimized.gif" alt="MR6D teaser image" loading="lazy"
         style="width:100%; height:100%; object-fit:contain;">
  </div>
  <!-- Right: paper info -->
  <div class="pub-meta" style="line-height:1.35;">
    <h3 class="pub-title" style="margin:0 0 0.3em 0; color:#142d6f;">
      <a href="https://arxiv.org/abs/2508.13775" style="color:#142d6f; text-decoration:none;" target="_blank" rel="noopener">
        MR6D: Benchmarking 6D Pose Estimation for Mobile Robots
      </a>
    </h3>
    <p class="pub-authors" style="margin:0.2em 0; color:#1b2747;">
      Anas Gouda <sup>1,3</sup>, <strong>Shrutarv Awasthi</strong>strong><sup>1</sup>,
      Christian Blesing<sup>2</sup>, Lokeshwaran Manohar<sup>1</sup>, 
      Frank Hoffmann<sup>1</sup>, Alice Kirchheim<sup>1,2,3</sup>
    </p>
    <p class="pub-affiliations" style="margin:0.2em 0; font-size:0.95em; color:#53618f;">
      <sup>1</sup> TU Dortmund · <sup>2</sup> Fraunhofer IML · <sup>3</sup> Lamarr Institute
    </p>
    <p class="pub-venue" style="margin:0.3em 0; font-style:italic; color:#2d3f74;">
      ICCV 2025 — R6D Workshop
    </p>
    <p class="pub-links" style="margin:0.6em 0; display:flex; flex-wrap:wrap; gap:0.6rem;">
      <a href="https://arxiv.org/abs/2508.13775" target="_blank" rel="noopener"
         style="background:#dbe4ff; color:#142d6f; padding:0.25em 0.6em; border-radius:0.35em; font-size:0.9em; text-decoration:none; display:inline-flex; align-items:center; gap:0.35rem;">
         <img src="/images_content/arxiv-logo.png" alt="arXiv" style="height:16px;">
      </a>
      <a href="https://huggingface.co/datasets/anas-gouda/mr6d" target="_blank" rel="noopener"
         style="background:#dbe4ff; color:#142d6f; padding:0.25em 0.6em; border-radius:0.35em; font-size:0.9em; text-decoration:none; display:inline-flex; align-items:center; gap:0.35rem;">
         <img src="/images_content/hf-logo.png" alt="Hugging Face" style="height:16px;"> Dataset
      </a>
    </p>
  </div>
</div>
</section>
