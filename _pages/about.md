---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<h1 align="center">
<em> We build quantitative models informed by molecular and epidemiological data to guide the public health repsonse to emerging and endemic pathogenic threats.</em>
</h1>

The Martin Group @ JHU BSPH is a computational biology research group in the [Department of Epidemiology](https://publichealth.jhu.edu/departments/epidemiology) at the Johns Hopkins Bloomberg School of Public Health. Broadly, our work aims to reduce the global burden of infectious diseases. More specifically, we use pathogen molecular (particularly genomic) data and quantitative mathematical models to better understand the biological, environmental, and sociological drivers of pathogen population dynamics to inform the public health response to endemic and emerging infectious threats. We are a part of the [Infectious Disease Dynamics](https://www.iddynamics.jhsph.edu) group at JHU and collaborate broadly throughout the university and beyond. 

## Broadly, most of our work falls into one of the following themes: 

<div class="theme-grid">
  {% for theme in site.data.themes %}
    <div class="theme-card">
      {% if theme.name %}
        <h3> {{ theme.name }} </h3>
      {% endif %}
    </div>
  {% endfor %}
</div>

# News
## 2026
- Starting June 1st, 2026, I will be transitioning to an Assistant Professor role in the [Department of Epidemiology](https://publichealth.jhu.edu/departments/epidemiology) at the Johns Hopkins Bloomberg School of Public Health where I'll be continuing as a member of the wonderful [Infectious Disease Dynamics](https://www.iddynamics.jhsph.edu) group. I'm very excited to continue with my ongoing collaborations at the school and forge new ones in the department and beyond. Over the next few weeks I will be (haphazardly) transitioning this website away from a personal website and towards a group website.
  
- Our work on HIV viral load suppression and resistance during the dolutegravir transition has been published in [Clinical Infectious Diseases](https://academic.oup.com/cid/advance-article/doi/10.1093/cid/ciag161/8516728) and selected as an Editor's Choice. The main findings remain similar to what was presented in the pre-print described below. [PDF](hppts://m-a-martin.github.io/files/hiv_resistance_dtg.pdf).
  
- I'll be presenting two poster presentations at the upcoming [2026 Conference on Retroviruses and Opportunistic Infections (CROI)](https://www.croiconference.org). The first, 903 - Quantifying Uncertainty in HIV Transmission Risk From Persons With Low-Level Viremia (February 24, 2:30 PM - 4:00 PM), is about ongoing work in collaboration with the Rakai Health Sciences Program (RHSP), Dr. M. Kate Grabowski at Johns Hopkins Medicine, and Dr. Alison Hill, now at UToronto, in which we are trying to estimate the true risk of infection from individuals presenting with low-level viremia (200 - 1,000 copies/mL). We are specifically focused on contexts sucha as sub-Saharan Africa in which viral load monitoring is rare. This work was also selectd for a short Themed Discussion presentation. Additionall, I'll be presenting 557 - Genetically Inferred Patterns of Transmitted HIV Pretreatment Resistance in Southern Uganda (February 23, 2:30 PM - 4:00 PM) on ongoing work with RHSP and the PANGEA-HIV consortium on genetic clustering patterns of resistance mutations in Rakai, Uganda. I'm looking forward to reconnecting with the rich HIV and OI research community at this meeting.
  
## 2025
- We recently made a pre-print available on the dynamics of HIV viral load suppression and resistance during the dolutegravir transition. We estimate suppresison to be at 90% among all people with HIV and 95% among those on treatment. We observe minimal DTG resistance overall but do identify the recent emergence of the inS153Y mutation, which confers about two-fold DTG resistance, with putative evidence for transmission. One of my favorite results from this work is that pre-existing NNRTI/NRTI resistance is not associated with individual-level probabilities of achieving viral load suppression in recent years, highlighting important programmatic efforts to increase suppression in this population. I had the opportunity to present this work in an oral at the [International Workshop on HIV Drug Resistance and Treatment Strategies](https://www.hivresistance.co.za). [PDF](hppts://m-a-martin.github.io/files/hiv_dtg_impact.pdf).
- Our work on HIV multiple infections in the Rakai Community Cohort Study is now published in *PLOS Pathogens*. The main results are similar to the pre-print (see below), however, we now incorporate Bayesian post-stratification to account for potential sampling biases in our sequence data. We therefore are able to estimate that ~4% of viremic PLHIV in the population (as opposed to ~6% in the sample) harbor MIs at the time of sampling. Further, we incorporated direct comparison to what I call "synthetic amplicon" data to show that using whole-genome data increases sensitivity of the method more than two-fold. [PDF](https://m-a-martin.github.io/files/hiv_mi.pdf).
## 2024
- Our preprint on HIV multiple infections in the Rakai Community Cohort Study is now available. We develop a Bayesian model to identify MIs in whole genome deep-sequence data. We use the model to show that ~6% of viremic PLHIV harbor MIs at time of sampling and that the risk of MI is ~two-fold higher in high prevalence fishing communities. [PDF](https://www.medrxiv.org/content/10.1101/2024.10.21.24314869v1.full.pdf). 
- We have considerably revised our work on the dynamics of HIV drug resistance in Rakai, Uganda in response to reviewer comments. Hopefully the revised version is more digestible for readers. [PDF](https://m-a-martin.github.io/files/rccs_resistance.pdf). 
- Our work on the within- and between-host dynamics of influenza A virus defective viral genomes is now out in [Virus Evolution](https://doi.org/10.1093/ve/veae042) [\[PDF\]](https://m-a-martin.github.io/files/influenza_dvgs.pdf). This work was (mostly) completed during my doctoral research in [Dr. Katia Koelle](https://scholarblogs.emory.edu/koellelab/)'s group. 
- I finally found the motivation to make a professional website. Thank you [Clif McKee](https://clifmckee.github.io) for the nudge. 

