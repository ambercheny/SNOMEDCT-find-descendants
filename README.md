# SNOMEDCT-find-descendants
<p xmlns:cc="http://creativecommons.org/ns#" >This work is licensed under <a href="https://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""></a></p>

This code will give you an excel sheet with ancestors and descendants columns that you need. This can be helpful for creating computational phenotypes when working with subject matter experts.

Your should download your own SNOMED CT vocabulary
https://www.nlm.nih.gov/healthit/snomedct/international.html

After downloading the package, which is SnomedCT_InternationalRF2_PRODUCTION_20240301T120000Z in this example, please set up your folder strcture like this.
(Note that you may have different directory names if using different versions)

- SNOMED 
	- > SnomedCT_InternationalRF2_PRODUCTION_20240301T120000Z
 	- > AD_find_descendants_demo.ipynb

In this example, we want to find all SNOMED IDs relevant to autoimmune diseases.
