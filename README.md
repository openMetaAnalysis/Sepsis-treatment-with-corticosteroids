# Septic shock treatment with corticosteroids

A living systematic review

Short url: http://openmetaanalysis.github.io/sepsis-steroids

**Clinical summary:** This meta-analysis suggests that low dose corticosteroids (<= 200 mg/d hydrocortisone), when used for 7 days or less, in patients with septic shock who are hypotensive despite pressors *is* effective at reducing mortality at one month (relative risk 0.89; 95% CI 0.81 to 0.97) see [plot](files/forest-plots/Low-dose%20steroids%20for%20mortality%20at%20one%20month%20in%20septic%20shock%20requiring%20pressors%20-%20by%20duration%20of%20steroids%20(sans%20Tandan).png)). This recommendation is limited by being an retrospective [subgroup analysis](files/forest-plots/Low-dose%20steroids%20for%20mortality%20at%20one%20month%20in%20septic%20shock%20requiring%20pressors%20-%20by%20duration%20of%20steroids%20(sans%20Tandan).png) and after excluding the trial by Tandan that did not specify duration of steroid therapy.  

While the previous Cochrane Collaboration (citation below) found significant benefit among patients with septic shock (analysis 1.5), the Cochrane used Mantel-Haenszel fixed estimator. This method may be too optimistic because the heterogenteity as measured by I<sup>2</sup> was '[moderate](http://handbook.cochrane.org/chapter_9/9_5_2_identifying_and_measuring_heterogeneity.htm)' at 57%. In this setting the Knapp-Hartung estimator may be better (PMID: [24727843](https://pubmed.gov/24727843)). Thus, prior to the publication of the APROCCHSS and ADRENAL trials in 2018, the results using the Knapp-Hartung estimator for patients with vasodependent septic shock receving low dose steroids wdid not quite reach statistical insigificance ([files/forest-plots/archives](files/forest-plots/archives)). 

Exploration of heterogeneity of results is limited by inconsistent reporting of co-treatments such as volumes of fluids and duration of pressors prior to receiving steroids. It is not clear that patients in recent trials received 30 ml/kg fluids prior to receiving pressors and steroids. 

Among the four largest trials, CORTICUS was the only one without a trend towards reduction in mortality. Of the four trials, CORTICUS continued steroids for 11 days while the other three stopped at 7 days.

The benefit among vasopressor-dependent patients does not depend on their adrenal status or co-administration of fludrocortisone (see [additional forest plots](files/forest-plots))

Two dose finding studies, that were excluded (links are below) due to not having a control group, suggest 100 mg per day of hydrcortisone may be more effective and need further examination.

Meta-regression dooes not find modulators (year of publication, study size, event rate in the control groups) on the effect of the intervention.
* [Reconciliation of conclusions and studies included with prior meta-analyses](files/reconciliation-tables/)
* [Keep current with this topic](files/searching/Keep-up.md)

Acknowledgement: we acknowledge the essential work by the authors of the prior systematic review(s) listed below.

**Methods overview:** This repository is an [openMetaAnalysis](https://openmetaanalysis.github.io/) that combines methods of scoping, rapid, and living systematic reviews.  This analysis updates one or more previously published review(s) listed below. A comparison of studies included in this review compared to prior reviews are in the table, [reconciliation of trials included with prior meta-analyses](files/reconciliation-tables/Reconciliation%20of%20studies.pdf). Newer studies included are listed in the references below. Rationale for newer trials excluded may be listed at the end of the references. 
* [Methods](http://openmetaanalysis.github.io/methods.html) for openMetaAnalysis
* [Evidence search](files/searching/evidence-search.md) for this review

**Results:** Details of the studies included are in the:
* [Reconciliation of trials included with prior meta-analyses](files/reconciliation-tables/Reconciliation%20of%20studies.pdf)
<!--- 
* [Description of studies (PICO table)](files/study-details/table-pico.pdf) (under construction)
* [Risk of bias assessment](files/study-details/table-bias.pdf) (under construction)
--->
* [Forest plots](files//forest-plots) ([source data](files/data))
* [Meta-regressions](files//metaregression) ([source data](files/data))
* [Reconciliation of conclusions with prior meta-analyses](files/reconciliation-tables/Reconciliation%20of%20conclusions.pdf)

The forest plot for the primary outcomes are below. Additional [forest plots](files/forest-plots) of secondary analyses may be available. 

![Principle results for benefit](files/forest-plots/Outcome-Primary.png "Principle results for benefit]")

The meta-regression for the primary outcomes are below. Additional [meta-regressions](files/metaregression) of secondary analyses may be available. 

![Principle results for benefit](files/metaregression/Outcome-Primary.png "Principle results for benefit]")

References:
----------------------------------
### Systematic review(s)
#### Most recent review(s) at time of last revision of this repository
1. Aletreby WT, Alharthy AM, Madi AF, Soliman IR, Hamido HM, Ramadan OE, Alzayer W, Huwait BM, Alodat MA, Mumtaz SA, Mahmood NN, Al Kurdi MH, Farrag HA, Karakitsos D. Impact on Efficacy and Safety of Hydrocortisone in Sepsis and Septic Shock - A Systematic Literature Review and Meta-analysis. Arch Iran Med. 2019 Jul 1;22(7):394-402. PMID: [31679383](http://pubmed.gov/31679383).
1. Gibbison B, López-López JA, Higgins JP, Miller T, Angelini GD, Lightman SL, Annane D. Corticosteroids in septic shock: a systematic review and network meta-analysis. Crit Care. 2017 Mar 28;21(1):78. doi: [10.1186/s13054-017-1659-4](http://dx.doi.org/10.1186/s13054-017-1659-4). PMID: [28351429](http://pubmed.gov/28351429); PMCID: [PMC5371269](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5371269/)
2. Volbeda M, Wetterslev J, Gluud C, Zijlstra JG, van der Horst IC, Keus F. Glucocorticosteroids for sepsis: systematic review with meta-analysis and trial sequential analysis. Intensive Care Med. 2015 Jul;41(7):1220-34. doi: [10.1007/s00134-015-3899-6](http://dx.doi.org/10.1007/s00134-015-3899-6). PMID: [26100123](http://pubmed.gov/26100123); PMCID: [PMC4483251](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4483251/)
3. Annane D, Bellissant E, Bollaert PE, Briegel J, Keh D, Kupfer Y. Corticosteroids for treating sepsis. Cochrane Database Syst Rev. 2015 Dec 3;(12):CD002243. doi: [10.1002/14651858.CD002243.pub3](http://dx.doi.org/10.1002/14651858.CD002243.pub3). PMID: [26633262](http://pubmed.gov/26633262)
4. Rygård SL, Butler E, Granholm A, Møller MH, Cohen J, Finfer S, Perner A, Myburgh J, Venkatesh B, Delaney A. Low-dose corticosteroids for adult patients with septic shock: a systematic review with meta-analysis and trial sequential analysis. Intensive Care Med. 2018 Jul;44(7):1003-1016. doi: 10.1007/s00134-018-5197-6. Epub 2018 May 14. Review. PubMed PMID: [29761216](http://pubmed.gov/29761216)

### Randomized controlled trials that are more recent
1. Mirea L, Ungureanu R, Pavelescu D, Grintescu I, Dumitrache C, Mirea D, et al. Impact of corticosteroid administration in septic shock on glycemic variability. Critical Care. 2014 Mar 17;18(1):P445. https://doi.org/10.1186/cc13635 *Mortality data not available in this poster but later made avaialble by Rygard, Intensive Care Med 2018 PMID [29761216](http://pubmed.gov/29761216)*
2. Tongyoo S, Permpikul C, Mongkolpun W, Vattanavanit V, Udompanturak S, Kocak M, Meduri GU. Hydrocortisone treatment in early sepsis-associated acute respiratory distress syndrome: results of a randomized controlled trial. Crit Care. 2016 Oct 15;20(1):329. PMID: [27741949](http://pubmed.gov/27741949); PMCID: [PMC5065699](https://www.ncbi.nlm.nih.gov/pmc/articles/pmid/27741949/)
3. Keh D, Trips E, Marx G, Wirtz SP, Abduljawwad E, Bercker S, et al; SepNet–Critical Care Trials Group.. Effect of Hydrocortisone on Development of Shock Among Patients With Severe Sepsis: The HYPRESS Randomized Clinical Trial. JAMA. 2016 Nov 1;316(17):1775-1785. doi: [10.1001/jama.2016.14799](http://dx.doi.org/10.1001/jama.2016.14799). PMID: [27695824](http://pubmed.gov/27695824).
4. Lv QQ, Gu XH, Chen QH, Yu JQ, Zheng RQ. Early initiation of low-dose hydrocortisone treatment for septic shock in adults: A randomized clinical trial. Am J Emerg Med. 2017 Jun 5. pii: S0735-6757(17)30444-8. doi: 10.1016/j.ajem.2017.06.004. PMID: [28615145](http://pubmed.gov/28615145)
5. Annane D, Renault A, Brun-Buisson C, Megarbane B, Quenot JP, Siami S, Cariou A, Forceville X, Schwebel C, Martin C, Timsit JF, Misset B, Ali Benali M, Colin G, Souweine B, Asehnoune K, Mercier E, Chimot L, Charpentier C, François B, Boulain T, Petitpas F, Constantin JM, Dhonneur G, Baudin F, Combes A, Bohé J, Loriferne JF, Amathieu R, Cook F, Slama M, Leroy O, Capellier G, Dargent A, Hissem T, Maxime V, Bellissant E; CRICS-TRIGGERSEP Network. Hydrocortisone plus Fludrocortisone for Adults with Septic Shock. N Engl J Med. 2018 Mar 1;378(9):809-818. doi: 10.1056/NEJMoa1705716. PMID: [29490185](http://pubmed.gov/29490185)
6. Venkatesh B, Finfer S, Cohen J, Rajbhandari D, Arabi Y, Bellomo R, Billot L, Correa M, Glass P, Harward M, Joyce C, Li Q, McArthur C, Perner A, Rhodes A, Thompson K, Webb S, Myburgh J; ADRENAL Trial Investigators and the Australian–New Zealand Intensive Care Society Clinical Trials Group. Adjunctive Glucocorticoid Therapy in Patients with Septic Shock. N Engl J Med. 2018 Mar 1;378(9):797-808. doi: 10.1056/NEJMoa1705835. Epub 2018 Jan 19. PMID: [29347874](http://pubmed.gov/29347874)


#### New study(s) undergoing review
Meta-analyses
1. Son JY, Shin S, Choi YJ. New Evidence of Potential Benefits of Dexamethasone and Added on Therapy of Fludrocortisone on Clinical Outcomes of Corticosteroid in Sepsis Patients: A Systematic Review and Meta-Analysis. J Pers Med. 2021 Jun 11;11(6):544. doi: 10.3390/jpm11060544. PMID: [34208300](http://pubmed.gov/34208300).
1. Pirracchio R, Hubbard A, Sprung CL, Chevret S, Annane D; Rapid Recognition of Corticosteroid Resistant or Sensitive Sepsis (RECORDS) Collaborators. Assessment of Machine Learning to Estimate the Individual Treatment Effect of Corticosteroids in Septic Shock. JAMA Netw Open. 2020 Dec 1;3(12):e2029050. doi: 10.1001/jamanetworkopen.2020.29050. PMID: [33301017](http://pubmed.gov/33301017);.
1. Yamamoto R, Nahara I, Toyosaki M, Fukuda T, Masuda Y, Fujishima S. Hydrocortisone with fludrocortisone for septic shock: a systematic review and meta-analysis. Acute Med Surg. 2020 Sep 1;7(1):e563. doi: 10.1002/ams2.563. PMID: [32995018](http://pubmed.gov/32995018); PMCID: PMC7507448.
1. Thompson KJ, Taylor CB, Venkatesh B, Cohen J, Hammond NE, Jan S, Li Q, Myburgh J, Rajbhandari D, Saxena M, Kumar A, Finfer SR; The ADRENAL Management Committee and Investigators and the ANZICS Clinical Trials Group. The cost-effectiveness of adjunctive corticosteroids for patients with septic shock. Crit Care Resusc. 2020 Sep;22(3):191-199. PMID: [32900325](http://pubmed.gov/32900325).
1. Zhang S, Chang W, Xie J, Wu Z, Yang Y, Qiu H. The Efficacy, Safety, and Optimal Regimen of Corticosteroids in Sepsis: A Bayesian Network Meta-Analysis. Crit Care Explor. 2020 Apr 29;2(4):e0094. doi: 10.1097/CCE.0000000000000094. PMID: [32426736](http://pubmed.gov/32426736); PMCID: PMC7188436.
1. Pourmand A, Whiteside T, Yamane D, Rashed A, Mazer-Amirshahi M. The controversial role of corticosteroids in septic shock. Am J Emerg Med. 2019 Jul;37(7):1353-1361. doi: 10.1016/j.ajem.2019.04.045. PMID: [31056383](http://pubmed.gov/31056383).
1. Archontakis Barakakis P, Palaiodimos L, Fleitas Sosa D, Benes L, Gulani P, Fein D. Combination of low-dose glucocorticosteroids and mineralocorticoids as adjunct therapy for adult patients with septic shock: A systematic review and meta-analysis of randomized trials and observational studies. Avicenna J Med. 2019 Oct 3;9(4):134-142. doi: 10.4103/ajm.AJM_97_19. PMID: [31903388](http://pubmed.gov/31903388)
1. Annane D, Bellissant E, Bollaert PE, Briegel J, Keh D, Kupfer Y, Pirracchio R, Rochwerg B. Corticosteroids for treating sepsis in children and adults. Cochrane Database Syst Rev. 2019 Dec 6;12:CD002243. doi: 10.1002/14651858.CD002243.pub4. PMID: [31808551](http://pubmed.gov/31808551)
1. Ni YN, Liu YM, Wang YW, Liang BM, Liang ZA. Can corticosteroids reduce the mortality of patients with severe sepsis? A systematic review and meta-analysis. Am J Emerg Med. 2019 Sep;37(9):1657-1664. doi: 10.1016/j.ajem.2018.11.040. Epub 2018 Nov 27. PubMed PMID: [30522935](http://pubmed.gov/30522935)
1. Aletreby WT, Alharthy AM, Madi AF, Soliman IR, Hamido HM, Ramadan OE, Alzayer W, Huwait BM, Alodat MA, Mumtaz SA, Mahmood NN, Al Kurdi MH, Farrag HA, Karakitsos D. Impact on Efficacy and Safety of Hydrocortisone in Sepsis and Septic Shock - A Systematic Literature Review and Meta-analysis. Arch Iran Med. 2019 Jul 1;22(7):394-402. PMID: [31679383](http://pubmed.gov/31679383).
1. Siddiqui WJ, Iyer P, Aftab G, Zafrullah F, Zain MA, Jethwani K, Mazhar R, Abdulsalam U, Raza A, Hanif MO, Sharma E, Aggarwal S. Hydrocortisone Reduces 28-day Mortality in Septic Patients: A Systemic Review and Meta-analysis. Cureus. 2019 Jun 17;11(6):e4914. doi: 10.7759/cureus.4914. PMID: [31423390](http://pubmed.gov/31423390)
1. Lian XJ, Huang DZ, Cao YS, Wei YX, Lian ZZ, Qin TH, He PC, Liu YH, Wang SH. Reevaluating the Role of Corticosteroids in Septic Shock: An Updated Meta-Analysis of Randomized Controlled Trials. Biomed Res Int. 2019 Jun 10;2019:3175047. doi: 10.1155/2019/3175047. eCollection 2019. PubMed PMID: [31281831](http://pubmed.gov/31281831); PubMed Central PMCID: PMC6590573
1. Moskowitz A, Huang DT, Hou PC, Gong J, Doshi PB, Grossestreuer AV, Andersen LW, Ngo L, Sherwin RL, Berg KM, Chase M, Cocchi MN, McCannon JB, Hershey M, Hilewitz A, Korotun M, Becker LB, Otero RM, Uduman J, Sen A, Donnino MW; ACTS Clinical Trial Investigators. Effect of Ascorbic Acid, Corticosteroids, and Thiamine on Organ Injury in Septic Shock: The ACTS Randomized Clinical Trial. JAMA. 2020 Aug 18;324(7):642-650. doi: 10.1001/jama.2020.11946. PMID: [32809003](http://pubmed.gov/32809003).
1. Fang F, Zhang Y, Tang J, Lunsford LD, Li T, Tang R, He J, Xu P, Faramand A, Xu J, You C. Association of Corticosteroid Treatment With Outcomes in Adult Patients With Sepsis: A Systematic Review and Meta-analysis. JAMA Intern Med. 2019 Feb 1;179(2):213-223. doi: 10.1001/jamainternmed.2018.5849. PubMed PMID: [30575845](http://pubmed.gov/30575845); PubMed Central PMCID: PMC6439648.
1. Xu R, Wang Q, Huang Y, Wu L, Liu Q, Hu W, Zhou C, Du Q. Do low-dose corticosteroids improve survival or shock reversal from septic shock in adults? Meta-analysis with trial sequential analysis. J Int Med Res. 2018 Jul;46(7):2513-2524. doi: 10.1177/0300060518774985. PMID: [29911468](http://pubmed.gov/29911468)
1. Zhu L, Li X, Liu Y, Yang K, Jing G, Chen Y, Dou Z, Chen Q, Liu J. Effects of different administration methods of hydrocortisone on blood glucose in patients with septic shock: a Meta-analysis. Zhonghua Wei Zhong Bing Ji Jiu Yi Xue. 2018 
Oct;30(10):915-919. doi: 10.3760/cma.j.issn.2095-4352.2018.010.001. Chinese. PMID: [30439307](http://pubmed.gov/30439307).
1. Rochwerg B et al. Corticosteroids in Sepsis: An Updated Systematic Review and Meta-Analysis. Crit Care Med. 2018
Sep;46(9):1411-1420. doi: 10.1097/CCM.0000000000003262. PMID: [29979221](http://pubmed.gov/29979221).
2. Lyu QQ, Chen QH, Zheng RQ, Yu JQ, Gu XH. Effect of Low-Dose Hydrocortisone Therapy in Adult Patients With Septic Shock: A Meta-Analysis With Trial Sequential Analysis of Randomized Controlled Trials. J Intensive Care Med. 2018 Oct 1:885066618803062. doi: 10.1177/0885066618803062. PMID: [30270720](http://pubmed.gov/30270720). *Found: for mortality, 11 trials (most recent 2018):  28-day mortality OR = 0.90, 95% CI = 0.81-1.00*
2. Zhou X, Hu C, Yao L, Fan Z, Sun L, Wang Y, Xu Z. Effect of adjunctive corticosteroids on clinical outcomes in adult patients with septic shock - a meta-analysis of randomized controlled trials and trial sequential analysis. J Crit Care. 2018 Sep 14;48:296-306. doi: 10.1016/j.jcrc.2018.09.013. PMID: [30269009](http://pubmed.gov/30269009) *Found: for mortality, 18 trials (most recent 2017): the pooled results from meta-analysis using random-effects model suggested that the difference in short-term mortality between both groups was not significant, with an RR of 0.92 (95%CI: 0.84–1.02, P = 0.104)*
3. Xu R, Wang Q, Huang Y, Wu L, Liu Q, Hu W, Zhou C, Du Q. Do low-dose corticosteroids improve survival or shock reversal from septic shock in adults? Meta-analysis with trial sequential analysis. J Int Med Res. 2018 Jan 1:300060518774985. doi: 10.1177/0300060518774985. PMID: [29911468](http://pubmed.gov/29911468). *Found: for mortality, 9 trials (most recent 2014):  28-day mortality (RR, 0.96; 95% CI, 0.85–1.09; TSA-adjusted 95% CI, 0.74–1.24)*
4. Mentzelopoulos SD, Koliantzaki I, Karvouniaris M, Vrettou C, Mongardon N, Karlis G, et al. Publisher Correction: Exposure to Stress-Dose Steroids and Lethal Septic Shock After In-Hospital Cardiac Arrest: Individual Patient Data Reanalysis of Two Prior Randomized Clinical Trials that Evaluated the Vasopressin-Steroids-Epinephrine Combination Versus Epinephrine Alone. Cardiovasc Drugs Ther. 2018 Sep 19. doi: 10.1007/s10557-018-6828-4. PMID: [30232658](http://pubmed.gov/30232658)

Trials
None

Other
1. Wong HR, Hart KW, Lindsell CJ, Sweeney TE. External Corroboration That Corticosteroids May Be Harmful to Septic Shock Endotype A Patients. Crit Care Med. 2020 Nov 5. doi: 10.1097/CCM.0000000000004709. PMID: [33156120](http://pubmed.gov/33156120).

#### New study(s) *excluded* 
1. Chen Z, Yang C, He H, He Z. The impacts of low-dose corticosteroids infusion given in different manners on refractory septic shock patients. Zhonghua Wei Zhong Bing Ji Jiu Yi Xue. 2015 Jun;27(6):443-7. doi: [10.3760/cma.j.issn.2095-4352.2015.06.006](http://dx.doi.org/10.3760/cma.j.issn.2095-4352.2015.06.006). Chinese. PMID: [26049181](http://pubmed.gov/26049181). *Compared modes of steroid therapies*
2. Huh JW, Choi HS, Lim CM, Koh Y, Oh YM, Shim TS, Lee SD, Kim WS, Kim DS, Hong SB. Low-dose hydrocortisone treatment for patients with septic shock: a pilot study comparing 3days with 7days. Respirology. 2011 Oct;16(7):1088-95. doi:[10.1111/j.1440-1843.2011.02018.x](http://dx.doi.org/10.1111/j.1440-1843.2011.02018.x). PMID: [21726354](http://pubmed.gov/21726354) *Compared hydrocortisone 100 mg/day for 3 days versus 7 days*
3. Hyvernat H, Barel R, Gentilhomme A, Césari-Giordani JF, Freche A, Kaidomar M,  Goubaux B, Pradier C, Dellamonica J, Bernardin G. Effects of Increasing Hydrocortisone to 300 mg Per Day in the Treatment of Septic Shock: a Pilot Study. Shock. 2016 Nov;46(5):498-505. PMID: [27405061](http://pubmed.gov/27405061) *Compared hydrocortisone 300 mg/day vs 200 mg/day*
4. Ngaosuwan K, Ounchokdee K, Chalermchai T. Clinical Outcomes of Minimized Hydrocortisone Dosage of 100 mg/day on Lower Occurrence of Hyperglycemia in Septic Shock Patients. Shock. 2017 Nov 15. doi: [10.1097/SHK.0000000000001061](http://dx.doi.org/10.1097/SHK.0000000000001061). PMID: [29176402](http://pubmed.gov/29176402). *Compared hydrocortisone 200 mg/day vs 100 mg/day*
5. Balakrishnan M, Gandhi H, Shah K, Pandya H, Patel R, Keshwani S, Yadav N. Hydrocortisone, Vitamin C and thiamine for the treatment of sepsis and septic shock following cardiac surgery. Indian J Anaesth. 2018 Dec;62(12):934-939. doi: 10.4103/ija.IJA_361_18.  PMID: [30636793](http://pubmed.gov/30636793). * Could not isolate impact of steroids*
6. Tilouche N, Jaoued O, Ali HBS, Gharbi R, Fekih Hassen M, Elatrous S. Comparison Between Continuous and Intermittent Administration of Hydrocortisone During Septic Shock: A Randomized Controlled Clinical Trial. Shock. 2019 Nov;52(5):481-486. doi: 10.1097/SHK.0000000000001316. PMID: [30628950](http://pubmed.gov/30628950). *NO placebo group*
7. Venkatesh B, Finfer S, Cohen J, Rajbhandari D, Arabi Y, Bellomo R, Billot L, Glass P, Joyce C, Li Q, McArthur C, Perner A, Rhodes A, Thompson K, Webb S, Myburgh J. Hydrocortisone Compared with Placebo in Patients with Septic Shock Satisfying the Sepsis-3 Diagnostic Criteria and APROCCHSS Study Inclusion Criteria: A Post Hoc Analysis of the ADRENAL Trial. Anesthesiology. 2019 Oct 16. doi: 10.1097/ALN.0000000000002955. PMID: [31651531](http://pubmed.gov/31651531).

#### This review has been cited by:
1. Duran BA, Badgett RG, Simpson SQ. Hydrocortisone did not reduce mortality at 90 days in patients with septic shock. Ann Intern Med. 2018 Jun 19;168(12):JC69. doi: 10.7326/ACPJC-2018-168-12-069. PMID: [29913494](http://pubmed.gov/29913494).
2. Duran BA, Badgett RG, Simpson SQ. Hydrocortisone plus fludrocortisone reduced mortality at 90 days in patients with septic shock. Ann Intern Med. 2018 Jun 19;168(12):JC68. doi: 10.7326/ACPJC-2018-168-12-068. PMID: [29913493](http://pubmed.gov/29913493).
3. WikiDoc Contributors. Septic shock treatment with corticosteroids. openMetaAnalysis. Version December 14, 2014. Available at: https://www.wikidoc.org/index.php/Sepsis_medical_therapy#Steroids. Accessed June 22, 2018.
-------------------------------
[Cite and use this content](https://github.com/openMetaAnalysis/openMetaAnalysis.github.io/blob/master/reusing.MD)  - [License](files/LICENSE.md) - [Edit this page](../../edit/master/README.md) - [History](../../commits/master/README.md)  - 
[Issues and comments](../../issues?q=is%3Aboth+is%3Aissue)

