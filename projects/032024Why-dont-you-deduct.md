---
title: "Why don't you deduct to donate more?"
# permalink: /research/032024Why-dont-you-deduct.md
excerpt: 'Anecdotal evidence suggests very low rates of tax deduction for in-person donations in the field. Teaming up with a large Austrian charitable organization, we analyze their historical data and persistently document this phenomenon. To examine the reasons for this negligence of tax incentives, we first implement a representative online survey to collect beliefs on the moral perception of deduction and reasons for which people may be hesitant to deduct. The survey suggests social image concerns and a lack of information for the majority of the population as main drivers. Building on this, we run both an online and a field experiment to study the role of procedural information and social image in more detail. Our results suggest that a mere lack of information on how to deduct one’s donations cannot explain the low rates of deduction for field donations. Similarly, providing people with second-order beliefs on the moral perception of deducting did not induce a higher deduction propensity.'
# date: 2024-03-01
# venue: 'GitHub Journal of Bugs'
# paperurl: # 
# citation: #
---

#### <span style="font-size: 1.5em;">Background</span>

In 2017 Austria passed a tax-reform which shifted the administrative burden of tax deducting from the donors to the charitable organization. While before a donors had to ask for confirmation of their donation, declare their taxes and include this confirmation in the declaration, now the donor simply needs to indicate to the charity that she would like to deduct and give the charity her date of birth and adress. Thereafter, the charitable organization handles the transmission of this data to the financial authorities and the financial authorities declare the donor's taxes automatically. 

Despite this change, only 0.5% of people donating to the carol singers (Sternsingen) in the field ask for tax-deduction. 

#### <span style="font-size: 1.5em;">Step 0: measuring the effect of the tax reform</span>
1. Analysis of our several Austrian charities reveals that the tax-reform had little to no effect:
![Share of deductors among eligible donors](/projects/charity/Effect_tax_reform_donation_vol.png)
2. Our partner charity has 3 sources of revenue: donations through bank-transfers, website, in-field-donations. For the first two deduction propensity is above 50%
3. Using tick-lists we measured the deduction propensity in the field to be around 0.54%, two orders of magnitude smaller than those of the other two sources.

#### <span style="font-size: 1.5em;">Step I: Representative survey (n=314)</span>
Using a representative Austrian sample we conducted a survey to uncover people's attitudes towards tax-deducting. 
Results:
- Information
    1. Only 40% of the responders are fully informed about the steps of tax-deducting.
    2. 57% of the responders think lack of information to be a main driver of low tax-deduction rates.
- Social image concerns
    1. 88% of the responders think tax deducting is morally acceptable, while only 64% of them believe that others find it also morally acceptable. This difference of 20 percentage points points towards social image concerns as a potential driver.
- Cost-benefit considerations
    1. Responders believe on average it would take around 11 minutes to tax-deduct donations, while in practice this is less than a minute.
    2. 24% of the responders suggest cost-benefit considerations as a potential driver.

#### <span style="font-size: 1.5em;">Step II: Online experiment</span>
In our online experiment (n=483), we simulate an online economy. Participants are grouped into 20 people. After solving tasks to earn credits, their credits are taxed at a 30% rate. Participants are allowed to use their credits to donate to a charity of their choice from 9 charities. 3 of these are eligible for deduction. Donors of those charities can choose to deduct, in that, they are asked whether they would like to go through the deduction process. 

There are three treatments. Treatments differ only in the description of the game. In the control treatment, the description includes "some of these charities are eligible for deduction". In the information treatment, on top of this, participants are told which charities are eligible and how the deduction process works. In the morality treatment on top of the information treatment, participants are told that 88% of responders to a recent survey finds it morally acceptable to tax-deduct donations.


Key findings:
1. The deduction rate among donors is very high. This is very similar to the deduction rate among those who donate through the charitable organization's website.
2. Treatment has no effect on the deduction propensity.
![Share of deductors among eligible donors](/projects/charity/online_pic_1.png)
3. Morality treatment leads to higher donations in both margins.
![Share of deductors among eligible donors](/projects/charity/online_pic_2.png)
![Share of deductors among eligible donors](/projects/charity/online_pic_3.png)



#### <span style="font-size: 1.5em;">Step III: Field experiment</span>
1. Field experiment took place in Gleisdorf Austria from November 23 till January 5.
    1. Nov. 23 - Dec.3: we treated 6728 adresses in Gleisdorf, Austria.
    2. Dec.26 - Jan.5: Data collection by the carol singers. Carol singers solicited donations. The identities of the deductors were communicated to us via the charity organization.
2. Treatment included a flyer text in the form of an article in the bi-monthly issue of the parish journal. Treatment was randomized at the household level. 

Main result: Less than 0.5% of donors deduct their donations. Treatment has no effect.
![Share of deductors among eligible donors](/projects/charity/field_pic_1.png)

