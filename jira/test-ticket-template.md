{panel:title=DESCRIPTION}

*Portal/Application* 

[Portal/Application | ] - [Page Type | global | homepage | search results | boat details | browse | adv search | choose package | build your ad | review your ad | checkout | confirmation]

*Hypothesis*

I believe that if we reorder the presentation of Sellers’ contact information on boats.com’s boat “product pages” so that it’s easier for consumers to see the phone number, then we will increase the number of phone and email leads. If I am right, consumers will have an easier time finding the contact information they need to reach out to the Seller/Dealer/Broker.


*Problem We're Addressing*

The number of phone leads have decreased since the PDP has been redesigned.

*Goal*

Increase phone leads

*References*
* (list any spreadsheets, documents or other assets needed for this test)

{panel}

{panel:title=STAKEHOLDERS}
* name 1
* name 2
{panel}

{panel:title= ACCEPTANCE CRITERIA}
h4. {color:#14892c}Targeting{color}

_Device_:  [Device Type | all devices | desktop | tablet | mobile ]

_Page_: [Page Type | global | homepage | search results | boat details | browse | adv search | choose package | build your ad | review your ad | checkout | confirmation]

_Section_: navigation/results filter/etc

_Locales_: [Locale Type | all locales | us only | us/au/uk only | specific region(s)]
(Note: If we're using specific region(s), we'll need to make sure we have all the major cities provided in a document/spreadsheet to enter into Optimizely.)

_Traffic Allocation_: [Traffic | 50/50 | 33/33/33 | 25/25/25/25]


----

h4. {color:#14892c}Metrics{color}
- detailed pageviews
- email leads
- phone leads
- (add additional metrics, if necessary)

----
* Design Ticket Reference: ANA-101

h4. {color:#14892c}Variation 1 Requirements{color}


h5. Layout Changes
* (list design changes made)

h5. Text Changes
* (list any copy changes)
* are translations needed or can they be found within the site?

h5. Interaction Changes
* (list any new functionalities introduced by the new design)

(Create v2 section, if needed)

h5. Test Dependencies
* (list any tickets this test is relying upon, whether within the crew or a different crew)

{panel}

{panel:title=ASSET/INFORMATION REQUESTS}
* Is there information that is needed before creating the design? 
** Example: Dealer Information (Name, logo, boat listing for display, description, etc.)
{panel}

{panel:title=OUT OF SCOPE}
h5. Test Excludes:
* (list any design components that will not be included in the test)
{panel}

{panel:title=OUTSTANDING QUESTIONS}
(add any questions that could provide more context/clarity to the implementation of this test)
* are there complexities being introduced that would require further investigation?
{panel}

{panel:title=QA NOTES}
h5. {color:#f79232}Reference Links{color}
* Hotjar Heatmap - v1: http://hotjar.com
* (Create v2 heatmap, if needed)
* Optimizely Experiment: http://www.optimizely.com
* Experiment Token: ?optimizely_token

h5. {color:#f79232}Testing Instructions{color}
1. Heat maps and recordings are setup for the variation in Hotjar.
2. Open Optimizely in an incognito window.
3. Go into the Experiment Overview and verify the following:
	* Targeting: 
	* Audiences: 
	* Metrics:
	* Traffic Allocation:

4. Click into the Variations under Manage Experiment:
	* You'll have the Original and Variation(s). 
		** *Note: Make sure that the variations have unique names and not "Variation 1" and "Original"
	* Click into Variation.
	* Click Preview. This will open the page in a new tab.
	* Verify test changes with the listed Variation Requirements.
	* If you want to force a variation on a page, use the Experiment Token at the end of the url.
		** If you're testing different locales, you can: 
			*** use the locale dropdown
			*** load the new page 
			*** add the experiment token
			*** load the page again
	* If you're verifying the Audience experience, use the Preview Tool. 
		** To check if the experiment would display for an excluded audience (Example: window width less than 1280px), turn the Override Mode: Off. 
		*** [Screenshot Example]

5. Make sure to click around the experiment page to verify no bugs have been introduced.

h5. {color:#f79232}Special QA Notes{color}
* (list any special instructions a QA person will need for this specific experiment)
{panel}

{panel:title=PUBLISH EXPERIMENT}
1 Make sure no experiments are currently running on the same page.
2 Notify stakeholders before publishing experiment to production, if it's a major change to the page structure/functionality.
3 [*Start Experiment*] in Optimizely.
4 Make sure metrics are being recorded. You should be able to see results within 30mins-1hr.
{panel}

{panel:title=TEST RESULTS} 
*Launch Date*: 
*Paused Date*: 
*Experiment Visitors*: 
*Result*: 
* (list metrics and final stats)
* DPV: -1.5% (example)

*Follow-up*: (list ticket number if implementing or designing another iteration)
{panel}
