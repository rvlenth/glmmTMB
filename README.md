# glmmTMB Working Group
This directory organizes materials and logistics for the working group. It's all up for discussion and editing. 
The subdirectory of the same name organizes the R package.

Rough daily schedule
==========
9am meet in room Y13-L-11

12-13 lunch

coffee breaks ad libitum

We could take a group excursion in the second half of the week if the weather cooperates (e.g., hike Rigi or boating on Zürichsee). We will continue to discuss the project while on the excursion, leading to new insights.

Goals for each day
==========
Monday: Orientation and Planning
----------
* Introduce participants to each other and describe expertise
* Bolker presents overview of lme4 interface
* Discuss parts of lme4 that can be reused and changes that need to be made
* Discuss goals of the workshop
	* assume all users install from source?
	* assume they install TMB or distribute DLL?
	* RE on count intercept only? ZI? slope? (Fournier input on identifiability)
	* distribution wishlist
		* Gaussian 
		* binomial
		* beta
		* beta-binomial
		* gamma
		* Poisson
		* negative binomial (also with other variance relationships)
		* t
		* tweedie
	* link wishlist
		* identity
		* log
		* logit
		* probit
		* clog-log
		* inverse
		* sqrt
		* Cauchy
	* dispersion formulas on variance for
		* Gaussian
		* beta
		* beta-binomial
		* negative binomial
		* gamma
	* correlation structure wishlist
	* features wishlist
		* summary
		* predict
		* AIC
		*confint
* Discuss code management, code style, license type
* Discuss paper 
* Discuss the variety of application data sets available for the paper
	* owls
	* toenails
	* seeds

Tuesday: Teams begin coding
------------
* Decide teams and tasks: R code, C++ code, and documentation
* Teams meet separately to discuss strategy
* Discuss inputs and outputs expected from each team so code parts are compatible
* Discuss starting values (Fournier expertise input)
* Teams work on coding
* Entire group comes together to discuss progress

Wednesday: Coding and Excursion
------------
* Teams continue coding

Thursday
------------
* Bring code pieces together
* Discuss warning messages
* Divide into new teams: debugging, documentation, and installation

Friday
------------
* Code should work on examples already
* Debugger team continues to debug extreme cases
* Documentation team works on examples and papers
* Installation team works on installation on various platforms
* Discuss future plans
